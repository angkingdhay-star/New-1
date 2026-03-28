# New-1
New 1
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan - Anggun & Angking</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Great+Vibes&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    <style>
        :root {
            --gold: #c5a059;
            --dark-brown: #4a3728;
            --bg-color: #fdfaf5;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: var(--bg-color);
            color: var(--dark-brown);
            text-align: center;
        }

        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&q=80') center/cover;
            color: white;
            padding: 20px;
        }

        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 4rem;
            margin: 10px 0;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            letter-spacing: 3px;
            text-transform: uppercase;
            font-size: 1.2rem;
        }

        .content-section {
            padding: 60px 20px;
            max-width: 800px;
            margin: auto;
        }

        .card {
            background: white;
            padding: 40px 20px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            margin-bottom: 30px;
            border: 1px solid #eee;
        }

        .couple-name {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
            color: var(--gold);
            margin: 15px 0;
        }

        .date-box {
            font-weight: bold;
            font-size: 1.1rem;
            border-top: 1px solid var(--gold);
            border-bottom: 1px solid var(--gold);
            display: inline-block;
            padding: 10px 20px;
            margin: 20px 0;
        }

        .btn {
            background-color: var(--gold);
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 50px;
            display: inline-block;
            margin-top: 20px;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: var(--dark-brown);
        }

        footer {
            padding: 40px;
            font-size: 0.8rem;
            opacity: 0.7;
        }
    </style>
</head>
<body>

    <section class="hero">
        <h2>The Wedding of</h2>
        <h1>Anggun & Angking</h1>
        <p>16 . 08 . 2026</p>
    </section>

    <section class="content-section">
        <p><i>Assalamu’alaikum Warahmatullahi Wabarakatuh</i></p>
        <p>Maha suci Allah yang telah menciptakan mahluk-Nya berpasang-pasangan. Dengan memohon rahmat-Nya, kami bermaksud mengundang Bapak/Ibu/Saudara/i di pernikahan kami:</p>
        
        <div class="couple-name">Adea Anggun Novita Sari (Anggun)</div>
        <p>&</p>
        <div class="couple-name">Muhamad Hidayatullah (Angking)</div>
    </section>

    <section class="content-section">
        <div class="card">
            <h3>Akad Nikah</h3>
            <div class="date-box">Jumat, 14 Agustus 2026</div>
            <p>09.00 - Selesai</p>
            <p><b>Lokasi:</b> KUA Kec. Dusun Tengah</p>
        </div>

        <div class="card">
            <h3>Resepsi</h3>
            <div class="date-box">Minggu, 16 Agustus 2026</div>
            <p>08.00 - Selesai</p>
            <p><b>Lokasi:</b> Samping RM. Kalijo Ampah<br>(Rumah Mempelai Wanita)</p>
            <a href="https://www.google.com/maps/search/RM.+Kalijo+Ampah" target="_blank" class="btn">Buka Google Maps</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Anggun & Angking Wedding Invitation</p>
    </footer>

</body>
</html>
