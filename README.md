Undangan Pernikahan
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">

<style>
    :root {
        --gold: #b38e44; /* Gold lebih deep agar terlihat mewah */
        --dark-brown: #2d241e;
        --bg-color: #faf7f2;
        --accent: #d4af37;
    }

    body {
        margin: 0;
        padding: 0;
        font-family: 'Montserrat', sans-serif;
        background-color: var(--bg-color);
        color: var(--dark-brown);
        text-align: center;
        line-height: 1.8;
    }

    /* Hero Section dengan Efek Parallax Sederhana */
    .hero {
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), 
                    url('https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&q=80') center/cover no-repeat;
        color: white;
        padding: 20px;
        position: relative;
    }

    /* Animasi Halus */
    .hero h1, .hero h2, .hero p {
        animation: fadeInUp 1.5s ease;
    }

    h1 {
        font-family: 'Great Vibes', cursive;
        font-size: clamp(3rem, 10vw, 5.5rem); /* Ukuran adaptif */
        margin: 15px 0;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }

    h2 {
        font-family: 'Playfair Display', serif;
        letter-spacing: 5px;
        text-transform: uppercase;
        font-size: 1rem;
        font-weight: 400;
    }

    .content-section {
        padding: 100px 20px;
        max-width: 900px;
        margin: auto;
    }

    /* Card Desain Mewah */
    .card {
        background: white;
        padding: 60px 30px;
        border-radius: 4px; /* Sudut lebih tajam agar terlihat formal */
        box-shadow: 0 20px 50px rgba(0,0,0,0.03);
        margin-bottom: 40px;
        position: relative;
        overflow: hidden;
        border: 1px solid rgba(179, 142, 68, 0.2); /* Border gold tipis */
    }

    /* Ornamen Sudut (Opsional) */
    .card::before {
        content: "";
        position: absolute;
        top: 10px; left: 10px; right: 10px; bottom: 10px;
        border: 1px solid rgba(179, 142, 68, 0.1);
        pointer-events: none;
    }

    .couple-
