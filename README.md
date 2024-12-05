# Teman baik <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Cinta</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Selamat Datang di Website Cinta</h1>
        <p>Temukan inspirasi dan ungkapan cinta di sini!</p>
    </header>
    
    <main>
        <section id="quotes">
            <h2>Kutipan Cinta</h2>
            <blockquote id="quote">"Cinta adalah jembatan antara dua hati."</blockquote>
            <button onclick="newQuote()">Dapatkan Kutipan Baru</button>
        </section>

        <section id="love-letters">
            <h2>Surat Cinta</h2>
            <textarea id="letter" placeholder="Tulis surat cintamu di sini..."></textarea>
            <button onclick="sendLetter()">Kirim Surat</button>
            <div id="response"></div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Website Cinta. Semua hak dilindungi.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
