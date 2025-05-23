<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Easy UST</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <link href="https://cdn.jsdelivr.net/npm/lucide@latest/dist/umd/lucide.min.js" rel="stylesheet">
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body class="bg-gradient-to-br from-indigo-200 via-pink-100 to-yellow-100 p-4 min-h-screen">
  <nav class="flex justify-between items-center bg-white p-4 rounded-xl shadow-md mb-6 sticky top-0 z-50">
    <h1 class="text-xl font-bold text-indigo-700">Easy UST</h1>
    <div class="space-x-4 text-sm">
      <a href="#home" class="text-gray-700 hover:text-indigo-600">Home</a>
      <a href="#about" class="text-gray-700 hover:text-indigo-600">About</a>
      <a href="#features" class="text-gray-700 hover:text-indigo-600">Features</a>
      <a href="#login" class="text-gray-700 hover:text-indigo-600">Login</a>
    </div>
  </nav>

  <section id="home">
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
      <div class="bg-white p-4 rounded-2xl shadow-md flex gap-4 items-center">
        <div><i data-lucide="users" class="w-8 h-8 text-blue-600"></i></div>
        <div>
          <h2 class="text-lg font-semibold">At-Risk Students</h2>
          <p class="text-sm text-gray-500">Identify students with low performance</p>
        </div>
      </div>

      <div class="bg-white p-4 rounded-2xl shadow-md flex gap-4 items-center">
        <div><i data-lucide="bar-chart-2" class="w-8 h-8 text-green-600"></i></div>
        <div>
          <h2 class="text-lg font-semibold">Resource Usage</h2>
          <p class="text-sm text-gray-500">Monitor classroom and lab utilization</p>
        </div>
      </div>

      <div class="bg-white p-4 rounded-2xl shadow-md flex gap-4 items-center">
        <div><i data-lucide="calendar-check" class="w-8 h-8 text-purple-600"></i></div>
        <div>
          <h2 class="text-lg font-semibold">Attendance Trends</h2>
          <p class="text-sm text-gray-500">Track attendance across semesters</p>
        </div>
      </div>

      <div class="bg-white p-4 rounded-2xl shadow-md flex gap-4 items-center">
        <div><i data-lucide="bar-chart-2" class="w-8 h-8 text-orange-600"></i></div>
        <div>
          <h2 class="text-lg font-semibold">Performance Forecast</h2>
          <p class="text-sm text-gray-500">Predict academic outcomes</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="mt-16 bg-white p-6 rounded-2xl shadow-md max-w-4xl mx-auto">
    <h2 class="text-xl font-bold text-center mb-4">About Easy UST</h2>
    <p class="text-gray-700 text-sm">Easy UST is a university performance and resource optimization system that applies signal processing and data analysis techniques to improve resource allocation and student outcomes. It integrates various data streams including student grades, attendance, and resource usage.</p>
  </section>

  <section id="features" class="mt-16 bg-white p-6 rounded-2xl shadow-md max-w-4xl mx-auto">
    <h2 class="text-xl font-bold text-center mb-4">Key Features</h2>
    <ul class="list-disc list-inside text-sm text-gray-700">
      <li>Student performance trend analysis</li>
      <li>Classroom and lab resource optimization</li>
      <li>Anomaly detection in data patterns</li>
      <li>Predictive analytics for student success</li>
      <li>Interactive dashboards and reports</li>
    </ul>
  </section>

  <section id="login" class="mt-16 max-w-md mx-auto bg-white p-6 rounded-2xl shadow-md">
    <h2 class="text-xl font-semibold text-center mb-4">Login</h2>
    <form class="space-y-4">
      <div>
        <label for="userId" class="block text-sm font-medium text-gray-700">User ID</label>
        <input type="text" id="userId" name="userId" class="mt-1 w-full px-3 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required />
      </div>
      <div>
        <label for="password" class="block text-sm font-medium text-gray-700">Password</label>
        <input type="password" id="password" name="password" class="mt-1 w-full px-3 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" required />
      </div>
      <div class="text-center">
        <button type="submit" class="px-6 py-2 bg-blue-600 text-white rounded-xl hover:bg-blue-700">Login</button>
      </div>
    </form>
  </section>

  <footer class="mt-16 text-center text-xs text-gray-500">
    &copy; 2025 Easy UST. All rights reserved.
  </footer>

  <script>
    lucide.createIcons();
  </script>
</body>
</html>

