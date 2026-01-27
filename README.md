<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Online Aswar</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800">

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-blue-600">ASW-Shop</a>
            <div class="space-x-6 hidden md:flex">
                <a href="#" class="hover:text-blue-600">Beranda</a>
                <a href="#" class="hover:text-blue-600">Kategori</a>
                <a href="#" class="hover:text-blue-600">Promo</a>
            </div>
            <div class="flex items-center space-x-4">
                <i class="fa-solid fa-magnifying-glass cursor-pointer"></i>
                <div class="relative">
                    <i class="fa-solid fa-cart-shopping text-xl cursor-pointer"></i>
                    <span class="absolute -top-2 -right-2 bg-red-500 text-white text-xs rounded-full px-1">3</span>
                </div>
            </div>
        </div>
    </nav>

    <header class="bg-blue-600 text-white py-20 px-6 text-center">
        <h1 class="text-4xl md:text-6xl font-extrabold mb-4">Diskon Gila Awal Tahun!</h1>
        <p class="text-lg mb-8 text-blue-100">Dapatkan produk impianmu dengan harga termurah se-Indonesia.</p>
        <a href="#produk" class="bg-white text-blue-600 px-8 py-3 rounded-full font-bold hover:bg-gray-100 transition">Belanja Sekarang</a>
    </header>

    <main id="produk" class="container mx-auto px-6 py-12">
        <h2 class="text-3xl font-bold mb-8 border-l-4 border-blue-600 pl-4">Produk Terbaru</h2>
        
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
            <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-2xl transition duration-300">
                <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" alt="Sepatu" class="w-full h-48 object-cover">
                <div class="p-4">
                    <span class="text-xs text-gray-400 uppercase">Lifestyle</span>
                    <h3 class="font-bold text-lg mb-2">Sepatu Sport Red-X</h3>
                    <p class="text-blue-600 font-bold mb-4">Rp 750.000</p>
                    <button class="w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700 transition">
                        + Keranjang
                    </button>
                </div>
            </div>

            <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-2xl transition duration-300">
                <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e" alt="Headphone" class="w-full h-48 object-cover">
                <div class="p-4">
                    <span class="text-xs text-gray-400 uppercase">Elektronik</span>
                    <h3 class="font-bold text-lg mb-2">Headphone Bass Boost</h3>
                    <p class="text-blue-600 font-bold mb-4">Rp 1.200.000</p>
                    <button class="w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700 transition">
                        + Keranjang
                    </button>
                </div>
            </div>
            
            </div>
    </main>

    <footer class="bg-gray-900 text-white py-10 mt-12 text-center">
        <p>&copy; 2026 Aswar E-Commerce. All Rights Reserved.</p>
    </footer>

</body>
</html>
