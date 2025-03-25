<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fotoaparatul Ideal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f1f1;
            color: #333;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #e6e6e6;
            padding: 10px;
        }

        nav a {
            color: #333;
            padding: 15px 25px;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav a:hover {
            background-color: #d4d4d4;
            transition: background-color 0.3s;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .photo-gallery div {
            margin: 10px;
            text-align: center;
        }

        .photo-gallery img {
            width: 300px;
            height: auto;
            border-radius: 8px;
            transition: transform 0.3s ease-in-out;
        }

        .photo-gallery img:hover {
            transform: scale(1.05);
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        h2 {
            color: #333;
        }

        /* Ceas */
        #ceas {
            font-size: 2em;
            font-weight: bold;
            color: #333;
        }

        /* Formular de contact */
        form {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }

        label {
            margin-top: 10px;
        }

        input, textarea {
            margin-bottom: 10px;
            padding: 8px;
            font-size: 1em;
            width: 100%;
            max-width: 400px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        input[type="submit"] {
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1.2em;
        }

        input[type="submit"]:hover {
            background-color: #555;
        }

        /* Imagine background */
        .image-bg {
            background-image: url('https://images.ctfassets.net/hrltx12pl8hq/6eGBYyHIdTsKBTfV5N5rNG/42c150cd8f1fd21e0e59340721dc6a64/3_abstract.webp');
            background-size: cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 1.5em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Găsește Fotoaparatele Perfecte pentru Tine</h1>
    </header>

    <!-- Meniu de navigare -->
    <nav>
        <a href="#acasa">Acasă</a>
        <a href="#despre">Despre Noi</a>
        <a href="#aparate">Fotoaparatul Ideal</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Secțiunea Ceas -->
    <section id="ceas">
        <h2 id="ora">Ceas</h2>
        <p id="data">Data: <span id="dataCurenta"></span></p>
        <p id="oraCurenta"></p>
    </section>

    <!-- Secțiunea "Acasă" -->
    <section id="acasa">
        <h2>Ce vei găsi aici?</h2>
        <p>Pe acest site îți oferim informații despre cele mai bune fotoaparate disponibile pe piață, cu imagini și descriere detaliată a fiecărui model. Alege-l pe cel care se potrivește cel mai bine nevoilor tale!</p>
    </section>

    <!-- Secțiunea "Despre Noi" -->
    <section id="despre">
        <h2>Despre Noi</h2>
        <p>Suntem o echipă de entuziaști ai fotografiei și tehnologiei. Ne dedicăm să îți oferim cele mai precise și utile informații despre fotoaparate, pentru a te ajuta să faci cea mai bună alegere.</p>
    </section>

    <!-- Secțiunea "Fotoaparatul Ideal" cu galeria de imagini -->
    <section id="aparate">
        <h2>Galeria Fotoaparatelor</h2>
        <div class="photo-gallery">
            <div>
                <a href="https://www.pandashop.md/i/products/78/787954.jpg" target="_blank">
                    <img src="https://www.pandashop.md/i/products/78/787954.jpg" alt="Fotoaparat 1">
                </a>
                <p>Fotoaparat 1 - Canon EOS 2000D</p>
            </div>
            <div>
                <a href="https://cdn.uno.md/storage/images/Product/168752/info/2b-cifrovoj-fotoapparat-canon-eos-2000d-18-55-is-ii-kit-2728c008.webp?v=1603723078" target="_blank">
                    <img src="https://cdn.uno.md/storage/images/Product/168752/info/2b-cifrovoj-fotoapparat-canon-eos-2000d-18-55-is-ii-kit-2728c008.webp?v=1603723078" alt="Fotoaparat 2">
                </a>
                <p>Fotoaparat 2 - Canon EOS 2000D Kit</p>
            </div>
            <div>
                <a href="https://gomagcdn.ro/domains/fotohobby.ro/files/product/large/canon-eos-r3-aparat-foto-mirrorless-full-frame-5714-9741.jpg" target="_blank">
                    <img src="https://gomagcdn.ro/domains/fotohobby.ro/files/product/large/canon-eos-r3-aparat-foto-mirrorless-full-frame-5714-9741.jpg" alt="Fotoaparat 3">
                </a>
                <p>Fotoaparat 3 - Canon EOS R3</p>
            </div>
            <div>
                <a href="https://smadshop.md/image/cache/product/foto-video-audio/fotoapparaty/canon/cifrovoj-fotoapparat-canon-eos-m200-ef-m-15-45-mm-f-3.5-6.3-is-stm-ef-m-55-200mm-f-4.5-6.3-is-stm-black-1280x960.jpeg" target="_blank">
                    <img src="https://smadshop.md/image/cache/product/foto-video-audio/fotoapparaty/canon/cifrovoj-fotoapparat-canon-eos-m200-ef-m-15-45-mm-f-3.5-6.3-is-stm-ef-m-55-200mm-f-4.5-6.3-is-stm-black-1280x960.jpeg" alt="Fotoaparat 4">
                </a>
                <p>Fotoaparat 4 - Canon EOS M200</p>
            </div>
        </div>
    </section>

    <!-- Secțiunea "Contact" -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Pentru întrebări și informații suplimentare, nu ezita să ne contactezi la:</p>
        <p>Adresa: Strada Exemplu 123, București, România</p>
        <p>Telefon: +373 676 11 312</p>
        <p>Email: <a href="mailto:contact@fotoaparate.com">contact@fotoaparate.com</a></p>

        <h3>Formular de Contact</h3>
        <form action="mailto:contact@fotoaparate.com" method="post" enctype="text/plain">
            <label for="nume">Nume:</label>
            <input type="text" id="nume" name="nume" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mesaj">Mesaj:</label>
            <textarea id="mesaj" name="mesaj" rows="4" required></textarea>
            <input type="submit" value="Trimite">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Fotoaparatele Perfecte. Toate drepturile rezervate.</p>
    </footer>

    <!-- Script pentru Ceas și Data -->
    <script>
        function updateTime() {
            var now = new Date();
            var hours = now.getHours().toString().padStart(2, '0');
            var minutes = now.getMinutes().toString().padStart(2, '0');
            var seconds = now.getSeconds().toString().padStart(2, '0');
            document.getElementById('oraCurenta').innerHTML = hours + ":" + minutes + ":" + seconds;

            var date = now.toLocaleDateString('ro-RO');
            document.getElementById('dataCurenta').innerHTML = date;
        }

        setInterval(updateTime, 1000);
        updateTime();
    </script>

</body>
</html>
