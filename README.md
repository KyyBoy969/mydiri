<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beranda | Resume Pribadi</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        <div class="nav-brand">MyResume</div>
        <ul class="nav-menu">
            <li><a href="index.html" class="active">Beranda</a></li>
            <li><a href="about.html">Tentang Saya</a></li>
            <li><a href="contact.html">Kontak</a></li>
        </ul>
    </nav>

    <main class="hero">
        <div class="hero-content">
            <div class="hero-image">
                <img src="foto zaki.jpg" alt="Foto Profil" width="200px"
                style="border-radius: 100px;"
            </div>
            <div class="hero-text">
                <h1>Halo, Saya <span class="highlight">Muhammad Zaki</span></h1>
                <div class="info-badge">
                    <span>Kelas XI</span>
                    <span>Rekayasa Perangkat Lunak</span>
                </div>
                <p class="intro">
                    Seorang siswa SMK yang memiliki passion di bidang pengembangan 
                    web dan aplikasi. Saya senang mempelajari teknologi baru dan 
                    menciptakan solusi digital yang bermanfaat.
                </p>
                <a href="about.html" class="btn btn-primary">Tentang Saya →</a>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2026 MUHAMMAD ZAKI ALFATIN.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tentang Saya - Resume Saya</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <div class="logo">Portofolio.</div>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="about.html" class="active">Tentang Saya</a></li>
                <li><a href="contact.html">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section class="card">
            <h2>Biodata Singkat</h2>
            <p>Saya seorang pelajar yang fokus mendalami dunia pengembangan perangkat lunak. Memiliki ketertarikan tinggi pada pembuatan antarmuka web yang rapi, responsif, dan mudah digunakan.</p>
        </section>

        <section class="card">
            <h2>Riwayat Pendidikan</h2>
            <ul>
                <li><strong>Smk Negeri 5 Telkom banda aceh</strong> — Jurusan Rekayasa perangkat lunak (2025 - 2028)</li>
                <li><strong>Smp Negeri 18 banda aceh</strong> (2022 - 2025)</li>
                                <li><strong>Sd negeri lam ujong</strong> (2015 - 2022)</li>

            </ul>
        </section>

        <section class="card">
            <h2>Kemampuan / Keterampilan</h2>
            <ul class="skills-list">
                <li>HTML</li>
                <li>CSS</li>
            </ul>
        </section>

        <section class="card">
            <h2>Hobi</h2>
            <ul class="hobby-list">
                <li>Coding</li>
                <li>bermain bola</li>
                <li>Bermain Game</li>
                <li>Mendengarkan Musik</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 MUHAMMAD ZAKI ALFATIN.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kontak - Resume Saya</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <div class="logo">Portofolio.</div>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="about.html">Tentang Saya</a></li>
                <li><a href="contact.html" class="active">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section class="card">
            <h2>Informasi Kontak</h2>
            <p><strong>Email:</strong> kyytokufanss@gmail.com</p>
            <p><strong>Telepon:</strong> +62 831-1091-1395</p>
            <br>
            <h3>Media Sosial</h3>
            <div class="social-links">
                                <a href="#">Tiktok:@kyy_younjung</a>
                                <a href="#">Instagram@7kiiee_</a>

            </div>
        </section>

        <section class="card">
            <h2>Kirim Pesan</h2>
            <form action="#" method="post">
                <div class="form-group">
                    <label for="name">Nama</label>
                    <input type="text" id="name" name="name" placeholder="Masukkan nama Anda" required>
                </div>

                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="Masukkan email Anda" required>
                </div>

                <div class="form-group">
                    <label for="message">Pesan</label>
                    <textarea id="message" name="message" rows="5" placeholder="Tuliskan pesan Anda di sini..." required></textarea>
                </div>

                <button type="submit" class="btn">Kirim</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 MUHAMMAD ZAKI ALFATIN.</p>
    </footer>

</body>
</html>
