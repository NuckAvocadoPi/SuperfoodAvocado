<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NuckAvocadoPi - Jual Avocado Lokal ke Internasional</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>NuckAvocadoPi</h1>
        <nav>
            <ul>
                <li><a href="#about">Tentang Kami</a></li>
                <li><a href="#products">Produk</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>Tentang Kami</h2>
        <p>NuckAvocadoPi adalah platform untuk menjual avocado lokal ke internasional. Kami menyediakan avocado berkualitas tinggi langsung dari petani lokal dengan harga yang bersaing.</p>
    </section>
    <section id="products">
        <h2>Produk Kami</h2>
        <div class="product">
            <img src="avocado.jpg" alt="Avocado">
            <h3>Avocado Segar</h3>
            <p>Kami menawarkan avocado segar dengan kualitas terbaik yang dipetik langsung dari kebun kami.</p>
        </div>
        <!-- tambahkan lebih banyak produk di sini jika diperlukan -->
    </section>
    <section id="contact">
        <h2>Hubungi Kami</h2>
        <p>Jika Anda memiliki pertanyaan atau ingin memesan produk kami, silakan hubungi kami di email: info@nuckavocadopi.com atau melalui formulir di bawah ini.</p>
        <form action="submit.php" method="post">
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Pesan:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Kirim</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 NuckAvocadoPi - Jual Avocado Lokal ke Internasional</p>
    </footer>
</body>
</html>

