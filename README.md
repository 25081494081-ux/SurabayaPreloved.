# SurabayaPreloved.
web
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surabaya Preloved - Jual Beli Barang Bekas Mahasiswa</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="header">
        <div class="container">
            <h1 class="logo">Surabaya Preloved ♻️</h1>
            <nav class="nav">
                <a href="#about">Tentang Kami</a>
                <a href="#services">Layanan</a>
                <a href="#how-to">Cara Kerja</a>
                <a href="#contact" class="btn-cta">Hubungi Kami</a>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero" class="hero">
            <div class="container">
                <h2>Cari Barang Kebutuhan Kuliah Murah & Berkualitas!</h2>
                <p>Platform terpercaya jual beli barang bekas khusus untuk mahasiswa di Surabaya.</p>
                 <p>Hemat uang dan kurangi sampah</p>
                <button id="cta-button" class="btn-primary">Mulai Jual Beli Sekarang!</button>
            </div>
        </section>

        <section id="about" class="section-padding">
            <div class="container">
                <h3 class="section-title">Kenapa Surabaya Preloved?</h3>
                <div class="grid-3">
                    <div class="card">
                        <h4>Hemat Biaya 💰</h4>
                        <p>Dapatkan barang-barang kuliah, kos, atau elektronik dengan harga yang ramah di kantong mahasiswa.</p>
                    </div>
                    <div class="card">
                        <h4>Fokus Mahasiswa 🎓</h4>
                        <p>Kami hanya menghubungkan penjual dan pembeli dari komunitas kampus di Surabaya, lebih aman dan relevan.</p>
                    </div>
                    <div class="card">
                        <h4>Ramah Lingkungan 🌱</h4>
                        <p>Beri kehidupan kedua pada barang. Bantu kota Surabaya menjadi lebih hijau dengan mengurangi limbah.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="section-padding bg-light">
            <div class="container">
                <h3 class="section-title">Kategori Barang Populer</h3>
                <div class="grid-4">
                    <div class="service-item">
                        <span class="icon">📚</span>
                        <h5>Buku & Alat Tulis</h5>
                    </div>
                    <div class="service-item">
                        <span class="icon">💻</span>
                        <h5>Elektronik (Laptop, HP)</h5>
                    </div>
                    <div class="service-item">
                        <span class="icon">🛋️</span>
                        <h5>Perabotan Kos</h5>
                    </div>
                    <div class="service-item">
                        <span class="icon">👗</span>
                        <h5>Pakaian & Aksesori</h5>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="how-to" class="section-padding">
            <div class="container">
                <h3 class="section-title">Mudah Banget! (Cara Jual)</h3>
                <div class="steps-container">
                    <div class="step active" data-step="1">
                        <span class="step-number">1</span>
                        <h5>Foto Barang</h5>
                        <p>Ambil foto jelas dari barang bekas Anda. Tulis deskripsi yang jujur.</p>
                    </div>
                    <div class="step" data-step="2">
                        <span class="step-number">2</span>
                        <h5>Posting & Tunggu</h5>
                        <p>Unggah di platform kami (atau grup/forum yang ditentukan). Tentukan harga terbaik Anda.</p>
                    </div>
                    <div class="step" data-step="3">
                        <span class="step-number">3</span>
                        <h5>COD Kampus</h5>
                        <p>Sepakati waktu dan tempat COD (sangat disarankan di area kampus) dengan pembeli.</p>
                    </div>
                </div>
                <p class="step-info" id="current-step-info">**Langkah 1:** Ambil foto jelas dari barang bekas Anda. Tulis deskripsi yang jujur.</p>
            </div>
        </section>
        
        <section class="testimonial-section bg-light">
            <div class="container">
                <h3 class="section-title">Kata Mereka</h3>
                <blockquote class="testimonial-card">
                    <p>"Bisa dapat laptop bekas kondisi 90% dengan harga separuh! COD-nya di depan rektorat, jadi aman banget. Sangat membantu mahasiswa seperti saya."</p>
                    <footer>- Rajwa (Mahasiswa UNESA)</footer>
                </blockquote>
            </div>
        </section>

        <section id="contact" class="section-padding">
            <div class="container text-center">
                <h3 class="section-title">Tertarik Bergabung?</h3>
                <p>Hubungi kami untuk informasi kemitraan atau jika Anda punya pertanyaan!</p>

                <a>bisa dm melalui Instagram @surabaya_preloved</a> </a>
                
                <p class="small-text">Atau kontak melalui WhatsApp +62 812-2689-0090</p>
            </div>
        </section>
 
    </main>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Surabaya Preloved | Dibuat dengan semangat hemat untuk mahasiswa Surabaya.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* RESET DASAR */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: #efeef5;
    background-color: #24755a;
}

/* UTILITAS */
.container {
    width: 85%;
    max-width: 1200px;
    margin: 0 auto;
}

.text-center {
    text-align: center;
}

.section-padding {
    padding: 80px 0;
}

.bg-light {
    background-color: #0d937f;
}

.section-title {
    font-size: 2.5em;
    font-weight: 700;
    color: #fcffff; /* Warna hijau teal */
    margin-bottom: 40px;
    text-align: center;
}

.grid-3 {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
}

