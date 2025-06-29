

`anik_shandilya_ store_beauty.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anik Shandilya | Beauty Boutique</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fef6f6;
        }
        
        .logo-text {
            background: linear-gradient(45deg, #f37171, #ff6600);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 700;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .wave-shape {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            overflow: hidden;
            line-height: 0;
        }
        
        .wave-shape svg {
            position: relative;
            display: block;
            width: calc(100% + 1.3px);
            height: 100px;
        }
    </style>
</head>
<body>
    <!-- Header with Logo -->
    <header class="bg-white shadow-sm py-4 sticky top-0 z-50">
        <div class="container mx-auto px-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <img src="https://placehold.co/100x100" alt="Anik Shandilya logo mark - abstract beauty symbol with soft pink and gold colors" class="h-12 w-12 rounded-full">
                <h1 class="text-3xl logo-text">Anik Shandilya</h1>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">Home</a>
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">Shop</a>
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">About</a>
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">Contact</a>
            </nav>
            <div class="flex items-center space-x-4">
                <button class="p-2 rounded-full bg-gray-100 hover:bg-pink-100">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                </button>
                <button class="p-2 rounded-full bg-gray-100 hover:bg-pink-100">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                    </svg>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-gradient-to-r from-pink-100 to-orange-50 py-20 overflow-hidden">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">Discover Your Beauty</h2>
                <p class="text-lg text-gray-600 mb-8">Premium beauty products curated by Anik Shandilya for your perfect look.</p>
                <button class="bg-gradient-to-r from-pink-500 to-orange-500 text-white px-6 py-3 rounded-full font-medium hover:opacity-90 transition">Shop Now</button>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://placehold.co/600x400" alt="Elegant display of luxury beauty products including skincare serums, makeup brushes, and perfumes arranged artfully" class="rounded-lg shadow-xl">
            </div>
        </div>
        <div class="wave-shape">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.63,43,919.64,70.2,1000,120H0V0Z" class="shape-fill"></path>
            </svg>
        </div>
    </section>

    <!-- Trending Products Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Trending Beauty Products</h2>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://placehold.co/500x500" alt="Hyaluronic Acid Serum in sleek glass bottle with dropper, product shown on marble surface" class="w-full h-64 object-cover">
                        <span class="absolute top-4 right-4 bg-pink-500 text-white text-xs px-2 py-1 rounded-full">BESTSELLER</span>
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">Hyaluronic Acid Serum</h3>
                        <p class="text-sm text-gray-600 mb-2">Deep hydration for plump, youthful skin</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$24.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://placehold.co/500x500" alt="Vitamin C Brightening Cream in gold jar with elegant typography, product surrounded by citrus fruits" class="w-full h-64 object-cover">
                        <span class="absolute top-4 right-4 bg-orange-500 text-white text-xs px-2 py-1 rounded-full">NEW</span>
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">Vitamin C Brightening Cream</h3>
                        <p class="text-sm text-gray-600 mb-2">Illuminate and even skin tone</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$29.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://placehold.co/500x500" alt="Rose Quartz Facial Roller with pink background, product shown with rose petals" class="w-full h-64 object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">Rose Quartz Facial Roller</h3>
                        <p class="text-sm text-gray-600 mb-2">Reduce puffiness & enhance absorption</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$19.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://placehold.co/500x500" alt="CBD Infused Night Cream in dark green packaging, product shown with lavender flowers" class="w-full h-64 object-cover">
                        <span class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full">TRENDING</span>
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">CBD Night Repair Cream</h3>
                        <p class="text-sm text-gray-600 mb-2">Calm & restore while you sleep</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$34.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="border border-pink-500 text-pink-500 px-6 py-2 rounded-full font-medium hover:bg-pink-50 transition">View All Products</button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center p-6">
                    <div class="bg-pink-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15l8-8m0 0h-6m6 0v6" />
                        </svg>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Free Shipping</h3>
                    <p class="text-gray-600">On all orders over $50</p>
                </div>
                <div class="text-center p-6">
                    <div class="bg-pink-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                        </svg>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Quality Guarantee</h3>
                    <p class="text-gray-600">100% satisfaction or money back</p>
                </div>
                <div class="text-center p-6">
                    <div class="bg-pink-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z" />
                        </svg>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Secure Payment</h3>
                    <p class="text-gray-600">Safe & encrypted transactions</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="py-16 bg-gradient-to-r from-pink-500 to-orange-500 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">Subscribe to Our Newsletter</h2>
            <p class="mb-8 max-w-2xl mx-auto">Get exclusive beauty tips, new product launches, and special offers delivered straight to your inbox.</p>
            <div class="max-w-md mx-auto flex">
                <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 rounded-l-full focus:outline-none text-gray-800">
                <button class="bg-black px-6 py-3 rounded-r-full font-medium hover:bg-gray-800 transition">Subscribe</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <img src="https://placehold.co/100x100" alt="Anik Shandilya brand logo mark - abstract beauty symbol in white" class="h-10 w-10 rounded-full">
                        <h3 class="text-2xl text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-orange-300 font-bold">Anik Shandilya</h3>
                    </div>
                    <p class="text-gray-400">Premium beauty products curated for your perfect look.</p>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Shop</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Skincare</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Makeup</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Haircare</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Best Sellers</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Help</h4>
                    <ul class="space-y-2">
```

🎨 **Generating images based on descriptions...**

✅ **Images generated successfully! Here's your updated content:**

