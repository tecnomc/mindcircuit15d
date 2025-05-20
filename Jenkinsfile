<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Web Page</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Navigation Bar -->
    <nav class="bg-blue-600 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">My Website</h1>
            <ul class="flex space-x-6">
                <li><a href="#" class="hover:text-gray-200">Home</a></li>
                <li><a href="#" class="hover:text-gray-200">About</a></li>
                <li><a href="#" class="hover:text-gray-200">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container mx-auto mt-8 p-4">
        <section class="bg-white rounded-lg shadow-md p-6">
            <h2 class="text-3xl font-semibold text-gray-800">Welcome!</h2>
            <p class="mt-4 text-gray-600">This is a sample web page built with HTML, Tailwind CSS, and JavaScript.</p>
            <button id="greetButton" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">
                Click Me!
            </button>
            <p id="greeting" class="mt-4 text-gray-600"></p>
        </section>
    </main>

    <!-- JavaScript -->
    <script>
        document.getElementById('greetButton').addEventListener('click', () => {
            const greeting = document.getElementById('greeting');
            greeting.textContent = 'Hello! Thanks for clicking the button!';
        });
    </script>
</body>
</html>
