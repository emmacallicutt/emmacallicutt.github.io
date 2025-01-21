<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Portfolio</title>
    <style>
        body {
            font-family: Georgia, serif;
            background-color: #f5f5dc; /* Cream color */
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #eee;
            border-bottom: 2px solid #ccc;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 15px;
            font-size: 1.2em;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            max-width: 900px;
            margin: 30px auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 40px;
        }

        section h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        section p {
            font-size: 1.1em;
            line-height: 1.6;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }

        .gallery img {
            width: 100%;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #eee;
            border-top: 2px solid #ccc;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Artist Name</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#gallery">Gallery</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About</h2>
            <p>Welcome to my portfolio! I am an artist passionate about creating unique and meaningful pieces that inspire and connect. My work spans various mediums, including painting, sculpture, and digital art.</p>
        </section>

        <section id="gallery">
            <h2>Gallery</h2>
            <div class="gallery">
                <img src="placeholder1.jpg" alt="Artwork 1">
                <img src="placeholder2.jpg" alt="Artwork 2">
                <img src="placeholder3.jpg" alt="Artwork 3">
                <img src="placeholder4.jpg" alt="Artwork 4">
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you'd like to get in touch, feel free to email me at <a href="mailto:artist@example.com">artist@example.com</a>.</p>
        </section>
    </main>

    <footer>
        &copy; 2025 Artist Name. All rights reserved.
    </footer>
</body>
</html>

