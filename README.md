<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shopping Site</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900">

   
  <header class="bg-white shadow-md">
    <div class="container mx-auto flex items-center justify-between px-4 py-3">
      
      <!-- Logo -->
      <h1 class="text-xl font-bold text-blue-600">ShopEase</h1>
      
      <nav class="hidden md:flex gap-6">
        <a href="#" class="hover:text-blue-600">Home</a>
        <a href="#" class="hover:text-blue-600">Shop</a>
        <a href="#" class="hover:text-blue-600">About</a>
        <a href="#" class="hover:text-blue-600">Contact</a>
      </nav>
      
      <!-- Mobile menu button -->
      <button class="md:hidden text-gray-600 focus:outline-none">
        ☰
      </button>
    </div>
  </header>
  <section class="bg-blue-100 py-12 text-center">
    <h2 class="text-3xl md:text-4xl font-bold mb-4">Big Sale is Live!</h2>
    <p class="text-lg mb-6">Up to 50% off on selected items</p>
    <a href="#" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700">Shop Now</a>
  </section>

  <!--Products section -->
  <section class="container mx-auto px-4 py-12">
    <h3 class="text-2xl font-semibold mb-6 text-center">Featured Products</h3>
    
    <!-- mobile me 1 col, small tablets me 2, laptops me 3, large screen me 4 -->
    <div class="grid gap-6 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4">
      
      <!--Products -->
     
       <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <img src="./electronics.jpg" alt="Product 1" class="w-full h-48 object-cover rounded">
        <h4 class="mt-4 text-lg font-semibold">Electronic Products</h4>
        <p class="text-gray-600">50% Disscount</p>
        <button class="mt-2 w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
      </div>
       <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <img src="./makeup products.jpg" alt="Product 1" class="w-full h-48 object-cover rounded">
        <h4 class="mt-4 text-lg font-semibold">Beauty Products</h4>
        <p class="text-gray-600">50% Disscount</p>
        <button class="mt-2 w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
      </div> <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <img src="./phones.jpg" alt="Product 1" class="w-full h-48 object-cover rounded">
        <h4 class="mt-4 text-lg font-semibold">Phones</h4>
        <p class="text-gray-600">50% Disscount</p>
        <button class="mt-2 w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
      </div> <div class="bg-white p-4 rounded-lg shadow hover:shadow-lg transition">
        <img src="./stationaries.jpg" alt="Product 1" class="w-full h-48 object-cover rounded">
        <h4 class="mt-4 text-lg font-semibold">Stationary Products</h4>
        <p class="text-gray-600">50% Disscount</p>
        <button class="mt-2 w-full bg-blue-600 text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
      </div>

     
    </div>
  </section>

  <!--neeche ka hissa -->
  <footer class="bg-gray-800 text-white py-6 text-center">
    <p>&copy; 2025 ShopEase. All rights reserved.</p>
  </footer>

</body>
</html># Indikraft.in-task-4
