
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Website Pribadi Saya</title>
    <style>
        /* Umum */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
            line-height: 1.6;
        }

        h1, h2 {
            font-family: 'Helvetica Neue', sans-serif;
            font-weight: 700;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header */
        header {
            background-color: #6c63ff;
            color: white;
            text-align: center;
            padding: 2em 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 3em;
        }
       @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
       }

       header {
           animation: fadeIn 1s ease-in;
       }

        header p {
            font-size: 1.2em;
            margin-top: 0.5em;
        }

        /* Navigasi */
        nav {
            display: flex;
            justify-content: center;
            background-color: #f8f8f8;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        nav a {
            color: #333;
            padding: 18px 30px;
            text-align: center;
            font-size: 1.1em;
            transition: background-color 0.3s, color 0.3s;
        }

        nav a:hover {
            background-color: #6c63ff;
            color: white;
        }

        /* Profil */
        .profile {
            text-align: center;
            margin: 3em 0;
            background: linear-gradient(135deg, #6c63ff 0%, #7e55ff 100%);
            padding: 2em;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);
        }

        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 5px solid white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        .profile h2 {
            margin-top: 1em;
            color: white;
            font-size: 2em;
        }

        .profile p {
            color: #f9f9f9;
            font-size: 1.2em;
            max-width: 80%;
            margin: 1em auto;
        }

        /* Galeri Foto */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin: 3em 0;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 45px rgba(0, 0, 0, 0.2);
        }

        .gallery {
             display: flex;
            flex-wrap: wrap;
       }

        .gallery-item {
             width: 30%;
             margin: 10px;
             transition: transform 0.2s;
       }

      .gallery-item:hover {
             transform: scale(1.05);
       }
        /* Kontak */
        .contact {
            background-color: #f7f7f7;
            padding: 2em;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
            margin-bottom: 3em;
        }

        .contact h2 {
            font-size: 2.5em;
            color: #333;
            text-align: center;
            margin-bottom: 1em;
        }

        .contact ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        .contact ul li {
            font-size: 1.2em;
            margin: 10px 0;
        }

        .social-links {
            text-align: center;
            margin-top: 1.5em;
        }

        .social-links a {
            margin: 0 15px;
            color: #333;
            font-size: 2em;
            transition: color 0.3s;
        }

        .social-links a:hover {
            color: #6c63ff;
        }

        /* Footer */
        footer {
            background-color: #000080;
            color: white;
            padding: 1.5em 0;
            text-align: center;
        }

        .parallax {
             background-image: url('background.jpg');
             height: 400px;
             background-attachment: fixed;
             background-position: center;
             background-repeat: no-repeat;
             background-size: cover;
      }
    </style>
</head>
<body>

    <header>
        <h1>Website Pribadi Gue</h1>
        <p>Yokoso orang orang sdm Tinggi</p>
    </header>

    <nav>
        <a href="#about">Tentang Gue</a>
        <a href="#gallery">Galeri random</a>
        <a href="#contact">Kontak</a>
    </nav>

    <section id="about">
        <div class="profile">
            <img src="pann1.jpg" alt="Foto Profil">
            <h2>Panji syahputra</h2>
            <p>Seorang pelajar yang baru belajar membuat web walaupun masih html dan css jan di hujat bang wkwkwk,enjoy kasih rating web buatan gua wkwkwk,hobi cuma main game bang,umur 17 tahun,tinggal di jakarta,elitis dikit,takut sama kecoa bismillah kedepannya bisa lebih bagus webnya lagi otw java script</p>
        </div>
    </section>

    <section id="projects">
        <h2>Lagu favorit</h2>
        <ul>
            <li>salvastore: <a href="#">lana del rey</a></li>
            <li>we can't be your friend: <a href="#">ariana grande</a></li>
            <li>A little of piece heaven: <a href="#">avenged sevenfold</a></li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Galeri Foto</h2>
        <div class="gallery">
            <img src="kenn1.jpg" alt="Foto 1" class="gallery-item">
            <img src="mann1.jpg" alt="Foto 2" class="gallery-item">
            <img src="wass1.jpg" alt="Foto 3" class="gallery-item">
            <img src="fuu1.jpg" alt="Foto 4" class="gallery-item">
            <img src="https://beta.tvarenasport.com/data/images/2023-03-24/2352_tan2023-03-2405183162-3_f.jpg" alt="Foto 5" class="gallery-item">
            <img src="uruma1.jpg" alt="Foto 6" class="gallery-item">
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Kontak gue</h2>
        <ul>
            <li>Email: <a href="matkiong2008@gmail.com">matkiong2008@gmail.com</a></li>
            <li>Telepon: +62 855 9127 0832</li>
        </ul>
        <div class="social-links">
            <a href="https://www.instagram.com/kennethcelloo?igsh=a2d6OGsxZjYyMWFy" target="_blank">Instagram</a>
            <a href="https://www.tiktok.com/@kenn.2602?_t=ZS-8u7sOVashuS&_r=1" target="_blank">TikTok</a>
            <a href="https://www.facebook.com/panji.syahputra.7311" target="_blank">Facebook</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Website Pribadi gua,hakcip di lindungi gua sendiri.</p>
    </footer>
    <div class="parallax">
    </div>
    <script src="main.js"></script>
</body>
</html>