.grid-4 {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    text-align: center;
}

/* HEADER & NAVIGASI */
.header {
    background-color: #070f19;
    box-shadow: 0 2px 4px rgba(54, 49, 49, 0.05);
    position: sticky;
    top: 0;
    z-index: 1000;
    padding: 15px 0;
}

.header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.8em;
    color: #319a8e;
    font-weight: 700;
}

.nav a {
    text-decoration: none;
    color: #f8f2f2;
    margin-left: 25px;
    font-weight: 500;
    transition: color 0.3s;
}

.nav a:hover {
    color: #9cb0ac; /* Warna hijau lebih gelap */
}

/* BUTTONS */
.btn-cta {
    background-color: #0d8b7c;
    color: #0f0606;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s;
}

.btn-cta:hover {
    background-color: #266a5e;
}

.btn-primary {
    background-color: #ffc20c; /* Warna Kuning Ceria */
    color: #333;
    padding: 15px 30px;
    border: none;
    border-radius: 50px;
    font-size: 1.1em;
    font-weight: 600;
    cursor: pointer;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s, background-color 0.2s;
}

.btn-primary:hover {
    background-color: #f2af11;
    transform: translateY(-2px);
}

.btn-secondary {
    background-color: transparent;
    border: 2px solid #152422;
    color: #ffffff;
    padding: 12px 25px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: 600;
    transition: background-color 0.3s, color 0.3s;
}

.btn-secondary:hover {
    background-color: #00796B;
    color: #1d1616;
}

/* HERO SECTION */
.hero {
    background: linear-gradient(135deg, #00796B 0%, #4DB6AC 100%);
    color: #fbf8f8;
    padding: 120px 0;
    text-align: center;
    clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%); /* Efek melengkung di bawah */
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 15px;
    font-weight: 700;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

/* CARD LAYOUT (ABOUT) */
.card {
    background-color: #1c1616;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(109, 58, 58, 0.08);
    transition: transform 0.3s, box-shadow 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.card h4 {
    color: #00796B;
    margin-bottom: 10px;
    font-size: 1.3em;
}

/* SERVICES/KATEGORI */
.service-item {
    background-color: #000000;
    padding: 20px;
    border-radius: 8px;
    border: 1px solid #772828;
    transition: all 0.3s;
}

.service-item:hover {
    background-color: #1d1a1a;
    border-color: #00796B;
    transform: scale(1.05);
}

.service-item .icon {
    display: block;
    font-size: 3em;
    margin-bottom: 10px;
}

/* CARA KERJA (INTERAKTIF) */
.steps-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 30px;
    position: relative;
    padding-bottom: 30px;
}

.steps-container::before {
    content: '';
    position: absolute;
    top: 15px;
    left: 10%;
    right: 10%;
    height: 3px;
    background-color: #9c4545;
}

.step {
    flex: 1;
    text-align: center;
    position: relative;
    padding: 10px;
    cursor: pointer;
    transition: color 0.3s;
}

.step:hover {
    color: #2ca99a;
}

.step-number {
    display: block;
    width: 40px;
    height: 40px;
    line-height: 40px;
    margin: 0 auto 10px;
    background-color: #2a1c1c;
    border: 3px solid #eeeeef;
    border-radius: 50%;
    font-weight: 600;
    transition: all 0.3s;
}

.step.active .step-number {
    background-color: #00796B;
    border-color: #2e7069;
    color: #17cd81;
    transform: scale(1.1);
}

.step-info {
    font-style: italic;
    color: #062813;
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    min-height: 70px;
    display: flex;
    align-items: center;
    justify-content: center;
}

/* TESTIMONIALS */
.testimonial-card {
    max-width: 700px;
    margin: 0 auto;
    background-color: #202125;
    padding: 40px;
    border-radius: 10px;
    border-left: 5px solid #FFC107; /* Garis kuning sebagai penekanan */
    box-shadow: 0 4px 10px rgba(253, 251, 251, 0.05);
}

.testimonial-card p {
    font-size: 1.2em;
    margin-bottom: 15px;
    font-style: italic;
}

.testimonial-card footer {
    font-weight: 600;
    color: #e8f1f0;
    text-align: right;
    display: block;
}

/* FOOTER */
.footer {
    background-color: #312b2b;
    color: #ddd1d1;
    text-align: center;
    padding: 20px 0;
    font-size: 0.9em;
}

/* MEDIA QUERIES untuk Responsif */
@media (max-width: 768px) {
    .header .container {
        flex-direction: column;
    }
    .nav {
        margin-top: 15px;
        text-align: center;
    }
    .nav a {
        margin: 0 10px;
        display: inline-block;
    }
    .hero h2 {
        font-size: 2em;
    }
    .grid-3 {
        grid-template-columns: 1fr;
    }
    .grid-4 {
        grid-template-columns: repeat(2, 1fr);
    }
    .steps-container {
        flex-direction: column;
    }
    .steps-container::before {
        display: none;
    }
    .step {
        width: 100%;
        margin-bottom: 20px;
    }
    .step-number {
        margin: 0 auto 5px;
    }
    .step p {
        display: none; /* Sembunyikan deskripsi di bawah angka untuk mobile */
    }
}
