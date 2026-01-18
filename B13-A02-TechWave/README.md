<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Techwave Landing Page</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <nav class="flex items-center justify-between px-8 py-6 bg-white border-b border-gray-200">
        <div class="text-2xl font-bold text-blue-600">Techwave</div>
        <div class="hidden md:flex space-x-8 font-medium">
            <a href="#" class="hover:text-blue-600">Solutions</a>
            <a href="#" class="hover:text-blue-600">Products</a>
            <a href="#" class="hover:text-blue-600">Resources</a>
            <a href="#" class="hover:text-blue-600">Pricing</a>
        </div>
        <div class="flex items-center space-x-4">
            <button class="px-5 py-2 font-semibold text-gray-700 hover:text-blue-600">Log in</button>
            <button class="px-5 py-2 font-semibold text-white bg-blue-600 rounded-lg hover:bg-blue-700 transition">Get Started</button>
        </div>
    </nav>

    <section class="max-w-7xl mx-auto px-8 py-20 flex flex-col md:flex-row items-center gap-12">
        <div class="md:w-1/2 space-y-6 text-center md:text-left">
            <h1 class="text-5xl md:text-6xl font-extrabold leading-tight text-gray-900">
                Unlock the Power of <span class="text-blue-600">Modern Technology</span>
            </h1>
            <p class="text-xl text-gray-600">
                Streamline your workflow with our advanced AI-driven solutions designed for high-performance teams.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center md:justify-start">
                <button class="px-8 py-4 bg-blue-600 text-white font-bold rounded-xl shadow-lg hover:bg-blue-700 transition">Start Free Trial</button>
                <button class="px-8 py-4 bg-white border border-gray-300 text-gray-700 font-bold rounded-xl hover:bg-gray-50 transition">Book a Demo</button>
            </div>
        </div>
        <div class="md:w-1/2 relative">
            <div class="w-full h-80 md:h-96 bg-blue-100 rounded-3xl overflow-hidden shadow-2xl flex items-center justify-center">
                <div class="w-3/4 h-1/2 bg-white rounded-xl shadow-md border border-blue-200"></div>
            </div>
        </div>
    </section>

    <section class="bg-white py-20">
        <div class="max-w-7xl mx-auto px-8">
            <div class="text-center mb-16 space-y-4">
                <h2 class="text-3xl font-bold text-gray-900">Designed for Productivity</h2>
                <p class="text-gray-500 max-w-2xl mx-auto">Everything you need to manage your infrastructure in one intuitive dashboard.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-8 border border-gray-100 rounded-2xl bg-gray-50 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-blue-600 text-white rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Fast Implementation</h3>
                    <p class="text-gray-600">Get up and running in minutes with our simple integration guides[cite: 190].</p>
                </div>

                <div class="p-8 border border-gray-100 rounded-2xl bg-gray-50 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-green-500 text-white rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Secure by Default</h3>
                    <p class="text-gray-600">Enterprise-grade security protocols applied to every data point[cite: 191].</p>
                </div>

                <div class="p-8 border border-gray-100 rounded-2xl bg-gray-50 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-purple-600 text-white rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"/></svg>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Real-time Analytics</h3>
                    <p class="text-gray-600">Track your progress with customizable dashboards and live reporting[cite: 195].</p>
                </div>
            </div>
        </div>
    </section>

</body>
</html>