`anik_shandilya_beauty.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anik Shandilya | Beauty Boutique</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fef6f6;
        }
        
        .logo-text {
            background: linear-gradient(45deg, #f37171, #ff6600);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 700;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .wave-shape {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            overflow: hidden;
            line-height: 0;
        }
        
        .wave-shape svg {
            position: relative;
            display: block;
            width: calc(100% + 1.3px);
            height: 100px;
        }
    </style>
</head>
<body>
    <!-- Header with Logo -->
    <header class="bg-white shadow-sm py-4 sticky top-0 z-50">
        <div class="container mx-auto px-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d463f45d-ede8-4f63-b23d-fbca9da2d6a9.png" alt="Anik Shandilya logo mark - abstract beauty symbol with soft pink and gold colors" class="h-12 w-12 rounded-full">
                <h1 class="text-3xl logo-text">Anik Shandilya</h1>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">Home</a>
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">Shop</a>
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">About</a>
                <a href="#" class="text-gray-700 hover:text-pink-500 font-medium">Contact</a>
            </nav>
            <div class="flex items-center space-x-4">
                <button class="p-2 rounded-full bg-gray-100 hover:bg-pink-100">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                </button>
                <button class="p-2 rounded-full bg-gray-100 hover:bg-pink-100">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                    </svg>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-gradient-to-r from-pink-100 to-orange-50 py-20 overflow-hidden">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">Discover Your Beauty</h2>
                <p class="text-lg text-gray-600 mb-8">Premium beauty products curated by Anik Shandilya for your perfect look.</p>
                <button class="bg-gradient-to-r from-pink-500 to-orange-500 text-white px-6 py-3 rounded-full font-medium hover:opacity-90 transition">Shop Now</button>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/5b202314-3e8e-4e12-9b7e-915aa8892278.png" alt="Elegant display of luxury beauty products including skincare serums, makeup brushes, and perfumes arranged artfully" class="rounded-lg shadow-xl">
            </div>
        </div>
        <div class="wave-shape">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.63,43,919.64,70.2,1000,120H0V0Z" class="shape-fill"></path>
            </svg>
        </div>
    </section>

    <!-- Trending Products Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Trending Beauty Products</h2>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/b4eb282f-b7e2-4289-abab-16b10ae6255b.png" alt="Hyaluronic Acid Serum in sleek glass bottle with dropper, product shown on marble surface" class="w-full h-64 object-cover">
                        <span class="absolute top-4 right-4 bg-pink-500 text-white text-xs px-2 py-1 rounded-full">BESTSELLER</span>
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">Hyaluronic Acid Serum</h3>
                        <p class="text-sm text-gray-600 mb-2">Deep hydration for plump, youthful skin</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$24.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/3765ba18-eb2f-4d00-b9ca-000758ec0a2f.png" alt="Vitamin C Brightening Cream in gold jar with elegant typography, product surrounded by citrus fruits" class="w-full h-64 object-cover">
                        <span class="absolute top-4 right-4 bg-orange-500 text-white text-xs px-2 py-1 rounded-full">NEW</span>
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">Vitamin C Brightening Cream</h3>
                        <p class="text-sm text-gray-600 mb-2">Illuminate and even skin tone</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$29.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/0528d697-dbea-42c3-a42d-791590afcff5.png" alt="Rose Quartz Facial Roller with pink background, product shown with rose petals" class="w-full h-64 object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">Rose Quartz Facial Roller</h3>
                        <p class="text-sm text-gray-600 mb-2">Reduce puffiness & enhance absorption</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$19.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ac2952d8-fabf-4299-ba70-fe92b6d0a4c6.png" alt="CBD Infused Night Cream in dark green packaging, product shown with lavender flowers" class="w-full h-64 object-cover">
                        <span class="absolute top-4 right-4 bg-green-500 text-white text-xs px-2 py-1 rounded-full">TRENDING</span>
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-gray-800 mb-1">CBD Night Repair Cream</h3>
                        <p class="text-sm text-gray-600 mb-2">Calm & restore while you sleep</p>
                        <div class="flex items-center justify-between">
                            <span class="font-bold text-pink-600">$34.99</span>
                            <button class="bg-pink-100 text-pink-500 px-3 py-1 rounded-full text-sm hover:bg-pink-200">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="border border-pink-500 text-pink-500 px-6 py-2 rounded-full font-medium hover:bg-pink-50 transition">View All Products</button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center p-6">
                    <div class="bg-pink-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15l8-8m0 0h-6m6 0v6" />
                        </svg>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Free Shipping</h3>
                    <p class="text-gray-600">On all orders over $50</p>
                </div>
                <div class="text-center p-6">
                    <div class="bg-pink-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                        </svg>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Quality Guarantee</h3>
                    <p class="text-gray-600">100% satisfaction or money back</p>
                </div>
                <div class="text-center p-6">
                    <div class="bg-pink-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z" />
                        </svg>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Secure Payment</h3>
                    <p class="text-gray-600">Safe & encrypted transactions</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="py-16 bg-gradient-to-r from-pink-500 to-orange-500 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">Subscribe to Our Newsletter</h2>
            <p class="mb-8 max-w-2xl mx-auto">Get exclusive beauty tips, new product launches, and special offers delivered straight to your inbox.</p>
            <div class="max-w-md mx-auto flex">
                <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 rounded-l-full focus:outline-none text-gray-800">
                <button class="bg-black px-6 py-3 rounded-r-full font-medium hover:bg-gray-800 transition">Subscribe</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/86452fef-e970-46b8-8f52-6bd78ce0f639.png" alt="Anik Shandilya brand logo mark - abstract beauty symbol in white" class="h-10 w-10 rounded-full">
                        <h3 class="text-2xl text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-orange-300 font-bold">Anik Shandilya</h3>
                    </div>
                    <p class="text-gray-400">Premium beauty products curated for your perfect look.</p>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Shop</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Skincare</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Makeup</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Haircare</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-pink-300 transition">Best Sellers</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Help</h4>
                    <ul class="space-y-2">
```
