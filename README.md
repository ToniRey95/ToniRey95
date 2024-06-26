<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ihr Fotografie-Portfolio</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            color: white;
            background-color: black;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            padding: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .gallery img {
            width: 300px;
            margin: 10px;
            transition: transform 0.5s;
        }
        .gallery img:hover {
            transform: scale(1.1);
        }
        footer {
            margin-top: 20px;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ihr Name</h1>
        <p>Willkommen zu meinem Portfolio</p>
    </header>
    <section class="gallery">
        <img src="bild1.jpg" alt="Bild 1">
        <img src="bild2.jpg" alt="Bild 2">
        <img src="bild3.jpg" alt="Bild 3">
        <!-- Weitere Bilder hinzufügen -->
    </section>
    <section>
        <h2>Über mich</h2>
        <p>Hier können Informationen über Ihre Karriere und Ihren fotografischen Ansatz stehen.</p>
    </section>
    <footer>
        <p>Kontaktieren Sie mich: <a href="mailto:ihre.email@beispiel.com">ihre.email@beispiel.com</a></p>
    </footer>
</body>
</html>

<!---
ToniRey95/ToniRey95 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
