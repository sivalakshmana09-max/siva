# siva
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elite Dwellings | Real Estate</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 font-sans">

    <nav class="flex justify-between items-center px-10 py-6 bg-white shadow-sm">
        <div class="text-2xl font-bold text-blue-900">ELITE DWELLINGS</div>
        <ul class="hidden md:flex space-x-8 text-gray-600 font-medium">
            <li class="hover:text-blue-900 cursor-pointer">Buy</li>
            <li class="hover:text-blue-900 cursor-pointer">Rent</li>
            <li class="hover:text-blue-900 cursor-pointer">Sell</li>
            <li class="hover:text-blue-900 cursor-pointer">About</li>
        </ul>
        <button class="bg-blue-900 text-white px-6 py-2 rounded-full hover:bg-blue-800 transition">Contact Us</button>
    </nav>

    <section class="relative h-[500px] flex items-center justify-center bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1200&q=80');">
        <div class="absolute inset-0 bg-black opacity-40"></div>
        <div class="relative z-10 text-center text-white px-4">
            <h1 class="text-5xl font-extrabold mb-4">Find Your Perfect Sanctuary</h1>
            <p class="text-xl mb-8">Discover luxury homes tailored to your lifestyle.</p>
            
            <div class="bg-white p-4 rounded-lg shadow-xl flex flex-col md:flex-row gap-4 max-w-4xl mx-auto">
                <input type="text" placeholder="Location..." class="flex-1 p-3 text-gray-800 border rounded focus:outline-none focus:ring-2 focus:ring-blue-500">
                <select class="p-3 text-gray-800 border rounded">
                    <option>Price Range</option>
                    <option>$200k - $500k</option>
                    <option>$500k - $1M</option>
                </select>
                <button class="bg-blue-900 text-white px-10 py-3 rounded font-bold hover:bg-blue-800 transition">Search</button>
            </div>
        </div>
    </section>

    <section class="max-w-7xl mx-auto py-16 px-6">
        <h2 class="text-3xl font-bold text-gray-900 mb-8">Featured Properties</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            
            <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-2xl transition duration-300">
                <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=600&q=80" alt="Home" class="w-full h-56 object-cover">
                <div class="p-6">
                    <span class="text-blue-600 font-bold">$1,250,000</span>
                    <h3 class="text-xl font-semibold mt-2">The Glass Pavilion</h3>
                    <p class="text-gray-500 text-sm mt-1">Beverly Hills, CA</p>
                    <div class="flex justify-between mt-4 text-gray-600 text-sm border-t pt-4">
                        <span>4 Beds</span>
                        <span>3 Baths</span>
                        <span>3,200 sqft</span>
                    </div>
                </div>
            </div>

            </div>
    </section>

</body>
</html>
