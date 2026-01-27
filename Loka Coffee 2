<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loka Coffee - Pro Version</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        body { background-color: #2D1B14; font-family: 'Segoe UI', sans-serif; }
        .coffee-card { background-color: #F5E6D3; transition: transform 0.2s; }
        .coffee-card:active { transform: scale(0.95); }
    </style>
</head>
<body class="flex justify-center min-h-screen">

    <div class="w-full max-w-md bg-[#3D2B1F] min-h-screen relative flex flex-col shadow-2xl">
        
        <header class="pt-8 pb-4 text-center">
            <i class="fa-solid fa-mug-hot text-[#D4A373] text-5xl mb-2"></i>
            <h1 class="text-2xl font-black text-[#F5E6D3] tracking-tighter italic">LOKA COFFEE</h1>
            <p class="text-[#D4A373] text-xs">Premium Taste, Local Soul</p>
        </header>

        <main class="flex-1 px-4 py-4 pb-24">
            <div class="grid grid-cols-2 gap-3">
                
                <div class="coffee-card rounded-2xl p-3 flex flex-col shadow-md">
                    <img src="https://images.unsplash.com/photo-1510707577719-af7c183f1e59?w=300" class="w-full h-32 rounded-xl object-cover mb-2">
                    <h3 class="font-bold text-sm leading-tight mb-1">Espresso Roast</h3>
                    <p class="text-[#2D1B14] font-black text-sm mb-3">$10.00</p>
                    <button onclick="sendToWA('Espresso Roast', '10.00')" class="bg-[#7B3F00] text-white text-[10px] py-2 rounded-lg font-bold">
                        BELI SEKARANG
                    </button>
                </div>

                <div class="coffee-card rounded-2xl p-3 flex flex-col shadow-md">
                    <img src="https://images.unsplash.com/photo-1461023233037-2419b69b8941?w=300" class="w-full h-32 rounded-xl object-cover mb-2">
                    <h3 class="font-bold text-sm leading-tight mb-1">Signature Cold</h3>
                    <p class="text-[#2D1B14] font-black text-sm mb-3">$12.00</p>
                    <button onclick="sendToWA('Signature Cold', '12.00')" class="bg-[#7B3F00] text-white text-[10px] py-2 rounded-lg font-bold">
                        BELI SEKARANG
                    </button>
                </div>

                <div class="coffee-card rounded-2xl p-3 flex flex-col shadow-md">
                    <img src="https://images.unsplash.com/photo-1541167760496-162955ed8a9f?w=300" class="w-full h-32 rounded-xl object-cover mb-2">
                    <h3 class="font-bold text-sm leading-tight mb-1">Vanilla Latte</h3>
                    <p class="text-[#2D1B14] font-black text-sm mb-3">$9.50</p>
                    <button onclick="sendToWA('Vanilla Latte', '9.50')" class="bg-[#7B3F00] text-white text-[10px] py-2 rounded-lg font-bold">
                        BELI SEKARANG
                    </button>
                </div>

                <div class="coffee-card rounded-2xl p-3 flex flex-col shadow-md">
                    <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=300" class="w-full h-32 rounded-xl object-cover mb-2">
                    <h3 class="font-bold text-sm leading-tight mb-1">Caramel Macchiato</h3>
                    <p class="text-[#2D1B14] font-black text-sm mb-3">$11.00</p>
                    <button onclick="sendToWA('Caramel Macchiato', '11.00')" class="bg-[#7B3F00] text-white text-[10px] py-2 rounded-lg font-bold">
                        BELI SEKARANG
                    </button>
                </div>

            </div>
        </main>

        <nav class="fixed bottom-0 w-full max-w-md bg-[#5D4037] flex justify-around py-3 text-[#F5E6D3] shadow-inner">
            <i class="fa-solid fa-house text-lg"></i>
            <i class="fa-solid fa-magnifying-glass text-lg text-white/50"></i>
            <i class="fa-solid fa-cart-shopping text-lg text-white/50"></i>
            <i class="fa-solid fa-user text-lg text-white/50"></i>
        </nav>
    </div>

    <script>
        function sendToWA(nama, harga) {
            const nomor = "083899103235"; // Ganti ke nomor WA kamu!
            const text = `Halo Loka Coffee, saya pesan *${nama}* seharga *${harga}*.\n\nTolong diproses ya!`;
            window.open(`https://wa.me/${nomor}?text=${encodeURIComponent(text)}`, '_blank');
        }
    </script>
</body>
</html>
