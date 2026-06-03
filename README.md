<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HBD Sayangku CIntaku Cantikku Milikku Nisa 🌻</title>
    <!-- Tailwind CSS & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700&family=Playfair+Display:ital,wght@0,600;1,400&display=swap" rel="stylesheet">
    <!-- Font Awesome untuk Icon -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #e0f2fe; /* Smoothy Blue */
            scroll-behavior: smooth;
        }
        .serif-font {
            font-family: 'Playfair Display', serif;
        }
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #e0f2fe;
        }
        ::-webkit-scrollbar-thumb {
            background: #fde047;
            border-radius: 4px;
        }
        /* Floating Sunflowers Animation */
        .sunflower-float {
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(10deg); }
        }
    </style>
</head>
<body class="text-slate-800 overflow-x-hidden">

    <!-- 1. GATEWAY SCREEN (Halaman Pembuka Misterius) -->
    <div id="gateway" class="fixed inset-0 bg-[#e0f2fe] z-50 flex flex-col justify-center items-center p-6 transition-all duration-1000 ease-in-out">
        <div class="text-center max-w-md bg-white/60 backdrop-blur-md p-8 rounded-3xl shadow-xl border border-white/40 transform scale-100 transition-transform duration-500">
            <span class="text-4xl sunflower-float inline-block mb-4">🌻</span>
            <h1 class="serif-font text-2xl md:text-3xl font-semibold text-slate-800 mb-3">Eh, sebentar...</h1>
            <p class="text-slate-600 text-sm md:text-base mb-6 leading-relaxed">
                Ada sebuah ruang kecil digital yang sengaja dibuat cuma buat satu orang spesifik di bumi ini. Kebetulan namanya <span class="font-semibold text-rose-500">Siti Haerunisa Aura Rachman</span>. Kalau itu kamu, silakan masuk. Kalau bukan, mending nyontek dulu jalannya ke hati dia. 🤭
            </p>
            <button onclick="openGift()" class="bg-amber-400 hover:bg-amber-500 text-slate-900 font-semibold px-6 py-3 rounded-full shadow-md hover:shadow-lg transition-all duration-300 transform hover:-translate-y-1 active:translate-y-0">
                Masuk ke Ruang Kenangan ✨
            </button>
        </div>
    </div>

    <!-- MAIN CONTENT (Hidden initially) -->
    <div id="main-content" class="hidden opacity-0 transition-opacity duration-1000 page-layout">
        
        <!-- Background Decor -->
        <div class="fixed top-10 left-5 text-4xl opacity-20 sunflower-float">🌻</div>
        <div class="fixed bottom-10 right-5 text-5xl opacity-20 sunflower-float" style="animation-delay: 2s;">🌻</div>
        <div class="fixed top-1/3 right-10 text-3xl opacity-10 sunflower-float" style="animation-delay: 4s;">🌻</div>

        <!-- 2. HERO / WELCOME SECTION -->
        <header class="min-h-screen flex flex-col justify-center items-center text-center px-4 relative pt-10">
            <div class="bg-white/40 backdrop-blur-sm p-8 rounded-full shadow-inner mb-6 relative">
                <!-- GANTI DENGAN FOTO UTAMA NISA -->
                <img src="foto-utama.jpg" alt="Siti Haerunisa Aura Rachman" class="w-40 h-40 md:w-48 md:h-48 rounded-full object-cover border-4 border-white shadow-md">
                <span class="absolute bottom-2 right-2 text-3xl">🌻</span>
            </div>
            <p class="text-rose-500 font-semibold tracking-wide uppercase text-xs md:text-sm bg-rose-50 px-4 py-1.5 rounded-full mb-4 border border-rose-100">Selamat Ulang Tahun, Cantikku!</p>
            <h2 class="serif-font text-4xl md:text-6xl font-bold text-slate-900 mb-4 max-w-2xl px-2 leading-tight">
                Siti Haerunisa Aura Rachman
            </h2>
            <p class="text-slate-600 max-w-md text-sm md:text-base px-4 leading-relaxed mb-8">
                Hari ini semesta lagi senyum lebar, soalnya tepat di tanggal ini dulu, salah satu alasan paling manis di hidupku dilahirkan. Scroll pelan-pelan ya, mari kita buka kadonya satu-satu. 👇
            </p>
            <div class="animate-bounce text-slate-400 text-lg">
                <i class="fa-solid fa-chevron-down"></i>
            </div>
        </header>

        <!-- 3. STORYTELLING: PERJALANAN CINTA -->
        <section class="max-w-4xl mx-auto px-4 py-20">
            <div class="text-center mb-16">
                <span class="text-xs font-semibold tracking-widest text-slate-400 uppercase">Our Digital Timeline</span>
                <h3 class="serif-font text-3xl font-bold mt-1 text-slate-950">Cerita Singkat Kita 📜</h3>
                <div class="w-12 h-1 bg-amber-400 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="relative border-l-2 border-white/60 ml-4 md:ml-32 space-y-12">
                <!-- Timeline Item 1 -->
                <div class="relative pl-6 md:pl-8 group">
                    <div class="absolute -left-[11px] top-1 bg-amber-400 w-5 h-5 rounded-full border-4 border-[#e0f2fe] group-hover:scale-125 transition-transform"></div>
                    <div class="bg-white/70 backdrop-blur-sm p-6 rounded-2xl shadow-sm hover:shadow-md transition-all border border-white/50">
                        <span class="text-xs font-bold text-rose-400">Awal Cerita 👣</span>
                        <h4 class="font-bold text-lg text-slate-900 mt-1 mb-2">Pertama Kali Kenal</h4>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Inget gak sih pas awal kita kenal? Lucu ya kalau dipikir-pikir lagi sekarang. Dari yang awalnya malu-malu kucing, bales chatnya masih jaim banget, sampai akhirnya sadar kalau ngobrol sama kamu itu rasanya kayak pulang ke rumah: nyaman dan gak pengen pergi lagi.
                        </p>
                    </div>
                </div>

                <!-- Timeline Item 2 -->
                <div class="relative pl-6 md:pl-8 group">
                    <div class="absolute -left-[11px] top-1 bg-rose-400 w-5 h-5 rounded-full border-4 border-[#e0f2fe] group-hover:scale-125 transition-transform"></div>
                    <!-- GANTI DENGAN FOTO MOMEN BERSAMA -->
                    <div class="bg-white/70 backdrop-blur-sm p-6 rounded-2xl shadow-sm hover:shadow-md transition-all border border-white/50">
                        <span class="text-xs font-bold text-amber-500">Makin Dekat 💖</span>
                        <h4 class="font-bold text-lg text-slate-900 mt-1 mb-2">Dinamika & Tawa Bersama</h4>
                        <p class="text-sm text-slate-600 leading-relaxed mb-4">
                            Ngelewatin hari-hari sama kamu itu seru. Ada lucunya, ada ngambek-ngambek gemesnya (yang biasanya kalau kamu laper, hehe), tapi yang paling penting: kita selalu nemu jalan buat ketawa lagi. Kamu tuh bukan cuma pacar, tapi juga temen gibah paling asik sedunia.
                        </p>
                        <img src="foto-momen1.jpg" alt="Momen Kita" class="w-full h-48 object-cover rounded-xl border border-slate-100 shadow-sm">
                    </div>
                </div>

                <!-- Timeline Item 3 -->
                <div class="relative pl-6 md:pl-8 group">
                    <div class="absolute -left-[11px] top-1 bg-amber-400 w-5 h-5 rounded-full border-4 border-[#e0f2fe] group-hover:scale-125 transition-transform"></div>
                    <div class="bg-white/70 backdrop-blur-sm p-6 rounded-2xl shadow-sm hover:shadow-md transition-all border border-white/50">
                        <span class="text-xs font-bold text-emerald-500">Hari Ini & Seterusnya 📍</span>
                        <h4 class="font-bold text-lg text-slate-900 mt-1 mb-2">Sampai di Titik Ini</h4>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Dan sekarang, di hari ulang tahunmu ini, aku makin sadar kalau sayangku ke kamu itu gak berkurang sama sekali. Malah makin tumbuh, persis kayak sunflower yang selalu nyari arah matahari. Kamu mataharinya, Nisa.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. MOMEN SEDERHANA & HAL YANG DISUKAI -->
        <section class="bg-amber-50/50 py-20 border-y border-amber-100/50">
            <div class="max-w-5xl mx-auto px-4">
                <div class="text-center mb-12">
                    <h3 class="serif-font text-3xl font-bold text-slate-950">Little Things About You ✨</h3>
                    <p class="text-xs text-slate-500 mt-2">Hal-hal kecil yang diam-diam selalu bikin aku jatuh cinta (lagi)</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <!-- Card 1 -->
                    <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 transform hover:-translate-y-1 transition-all">
                        <div class="w-10 h-10 rounded-full bg-rose-50 flex items-center justify-center text-rose-500 mb-4">
                            <i class="fa-solid fa-face-smile-wink"></i>
                        </div>
                        <h4 class="font-bold text-base text-slate-900 mb-2">Ketawa Khas Kamu</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Cara kamu ketawa lepas kalau denger jokes garingku itu beneran mood booster terbaik. Jangan bosen denger candaan random aku ya!
                        </p>
                    </div>
                    <!-- Card 2 -->
                    <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 transform hover:-translate-y-1 transition-all" style="transition-delay: 0.1s;">
                        <div class="w-10 h-10 rounded-full bg-amber-50 flex items-center justify-center text-amber-500 mb-4">
                            <i class="fa-solid fa-heart"></i>
                        </div>
                        <h4 class="font-bold text-base text-slate-900 mb-2">Mode Kalo Lagi Manja</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Mulai dari nada suaranya yang berubah drastis sampai tatapan matanya. Di momen kayak gitu, rasanya pengen aku lindungin terus dari kerasnya dunia ini.
                        </p>
                    </div>
                    <!-- Card 3 -->
                    <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 transform hover:-translate-y-1 transition-all" style="transition-delay: 0.2s;">
                        <div class="w-10 h-10 rounded-full bg-blue-50 flex items-center justify-center text-blue-500 mb-4">
                            <i class="fa-solid fa-sun"></i>
                        </div>
                        <h4 class="font-bold text-base text-slate-900 mb-2">Sifat Pengertianmu</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Makasih ya udah selalu sabar, mau dengerin cerita aku, dan selalu kasih energi positif pas aku lagi capek-capeknya. Kamu hebat banget.
                        </p>
                    </div>
                </div>

                <!-- Gallery Mini -->
                <div class="mt-12 grid grid-cols-2 md:grid-cols-4 gap-4">
                    <!-- GANTI DENGAN FOTO-FOTO RANDOM YANG LUCU/CANTIK -->
                    <img src="foto-grid1.jpg" alt="Nisa Cantik" class="w-full h-40 object-cover rounded-2xl shadow-sm border border-white">
                    <img src="foto-grid2.jpg" alt="Nisa Lucu" class="w-full h-40 object-cover rounded-2xl shadow-sm border border-white">
                    <img src="foto-grid3.jpg" alt="Nisa Gemes" class="w-full h-40 object-cover rounded-2xl shadow-sm border border-white">
                    <img src="foto-grid4.jpg" alt="Momen Bersama" class="w-full h-40 object-cover rounded-2xl shadow-sm border border-white">
                </div>
            </div>
        </section>

        <!-- 5. INTERACTIVE INTERMEZZO (Krem/Pinkish tones included) -->
        <section class="max-w-md mx-auto px-4 py-20 text-center">
            <div class="bg-white/80 backdrop-blur-md p-8 rounded-3xl shadow-md border border-white">
                <span class="text-2xl">🎁</span>
                <h4 class="font-bold text-lg text-slate-900 mt-2 mb-1">Click This to Spawn Love</h4>
                <p class="text-xs text-slate-500 mb-4">Ketuk tombol di bawah ini sebanyak yang kamu mau buat ngirim 'cinta digital'</p>
                <button onclick="spawnHeart()" class="bg-rose-500 hover:bg-rose-600 text-white text-xs font-bold px-4 py-2 rounded-full shadow-sm transition-all active:scale-95">
                    <i class="fa-solid fa-heart mr-1"></i> Tekan Aku!
                </button>
                <div id="heart-counter" class="text-xs font-bold text-rose-500 mt-3 hidden">
                    Kamu udah ngirim <span id="count-click">0</span> cinta buat hari ini!
                </div>
            </div>
        </section>

        <!-- 6. SURPRISE SECTION (Paling Ditunggu) -->
        <section class="max-w-3xl mx-auto px-4 pb-28 pt-10 text-center">
            <div class="border-t-2 border-dashed border-slate-300 my-10"></div>
            
            <div id="lock-container" class="space-y-4">
                <p class="text-sm text-slate-500 italic">Ada satu surat terakhir yang dikunci rapat, khusus dibuka pas udah kelar baca semuanya...</p>
                <button onclick="revealSurprise()" class="bg-slate-900 hover:bg-slate-800 text-amber-300 text-sm font-semibold px-6 py-3 rounded-full transition-all shadow-md">
                    <i class="fa-solid fa-envelope-open-text mr-2"></i> Buka Surat Rahasia 💌
                </button>
            </div>

            <div id="surprise-box" class="hidden opacity-0 transition-all duration-1000 bg-white/90 backdrop-blur-md p-8 md:p-12 rounded-[2rem] shadow-xl border border-white text-left relative overflow-hidden">
                <div class="absolute -right-6 -top-6 text-7xl opacity-10 rotate-12">🌻</div>
                
                <h3 class="serif-font text-2xl md:text-3xl font-bold text-slate-950 mb-6 text-center border-b pb-4 border-slate-100">
                    Dear Siti Haerunisa Aura Rachman...
                </h3>
                
                <div class="text-slate-700 text-sm md:text-base space-y-4 leading-relaxed">
                    <p>
                        Selamat ulang tahun ya, sayangku, cintaku, cantikku, milikku. 
                    </p>
                    <p>
                        Makasih banyak ya udah lahir ke dunia ini, dan makasih jauh lebih banyak lagi karena udah ngebiarin aku jadi salah satu orang yang beruntung buat nemenin hari-harimu. Makasih udah bertahan bareng aku di segala situasi, baik pas lagi seneng bareng, atau pas dinamika hubungan kita lagi diuji ego masing-masing.
                    </p>
                    <p>
                        Doaku buat kamu di umur yang baru ini gak muluk-muluk: Aku berdoa semoga kamu selalu sehat, dilancarkan semua urusan kuliah dan impian yang lagi kamu kejar, didekatkan sama hal-hal baik, dan dijauhkan dari rasa sedih yang berlarut-larut. Kalau dunia luar lagi bikin kamu capek, inget ya kalau kamu selalu punya aku tempat buat pulang dan cerita apa aja.
                    </p>
                    <p>
                        Semoga kita bisa terus tumbuh bareng, dewasa bareng, dan saling menuntun jadi versi terbaik dari diri kita masing-masing. Tetap jadi Nisa yang aku kenal, yang sehangat dan seindah bunga matahari.
                    </p>
                    <p class="pt-4 font-bold text-right text-rose-500 serif-font italic">
                        With all my love, selalu dan selamanya. ❤️
                    </p>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center py-6 text-xs text-slate-400 bg-white/30 border-t border-white/40">
            Dibuat penuh rasa sayang untuk Siti Haerunisa Aura Rachman © 2026
        </footer>
    </div>

    <!-- JavaScript logic -->
    <script>
        // Membuka Gerbang Halaman Utama
        function openGift() {
            const gateway = document.getElementById('gateway');
            const mainContent = document.getElementById('main-content');
            
            gateway.classList.add('opacity-0', 'scale-95');
            setTimeout(() => {
                gateway.style.display = 'none';
                mainContent.classList.remove('hidden');
                setTimeout(() => {
                    mainContent.classList.add('opacity-100');
                }, 50);
            }, 1000);
        }

        // Kejutan Clicker Love
        let clicks = 0;
        function spawnHeart() {
            clicks++;
            const counterDiv = document.getElementById('heart-counter');
            const countSpan = document.getElementById('count-click');
            counterDiv.classList.remove('hidden');
            countSpan.innerText = clicks;

            // Membuat efek animasi love terbang bebas
            const heart = document.createElement('div');
            heart.innerHTML = '❤️';
            heart.style.position = 'fixed';
            heart.style.left = Math.random() * 80 + 10 + 'vw';
            heart.style.bottom = '0vh';
            heart.style.fontSize = Math.random() * 20 + 20 + 'px';
            heart.style.zIndex = '99';
            heart.style.transition = 'transform 2s ease-out, opacity 2s ease-out';
            document.body.appendChild(heart);

            setTimeout(() => {
                heart.style.transform = `translateY(-80vh) scale(1.5) rotate(${Math.random() * 360}deg)`;
                heart.style.opacity = '0';
            }, 50);

            setTimeout(() => {
                heart.remove();
            }, 2050);
        }

        // Membuka Bagian Surat Rahasia/Surprise
        function revealSurprise() {
            const lockContainer = document.getElementById('lock-container');
            const surpriseBox = document.getElementById('surprise-box');
            
            lockContainer.classList.add('hidden');
            surpriseBox.classList.remove('hidden');
            setTimeout(() => {
                surpriseBox.classList.remove('opacity-0');
                surpriseBox.classList.add('opacity-100');
                // Auto scroll perlahan ke box kejutan
                surpriseBox.scrollIntoView({ behavior: 'smooth' });
            }, 100);
        }
    </script>
</body>
</html>
