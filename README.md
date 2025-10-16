# website-link-dowload-gratis
Bisa Download game gratis dari link ini
[Web dasar.html](https://github.com/user-attachments/files/22945591/Web.dasar.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Game Vault - Portal Download Gratis Klasik</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
    <style>
        /* --- GAYA KLASIK UMUM --- */
        :root {
            --bg-color: #0f0f0f;
            --container-bg: #1e1e1e;
            --primary-color: #00ff41; /* Hijau retro */
            --secondary-color: #ffffff;
            --accent-color: #ffcc00; /* Kuning untuk badge */
            --border-color: #444;
            --button-bg: #3a3a3a;
            --button-border-light: #777;
            --button-border-dark: #111;
        }

        body {
            background-color: var(--bg-color);
            color: var(--primary-color);
            font-family: 'Courier New', Courier, monospace;
            font-size: 14px;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            /* Efek Scanline CRT */
            background-image: 
                linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%),
                linear-gradient(90deg, rgba(255, 0, 0, 0.06), rgba(0, 255, 0, 0.02), rgba(0, 0, 255, 0.06));
            background-size: 100% 2px, 3px 100%;
            overflow-x: hidden;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            background-color: var(--container-bg);
            border: 3px solid var(--border-color);
            box-shadow: 0 0 25px rgba(0, 255, 65, 0.3);
        }

        /* --- HEADER --- */
        header {
            background-color: #000;
            border-bottom: 3px solid var(--primary-color);
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-family: 'Press Start 2P', cursive;
            font-size: 32px;
            color: var(--primary-color);
            text-shadow: 3px 3px #ff00ff, 6px 6px #00ffff;
            margin: 0;
            letter-spacing: 3px;
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from { text-shadow: 3px 3px #ff00ff, 6px 6px #00ffff, 0 0 10px #fff; }
            to { text-shadow: 3px 3px #ff00ff, 6px 6px #00ffff, 0 0 20px #fff, 0 0 30px var(--primary-color); }
        }

        header p {
            font-family: 'Press Start 2P', cursive;
            font-size: 10px;
            color: var(--secondary-color);
            margin: 10px 0 0 0;
        }

        /* --- NAVIGASI --- */
        nav {
            background-color: #2a2a2a;
            border-bottom: 2px solid var(--border-color);
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: var(--secondary-color);
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
            border-right: 1px solid var(--border-color);
            transition: background-color 0.3s, color 0.3s;
        }

        nav a:last-child {
            border-right: none;
        }

        nav a:hover {
            background-color: var(--primary-color);
            color: #000;
        }

        /* --- KONTEN UTAMA --- */
        .content-wrapper {
            display: flex;
            padding: 20px;
            gap: 20px;
        }

        main {
            flex: 3;
        }

        aside {
            flex: 1;
        }

        /* --- GAME CARD --- */
        .game-card {
            background-color: #252525;
            border: 2px solid var(--border-color);
            padding: 15px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 20px;
            transition: border-color 0.3s, box-shadow 0.3s;
        }

        .game-card:hover {
            border-color: var(--primary-color);
            box-shadow: 0 0 15px rgba(0, 255, 65, 0.4);
        }

        .game-card img {
            width: 120px;
            height: 90px;
            border: 2px solid var(--border-color);
            object-fit: cover;
        }

        .game-info h3 {
            font-family: 'Press Start 2P', cursive;
            font-size: 14px;
            margin: 0 0 10px 0;
            color: var(--secondary-color);
        }

        .game-info p {
            margin: 5px 0;
            font-size: 12px;
        }

        .game-info .badge {
            display: inline-block;
            background-color: var(--accent-color);
            color: #000;
            padding: 2px 6px;
            font-size: 10px;
            font-weight: bold;
            margin-right: 5px;
            animation: blink 1.5s infinite;
        }

        /* --- TOMBOL KLASIK --- */
        .btn {
            background-color: var(--button-bg);
            border-top: 2px solid var(--button-border-light);
            border-left: 2px solid var(--button-border-light);
            border-bottom: 2px solid var(--button-border-dark);
            border-right: 2px solid var(--button-border-dark);
            color: var(--secondary-color);
            padding: 8px 15px;
            font-family: 'Press Start 2P', cursive;
            font-size: 10px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: all 0.1s;
            margin-top: 10px;
        }

        .btn:hover {
            background-color: #555;
        }

        .btn:active {
            border-top: 2px solid var(--button-border-dark);
            border-left: 2px solid var(--button-border-dark);
            border-bottom: 2px solid var(--button-border-light);
            border-right: 2px solid var(--button-border-light);
            transform: translate(1px, 1px);
        }

        /* --- SIDEBAR --- */
        .sidebar-section {
            background-color: #252525;
            border: 2px solid var(--border-color);
            padding: 15px;
            margin-bottom: 20px;
        }

        .sidebar-section h3 {
            font-family: 'Press Start 2P', cursive;
            font-size: 12px;
            margin-top: 0;
            border-bottom: 1px dashed var(--border-color);
            padding-bottom: 10px;
            color: var(--accent-color);
        }

        .sidebar-section ul {
            list-style-type: '>> ';
            padding-left: 20px;
        }

        .sidebar-section ul li {
            margin-bottom: 8px;
        }

        .sidebar-section ul li a {
            color: var(--primary-color);
            text-decoration: none;
        }

        .sidebar-section ul li a:hover {
            text-decoration: underline;
        }

        /* --- PENCARIAN --- */
        #searchInput {
            width: 100%;
            padding: 10px;
            background-color: #111;
            border: 2px solid var(--border-color);
            color: var(--secondary-color);
            font-family: 'Courier New', Courier, monospace;
            font-size: 14px;
            box-sizing: border-box;
        }

        #searchInput:focus {
            outline: none;
            border-color: var(--primary-color);
        }

        /* --- FOOTER --- */
        footer {
            background-color: #000;
            border-top: 3px solid var(--primary-color);
            text-align: center;
            padding: 20px;
            font-size: 12px;
        }

        /* --- ANIMASI --- */
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        /* --- NOTIFIKASI POPUP --- */
        .notification {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #000;
            border: 3px solid var(--primary-color);
            color: var(--primary-color);
            padding: 20px 30px;
            font-family: 'Press Start 2P', cursive;
            font-size: 12px;
            z-index: 1000;
            box-shadow: 0 0 20px var(--primary-color);
            text-align: center;
            animation: fadeIn 0.5s;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
            .content-wrapper {
                flex-direction: column;
            }
            .game-card {
                flex-direction: column;
                text-align: center;
            }
            header h1 {
                font-size: 22px;
            }
            nav a {
                display: block;
                padding: 10px;
                border-right: none;
                border-bottom: 1px solid var(--border-color);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>The Game Vault</h1>
            <p>Portal Menuju Game Gratis PC</p>
        </header>

        <nav>
            <a href="#">BERANDA</a>
            <a href="#">DAFTAR GAME</a>
            <a href="#">KATEGORI</a>
            <a href="#">CARA DOWNLOAD</a>
        </nav>

        <div class="content-wrapper">
            <main>
                <section id="gameList">
                    <div class="game-card">
                        <img src="<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Game Vault - Portal Download Gratis Klasik</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
    <style>
        /* --- GAYA KLASIK UMUM --- */
        :root {
            --bg-color: #0f0f0f;
            --container-bg: #1e1e1e;
            --primary-color: #00ff41; /* Hijau retro */
            --secondary-color: #ffffff;
            --accent-color: #ffcc00; /* Kuning untuk badge */
            --border-color: #444;
            --button-bg: #3a3a3a;
            --button-border-light: #777;
            --button-border-dark: #111;
        }

        body {
            background-color: var(--bg-color);
            color: var(--primary-color);
            font-family: 'Courier New', Courier, monospace;
            font-size: 14px;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            /* Efek Scanline CRT */
            background-image: 
                linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%),
                linear-gradient(90deg, rgba(255, 0, 0, 0.06), rgba(0, 255, 0, 0.02), rgba(0, 0, 255, 0.06));
            background-size: 100% 2px, 3px 100%;
            overflow-x: hidden;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            background-color: var(--container-bg);
            border: 3px solid var(--border-color);
            box-shadow: 0 0 25px rgba(0, 255, 65, 0.3);
        }

        /* --- HEADER --- */
        header {
            background-color: #000;
            border-bottom: 3px solid var(--primary-color);
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-family: 'Press Start 2P', cursive;
            font-size: 32px;
            color: var(--primary-color);
            text-shadow: 3px 3px #ff00ff, 6px 6px #00ffff;
            margin: 0;
            letter-spacing: 3px;
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from { text-shadow: 3px 3px #ff00ff, 6px 6px #00ffff, 0 0 10px #fff; }
            to { text-shadow: 3px 3px #ff00ff, 6px 6px #00ffff, 0 0 20px #fff, 0 0 30px var(--primary-color); }
        }

        header p {
            font-family: 'Press Start 2P', cursive;
            font-size: 10px;
            color: var(--secondary-color);
            margin: 10px 0 0 0;
        }

        /* --- NAVIGASI --- */
        nav {
            background-color: #2a2a2a;
            border-bottom: 2px solid var(--border-color);
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: var(--secondary-color);
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
            border-right: 1px solid var(--border-color);
            transition: background-color 0.3s, color 0.3s;
        }

        nav a:last-child {
            border-right: none;
        }

        nav a:hover {
            background-color: var(--primary-color);
            color: #000;
        }

        /* --- KONTEN UTAMA --- */
        .content-wrapper {
            display: flex;
            padding: 20px;
            gap: 20px;
        }

        main {
            flex: 3;
        }

        aside {
            flex: 1;
        }

        /* --- GAME CARD --- */
        .game-card {
            background-color: #252525;
            border: 2px solid var(--border-color);
            padding: 15px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 20px;
            transition: border-color 0.3s, box-shadow 0.3s;
        }

        .game-card:hover {
            border-color: var(--primary-color);
            box-shadow: 0 0 15px rgba(0, 255, 65, 0.4);
        }

        .game-card img {
            width: 120px;
            height: 90px;
            border: 2px solid var(--border-color);
            object-fit: cover;
        }

        .game-info h3 {
            font-family: 'Press Start 2P', cursive;
            font-size: 14px;
            margin: 0 0 10px 0;
            color: var(--secondary-color);
        }

        .game-info p {
            margin: 5px 0;
            font-size: 12px;
        }

        .game-info .badge {
            display: inline-block;
            background-color: var(--accent-color);
            color: #000;
            padding: 2px 6px;
            font-size: 10px;
            font-weight: bold;
            margin-right: 5px;
            animation: blink 1.5s infinite;
        }

        /* --- TOMBOL KLASIK --- */
        .btn {
            background-color: var(--button-bg);
            border-top: 2px solid var(--button-border-light);
            border-left: 2px solid var(--button-border-light);
            border-bottom: 2px solid var(--button-border-dark);
            border-right: 2px solid var(--button-border-dark);
            color: var(--secondary-color);
            padding: 8px 15px;
            font-family: 'Press Start 2P', cursive;
            font-size: 10px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: all 0.1s;
            margin-top: 10px;
        }

        .btn:hover {
            background-color: #555;
        }

        .btn:active {
            border-top: 2px solid var(--button-border-dark);
            border-left: 2px solid var(--button-border-dark);
            border-bottom: 2px solid var(--button-border-light);
            border-right: 2px solid var(--button-border-light);
            transform: translate(1px, 1px);
        }

        /* --- SIDEBAR --- */
        .sidebar-section {
            background-color: #252525;
            border: 2px solid var(--border-color);
            padding: 15px;
            margin-bottom: 20px;
        }

        .sidebar-section h3 {
            font-family: 'Press Start 2P', cursive;
            font-size: 12px;
            margin-top: 0;
            border-bottom: 1px dashed var(--border-color);
            padding-bottom: 10px;
            color: var(--accent-color);
        }

        .sidebar-section ul {
            list-style-type: '>> ';
            padding-left: 20px;
        }

        .sidebar-section ul li {
            margin-bottom: 8px;
        }

        .sidebar-section ul li a {
            color: var(--primary-color);
            text-decoration: none;
        }

        .sidebar-section ul li a:hover {
            text-decoration: underline;
        }

        /* --- PENCARIAN --- */
        #searchInput {
            width: 100%;
            padding: 10px;
            background-color: #111;
            border: 2px solid var(--border-color);
            color: var(--secondary-color);
            font-family: 'Courier New', Courier, monospace;
            font-size: 14px;
            box-sizing: border-box;
        }

        #searchInput:focus {
            outline: none;
            border-color: var(--primary-color);
        }

        /* --- FOOTER --- */
        footer {
            background-color: #000;
            border-top: 3px solid var(--primary-color);
            text-align: center;
            padding: 20px;
            font-size: 12px;
        }

        /* --- ANIMASI --- */
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        /* --- NOTIFIKASI POPUP --- */
        .notification {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #000;
            border: 3px solid var(--primary-color);
            color: var(--primary-color);
            padding: 20px 30px;
            font-family: 'Press Start 2P', cursive;
            font-size: 12px;
            z-index: 1000;
            box-shadow: 0 0 20px var(--primary-color);
            text-align: center;
            animation: fadeIn 0.5s;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
            .content-wrapper {
                flex-direction: column;
            }
            .game-card {
                flex-direction: column;
                text-align: center;
            }
            header h1 {
                font-size: 22px;
            }
            nav a {
                display: block;
                padding: 10px;
                border-right: none;
                border-bottom: 1px solid var(--border-color);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>The Game Vault</h1>
            <p>Portal Menuju Game Gratis PC</p>
        </header>

        <nav>
            <a href="#">BERANDA</a>
            <a href="#">DAFTAR GAME</a>
            <a href="#">KATEGORI</a>
            <a href="#">CARA DOWNLOAD</a>
        </nav>

        <div class="content-wrapper">
            <main>
                <section id="gameList">
                    <div class="game-card">
                        <img src="download.jpg" alt="GTA V Thumbnail">
                        <div class="game-info">
                            <h3>Grand Theft Auto V</h3>
                            <p><span class="badge">POPULER!</span> Kategori: Action, Open World | Ukuran: ~100 GB</p>
                            <p>Petualangan epik di Los Santos. Jelajahi dunia terbuka yang luas dan jalani hidup sebagai seorang kriminal.</p>
                            <a href="#" class="btn" onclick="handleDownload('Grand Theft Auto V')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/120x90/444/fff?text=Red+Dead+2" alt="Red Dead 2 Thumbnail">
                        <div class="game-info">
                            <h3>Red Dead Redemption 2</h3>
                            <p><span class="badge">BARU!</span> Kategori: Action, Adventure | Ukuran: ~150 GB</p>
                            <p>Masuki dunia liar Amerika sebagai Arthur Morgan. Cerita mendalam tentang loyalitas dan kelangsungan hidup.</p>
                            <a href="#" class="btn" onclick="handleDownload('Red Dead Redemption 2')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/120x90/555/fff?text=Cyberpunk+2077" alt="Cyberpunk 2077 Thumbnail">
                        <div class="game-info">
                            <h3>Cyberpunk 2077</h3>
                            <p><span class="badge">HOT!</span> Kategori: RPG, FPS | Ukuran: ~70 GB</p>
                            <p>Jelajahi Night City, sebuah megapolis yang terobsesi dengan kekuasaan, kemewahan, dan modifikasi tubuh.</p>
                            <a href="#" class="btn" onclick="handleDownload('Cyberpunk 2077')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/120x90/666/fff?text=Elden+Ring" alt="Elden Ring Thumbnail">
                        <div class="game-info">
                            <h3>Elden Ring</h3>
                            <p>Kategori: RPG, Action | Ukuran: ~60 GB</p>
                    <p>Menjadi Elden Ring di dunia action RPG fantasi yang luas. Taklukkan musuh-musuh legendaris dan jelajahi Lands Between.</p>
                            <a href="#" class="btn" onclick="handleDownload('Elden Ring')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                </section>
            </main>

            <aside>
                <div class="sidebar-section">
                    <h3>Pencarian Game</h3>
                    <input type="text" id="searchInput" placeholder="Ketik nama game..." onkeyup="filterGames()">
                </div>

                <div class="sidebar-section">
                    <h3>Kategori</h3>
                    <ul>
                        <li><a href="#">Action (50)</a></li>
                        <li><a href="#">RPG (35)</a></li>
                        <li><a href="#">Strategy (20)</a></li>
                        <li><a href="#">Horror (15)</a></li>
                        <li><a href="#">Simulation (25)</a></li>
                    </ul>
                </div>

                <div class="sidebar-section">
                    <h3>Top 5 Download</h3>
                    <ul>
                        <li><a href="#">Grand Theft Auto V</a></li>
                        <li><a href="#">Red Dead Redemption 2</a></li>
                        <li><a href="#">Cyberpunk 2077</a></li>
                        <li><a href="#">The Witcher 3</a></li>
                        <li><a href="#">Elden Ring</a></li>
                    </ul>
                </div>
            </aside>
        </div>

        <footer>
            <p>&copy; 2024 The Game Vault. Portal Pihak Ketiga.</p>
            <p>Pengunjung ke: <span id="visitorCount">98341</span></p>
        </footer>
    </div>

    <script>
        // --- Fungsi Pencarian Game ---
        function filterGames() {
            const input = document.getElementById('searchInput');
            const filter = input.value.toUpperCase();
            const gameList = document.getElementById('gameList');
            const gameCards = gameList.getElementsByClassName('game-card');

            for (let i = 0; i < gameCards.length; i++) {
                const gameInfo = gameCards[i].getElementsByClassName('game-info')[0];
                const titleElement = gameInfo.getElementsByTagName('h3')[0];
                const txtValue = titleElement.textContent || titleElement.innerText;

                if (txtValue.toUpperCase().indexOf(filter) > -1) {
                    gameCards[i].style.display = "";
                } else {
                    gameCards[i].style.display = "none";
                }
            }
        }

        // --- Fungsi Handle Download ke SteamUnlocked ---
        function handleDownload(gameName) {
            // Mencegah link meloncat ke atas
            event.preventDefault(); 
            
            // Buat notifikasi
            const notification = document.createElement('div');
            notification.className = 'notification';
            notification.innerHTML = `
                <p>Mengarahkan ke SteamUnlocked...</p>
                <p style="font-size: 10px; margin-top: 10px;">Mencari: ${gameName}</p>
            `;
            document.body.appendChild(notification);

            // Buka link di tab baru setelah delay singkat
            setTimeout(() => {
                // Encode nama game untuk URL yang aman
                const searchQuery = encodeURIComponent(gameName);
                const steamUnlockedURL = `https://steamunlocked.com.br/search/${searchQuery}`;
                window.open(steamUnlockedURL, '_blank');
                
                // Hapus notifikasi setelah beberapa saat
                setTimeout(() => {
                    notification.remove();
                }, 2000);
            }, 1000); // Delay 1 detik
        }

        // --- Simulasi Penghitung Pengunjung ---
        function updateVisitorCount() {
            const countElement = document.getElementById('visitorCount');
            let count = localStorage.getItem('visitorCount');
            if (count === null) {
                count = Math.floor(Math.random() * 5000) + 95000; // Angka awal acak
            } else {
                count = parseInt(count) + Math.floor(Math.random() * 3) + 1; // Tambah 1-3
            }
            localStorage.setItem('visitorCount', count);
            countElement.innerText = count.toLocaleString('id-ID');
        }

        // Jalankan fungsi saat halaman dimuat
        window.onload = updateVisitorCount;

    </script>

</body>
</html>" alt="GTA V Thumbnail">
                        <div class="game-infdata:image/jpeg;base64,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o">
                            <h3>Grand Theft Auto V</h3>
                            <p><span class="badge">POPULER!</span> Kategori: Action, Open World | Ukuran: ~100 GB</p>
                            <p>Petualangan epik di Los Santos. Jelajahi dunia terbuka yang luas dan jalani hidup sebagai seorang kriminal.</p>
                            <a href="#" class="btn" onclick="handleDownload('Grand Theft Auto V')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/120x90/444/fff?text=Red+Dead+2" alt="Red Dead 2 Thumbnail">
                        <div class="game-info">
                            <h3>Red Dead Redemption 2</h3>
                            <p><span class="badge">BARU!</span> Kategori: Action, Adventure | Ukuran: ~150 GB</p>
                            <p>Masuki dunia liar Amerika sebagai Arthur Morgan. Cerita mendalam tentang loyalitas dan kelangsungan hidup.</p>
                            <a href="#" class="btn" onclick="handleDownload('Red Dead Redemption 2')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/120x90/555/fff?text=Cyberpunk+2077" alt="Cyberpunk 2077 Thumbnail">
                        <div class="game-info">
                            <h3>Cyberpunk 2077</h3>
                            <p><span class="badge">HOT!</span> Kategori: RPG, FPS | Ukuran: ~70 GB</p>
                            <p>Jelajahi Night City, sebuah megapolis yang terobsesi dengan kekuasaan, kemewahan, dan modifikasi tubuh.</p>
                            <a href="#" class="btn" onclick="handleDownload('Cyberpunk 2077')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/120x90/666/fff?text=Elden+Ring" alt="Elden Ring Thumbnail">
                        <div class="game-info">
                            <h3>Elden Ring</h3>
                            <p>Kategori: RPG, Action | Ukuran: ~60 GB</p>
                    <p>Menjadi Elden Ring di dunia action RPG fantasi yang luas. Taklukkan musuh-musuh legendaris dan jelajahi Lands Between.</p>
                            <a href="#" class="btn" onclick="handleDownload('Elden Ring')">DOWNLOAD NOW</a>
                        </div>
                    </div>
                </section>
            </main>

            <aside>
                <div class="sidebar-section">
                    <h3>Pencarian Game</h3>
                    <input type="text" id="searchInput" placeholder="Ketik nama game..." onkeyup="filterGames()">
                </div>

                <div class="sidebar-section">
                    <h3>Kategori</h3>
                    <ul>
                        <li><a href="#">Action (50)</a></li>
                        <li><a href="#">RPG (35)</a></li>
                        <li><a href="#">Strategy (20)</a></li>
                        <li><a href="#">Horror (15)</a></li>
                        <li><a href="#">Simulation (25)</a></li>
                    </ul>
                </div>

                <div class="sidebar-section">
                    <h3>Top 5 Download</h3>
                    <ul>
                        <li><a href="#">Grand Theft Auto V</a></li>
                        <li><a href="#">Red Dead Redemption 2</a></li>
                        <li><a href="#">Cyberpunk 2077</a></li>
                        <li><a href="#">The Witcher 3</a></li>
                        <li><a href="#">Elden Ring</a></li>
                    </ul>
                </div>
            </aside>
        </div>

        <footer>
            <p>&copy; 2024 The Game Vault. Portal Pihak Ketiga.</p>
            <p>Pengunjung ke: <span id="visitorCount">98341</span></p>
        </footer>
    </div>

    <script>
        // --- Fungsi Pencarian Game ---
        function filterGames() {
            const input = document.getElementById('searchInput');
            const filter = input.value.toUpperCase();
            const gameList = document.getElementById('gameList');
            const gameCards = gameList.getElementsByClassName('game-card');

            for (let i = 0; i < gameCards.length; i++) {
                const gameInfo = gameCards[i].getElementsByClassName('game-info')[0];
                const titleElement = gameInfo.getElementsByTagName('h3')[0];
                const txtValue = titleElement.textContent || titleElement.innerText;

                if (txtValue.toUpperCase().indexOf(filter) > -1) {
                    gameCards[i].style.display = "";
                } else {
                    gameCards[i].style.display = "none";
                }
            }
        }

        // --- Fungsi Handle Download ke SteamUnlocked ---
        function handleDownload(gameName) {
            // Mencegah link meloncat ke atas
            event.preventDefault(); 
            
            // Buat notifikasi
            const notification = document.createElement('div');
            notification.className = 'notification';
            notification.innerHTML = `
                <p>Mengarahkan ke SteamUnlocked...</p>
                <p style="font-size: 10px; margin-top: 10px;">Mencari: ${gameName}</p>
            `;
            document.body.appendChild(notification);

            // Buka link di tab baru setelah delay singkat
            setTimeout(() => {
                // Encode nama game untuk URL yang aman
                const searchQuery = encodeURIComponent(gameName);
                const steamUnlockedURL = `https://steamunlocked.com.br/search/${searchQuery}`;
                window.open(steamUnlockedURL, '_blank');
                
                // Hapus notifikasi setelah beberapa saat
                setTimeout(() => {
                    notification.remove();
                }, 2000);
            }, 1000); // Delay 1 detik
        }

        // --- Simulasi Penghitung Pengunjung ---
        function updateVisitorCount() {
            const countElement = document.getElementById('visitorCount');
            let count = localStorage.getItem('visitorCount');
            if (count === null) {
                count = Math.floor(Math.random() * 5000) + 95000; // Angka awal acak
            } else {
                count = parseInt(count) + Math.floor(Math.random() * 3) + 1; // Tambah 1-3
            }
            localStorage.setItem('visitorCount', count);
            countElement.innerText = count.toLocaleString('id-ID');
        }

        // Jalankan fungsi saat halaman dimuat
        window.onload = updateVisitorCount;

    </script>

</body>
</html>
