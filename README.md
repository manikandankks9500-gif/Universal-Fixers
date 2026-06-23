<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Universal Fixers | Premium Home Services on Demand</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased font-sans">

    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-screwdriver-wrench text-blue-600 text-2xl"></i>
                <span class="text-xl font-extrabold tracking-tight text-gray-900">Universal<span class="text-blue-600">Fixers</span></span>
            </div>
            <nav class="hidden md:flex space-x-8 font-medium">
                <a href="#services" class="text-gray-600 hover:text-blue-600 transition">Services</a>
                <a href="#how-it-works" class="text-gray-600 hover:text-blue-600 transition">How it Works</a>
                <a href="#become-partner" class="text-gray-600 hover:text-blue-600 transition">Join as a Professional</a>
            </nav>
            <div class="flex items-center space-x-4">
                <a href="#" class="text-gray-600 hover:text-blue-600 font-medium transition">Login</a>
                <a href="#" class="bg-blue-600 text-white px-4 py-2 rounded-lg font-medium hover:bg-blue-700 transition shadow-sm">Book Now</a>
            </div>
        </div>
    </header>

    <section class="relative bg-gradient-to-r class bg-slate-900 text-white py-24 md:py-32 overflow-hidden">
        <div class="absolute inset-0 opacity-20">
            <img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&w=1920&q=80" alt="Handyman background" class="w-full h-full object-cover">
        </div>
        <div class="relative max-w-5xl mx-auto px-4 text-center">
            <span class="bg-blue-500/20 text-blue-400 font-semibold px-4 py-1.5 rounded-full text-sm inline-block mb-4 border border-blue-500/30">Verified & Insured Professionals</span>
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight mb-6 leading-tight">
                Your Entire Home Maintenance,<br><span class="text-blue-400">Perfected on Demand.</span>
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-2xl mx-auto mb-8">
                Book top-rated plumbers, electricians, cleaners, and technicians in less than 60 seconds.
            </p>
            
            <div class="bg-white p-2 rounded-xl shadow-2xl max-w-2xl mx-auto flex flex-col md:flex-row gap-2">
                <div class="flex-1 flex items-center px-3 text-gray-500 border-b md:border-b-0 md:border-r border-gray-200 py-2">
                    <i class="fa-solid fa-location-dot mr-2 text-blue-600"></i>
                    <input type="text" placeholder="Enter your delivery location..." class="w-full bg-transparent text-gray-800 focus:outline-none placeholder-gray-400">
                </div>
                <div class="flex-1 flex items-center px-3 text-gray-500 py-2">
                    <i class="fa-solid fa-magnifying-glass mr-2 text-blue-600"></i>
                    <input type="text" placeholder="What service do you need?" class="w-full bg-transparent text-gray-800 focus:outline-none placeholder-gray-400">
                </div>
                <button class="bg-blue-600 text-white font-semibold px-6 py-3 rounded-lg hover:bg-blue-700 transition whitespace-nowrap">
                    Search Fixers
                </button>
            </div>
        </div>
    </section>

    <section id="services" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-gray-900 md:text-4xl">Our Trending Services</h2>
            <p class="text-gray-600 mt-2">Premium quality services delivered safely to your doorstep.</p>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <div class="bg-white rounded-2xl p-6 text-center shadow-sm hover:shadow-md transition border border-gray-100 cursor-pointer group">
                <div class="w-16 h-16 bg-blue-50 text-blue-600 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:bg-blue-600 group-hover:text-white transition duration-300">
                    <i class="fa-solid fa-faucet-drip text-2xl"></i>
                </div>
                <h3 class="font-bold text-gray-900 group-hover:text-blue-600 transition">Plumbing Repairs</h3>
                <p class="text-sm text-gray-500 mt-1">Leaks, Blockages & Installs</p>
            </div>

            <div class="bg-white rounded-2xl p-6 text-center shadow-sm hover:shadow-md transition border border-gray-100 cursor-pointer group">
                <div class="w-16 h-16 bg-amber-50 text-amber-600 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:bg-amber-500 group-hover:text-white transition duration-300">
                    <i class="fa-solid fa-bolt text-2xl"></i>
                </div>
                <h3 class="font-bold text-gray-900 group-hover:text-amber-600 transition">Electrical Services</h3>
                <p class="text-sm text-gray-500 mt-1">Wiring, Fixtures & Faults</p>
            </div>

            <div class="bg-white rounded-2xl p-6 text-center shadow-sm hover:shadow-md transition border border-gray-100 cursor-pointer group">
                <div class="w-16 h-16 bg-green-50 text-green-600 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:bg-green-600 group-hover:text-white transition duration-300">
                    <i class="fa-solid fa-sparkles text-2xl"></i>
                </div>
                <h3 class="font-bold text-gray-900 group-hover:text-green-600 transition">Deep Cleaning</h3>
                <p class="text-sm text-gray-500 mt-1">Full Home & Sofa Sanitization</p>
            </div>

            <div class="bg-white rounded-2xl p-6 text-center shadow-sm hover:shadow-md transition border border-gray-100 cursor-pointer group">
                <div class="w-16 h-16 bg-red-50 text-red-600 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:bg-red-600 group-hover:text-white transition duration-300">
                    <i class="fa-solid fa-screwdriver text-2xl"></i>
                </div>
                <h3 class="font-bold text-gray-900 group-hover:text-red-600 transition">Appliance Care</h3>
                <p class="text-sm text-gray-500 mt-1">AC, Fridge & Washer Repair</p>
            </div>
        </div>
    </section>

    <section id="how-it-works" class="bg-slate-900 text-white py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold md:text-4xl">Seamless Booking Experience</h2>
                <p class="text-gray-400 mt-2">Get your issues fixed in 3 effortless steps</p>
            </div>

            <div class="grid md:grid-cols-3 gap-12 relative">
                <div class="text-center relative">
                    <div class="w-12 h-12 rounded-full bg-blue-600 flex items-center justify-center text-xl font-bold mx-auto mb-4 shadow-lg shadow-blue-600/30">1</div>
                    <h3 class="text-xl font-semibold mb-2">Select a Service</h3>
                    <p class="text-gray-400">Choose from dozens of upfront-priced, upfront-scoped home services.</p>
                </div>
                <div class="text-center relative">
                    <div class="w-12 h-12 rounded-full bg-blue-600 flex items-center justify-center text-xl font-bold mx-auto mb-4 shadow-lg shadow-blue-600/30">2</div>
                    <h3 class="text-xl font-semibold mb-2">Pick Time & Schedule</h3>
                    <p class="text-gray-400">Select an immediate dispatch or a scheduled slot that perfectly fits your day.</p>
                </div>
                <div class="text-center relative">
                    <div class="w-12 h-12 rounded-full bg-blue-600 flex items-center justify-center text-xl font-bold mx-auto mb-4 shadow-lg shadow-blue-600/30">3</div>
                    <h3 class="text-xl font-semibold mb-2">Expert Arrives</h3>
                    <p class="text-gray-400">A background-checked professional arrives at your door equipped to finish the job.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div class="bg-blue-600 rounded-3xl text-white p-8 md:p-12 shadow-xl grid md:grid-cols-3 gap-8 text-center md:text-left items-center">
            <div>
                <h3 class="text-2xl md:text-3xl font-bold">Why trust Universal Fixers?</h3>
                <p class="text-blue-100 mt-2">We set the gold standard for gig-economy home solutions.</p>
            </div>
            <div class="grid grid-cols-2 md:grid-cols-2 gap-4 md:col-span-2">
                <div class="bg-blue-700/50 p-4 rounded-xl">
                    <h4 class="text-2xl font-bold">100% Verified</h4>
                    <p class="text-sm text-blue-100">Strict criminal background and credential checks.</p>
                </div>
                <div class="bg-blue-700/50 p-4 rounded-xl">
                    <h4 class="text-2xl font-bold">$5,000 Insurance</h4>
                    <p class="text-sm text-blue-100">Every job is insured against unexpected property damage.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="become-partner" class="bg-gray-100 py-20">
        <div class="max-w-5xl mx-auto px-4 grid md:grid-cols-2 gap-12 items-center">
            <div>
                <img src="https://images.unsplash.com/photo-1504328345606-18bbc8c9d7d1?auto=format&fit=crop&w=800&q=80" alt="Happy service provider" class="rounded-3xl shadow-lg w-full object-cover h-80">
            </div>
            <div>
                <span class="text-blue-600 font-bold tracking-wider uppercase text-sm">Grow Your Business</span>
                <h2 class="text-3xl font-bold text-gray-900 mt-2 mb-4">Want to earn more as a professional Fixer?</h2>
                <p class="text-gray-600 mb-6 leading-relaxed">
                    Join our network of elite contractors. Control your own hours, access a non-stop pipeline of high-paying local jobs, and get paid directly to your bank account weekly.
                </p>
                <a href="#" class="inline-block bg-slate-900 text-white font-semibold px-6 py-3 rounded-xl hover:bg-slate-800 transition">Apply as a Partner</a>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-gray-400 pt-16 pb-8 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
            <div>
                <div class="flex items-center space-x-2 text-white mb-4">
                    <i class="fa-solid fa-screwdriver-wrench text-blue-500 text-xl"></i>
                    <span class="text-lg font-extrabold tracking-tight">Universal<span class="text-blue-500">Fixers</span></span>
                </div>
                <p class="text-sm">On-demand home maintenance ecosystem designed for convenience, safety, and ultimate speed.</p>
            </div>
            <div>
                <h4 class="text-white font-semibold mb-4">Popular Services</h4>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" class="hover:text-white transition">Emergency Plumbing</a></li>
                    <li><a href="#" class="hover:text-white transition">Electrical Fault Finding</a></li>
                    <li><a href="#" class="hover:text-white transition">End of Tenancy Cleaning</a></li>
                    <li><a href="#" class="hover:text-white transition">Smart Home Setup</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-semibold mb-4">Company</h4>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" class="hover:text-white transition">About Us</a></li>
                    <li><a href="#" class="hover:text-white transition">Careers</a></li>
                    <li><a href="#" class="hover:text-white transition">Safety Trust & Guarantee</a></li>
                    <li><a href="#" class="hover:text-white transition">Contact Support</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-semibold mb-4">Download Our Apps</h4>
                <div class="space-y-3">
                    <a href="#" class="flex items-center justify-center bg-slate-800 text-white rounded-lg px-4 py-2 hover:bg-slate-700 transition border border-slate-700">
                        <i class="fa-brands fa-apple text-xl mr-3"></i>
                        <span class="text-left text-xs block"><span class="block text-[10px] uppercase text-gray-400">Download on the</span>App Store</span>
                    </a>
                    <a href="#" class="flex items-center justify-center bg-slate-800 text-white rounded-lg px-4 py-2 hover:bg-slate-700 transition border border-slate-700">
                        <i class="fa-brands fa-google-play text-xl mr-3"></i>
                        <span class="text-left text-xs block"><span class="block text-[10px] uppercase text-gray-400">Get it on</span>Google Play</span>
                    </a>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 border-t border-slate-800 pt-6 flex flex-col md:flex-row justify-between items-center text-xs">
            <p>&copy; 2026 Universal Fixers Inc. All rights reserved.</p>
            <div class="flex space-x-6 mt-4 md:mt-0">
                <a href="#" class="hover:text-white transition">Privacy Policy</a>
                <a href="#" class="hover:text-white transition">Terms of Service</a>
                <a href="#" class="hover:text-white transition">Cookie Preferences</a>
            </div>
        </div>
    </footer>

</body>
</html>
