<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coding Websites</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&family=Dancing+Script&display=swap" rel="stylesheet">
    <link href="codingwebsites.css" rel="stylesheet">
    <style>
         body {
            font-family: 'Inter', sans-serif;
            overflow: hidden; /* Prevent scroll for the background elements */
        }
        .bg-gradient-custom {
            background: linear-gradient(135deg, #6A5ACD, #483D8B); /* Deeper purple gradient */
        }
        .font-dancing-script {
            font-family: 'Dancing Script', cursive;
        }
        /* Custom styles for abstract shapes - these would typically be SVG or generated via JS for true 3D */
        .shape-sphere {
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 50%;
            filter: blur(20px);
        }
        .shape-cylinder {
            background-color: rgba(255, 255, 255, 0.15);
            border-radius: 9999px; /* Pill shape */
            filter: blur(15px);
        }
    </style>
</head>
<body class="bg-gradient-custom text-white min-h-screen flex flex-col relative">

    <!-- Abstract Shapes (simplified for demonstration) -->
    <div class="absolute top-1/4 left-1/4 w-40 h-40 shape-sphere transform -translate-x-1/2 -translate-y-1/2"></div>
    <div class="absolute top-1/2 right-1/4 w-32 h-32 shape-sphere transform translate-x-1/2 -translate-y-1/2"></div>
    <div class="absolute bottom-1/4 left-1/3 w-20 h-20 shape-sphere transform -translate-x-1/2 translate-y-1/2"></div>

    <div class="absolute top-1/3 left-0 w-80 h-16 shape-cylinder transform -rotate-45 -translate-x-1/2"></div>
    <div class="absolute bottom-1/3 right-0 w-60 h-12 shape-cylinder transform rotate-45 translate-x-1/2"></div>

    <!-- Navigation Bar -->
    <nav class="p-6 flex justify-end z-10">
        <div class="flex space-x-6">
            <a href="CodingWindow.html" class="text-white hover:text-gray-300 transition-colors duration-200">Home</a>
            <a href="Get started-1.html" class="text-white hover:text-gray-300 transition-colors duration-200">Get Started</a>
            <a href="Sign in-1.html" class="text-white hover:text-gray-300 transition-colors duration-200">Sign In</a>
            <a href="Signup.html" class="text-white hover:text-gray-300 transition-colors duration-200">Sign Up</a>
            <a href="loginthroughsocial.html" class="text-white hover:text-gray-300 transition-colors duration-200">Social Login</a>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="flex-grow flex flex-col items-center justify-center text-center p-6 z-10">
        <h1 class="text-6xl md:text-8xl lg:text-9xl font-bold mb-4">
            <span class="font-dancing-script block leading-none mb-4" style="text-shadow: 2px 2px 4px rgba(0,0,0,0.3);">Coding</span>
            <span class="block leading-none" style="text-shadow: 2px 2px 4px rgba(0,0,0,0.3);">Websites</span>
        </h1>
        <button class="mt-8 px-8 py-3 border border-white text-white rounded-full hover:bg-white hover:text-purple-700 transition-all duration-300 shadow-lg">
            Start Coding 
        </button>
    </main>

    <!-- Optional: Add a subtle footer or other elements -->
    <footer class="p-4 text-center text-white text-sm opacity-75 z-10">
        &copy; 2025 Your Company. All rights reserved.
    </footer>

</body>
</html>
