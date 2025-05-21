pipeline {
    agent any
	tools{
	maven 'maven_3.9.9'
	}
    stages {
	
        stage('Clone GIT Repo') {
            steps {
                echo 'Cloning code from Github Repo'
				git branch: 'main', url: 'https://github.com/tecnomc/mindcircuit15d.git'
			
            }
        }
		
		 stage('Build Artifact') {
            steps {
                echo 'Building Artifact using maven build tool'
				sh 'mvn clean install'
				
            }
        }
		
	   stage('Deploy to Tomcat') {
            steps {
                echo 'Deploying artifact on to Tomcat'
				
				deploy adapters: [tomcat9(alternativeDeploymentContext: '', path: '', url: 'http://18.233.160.31:8080/')], contextPath: 'mcapp', war: '**/*.war'
            }
        }
			
		
    }
}
