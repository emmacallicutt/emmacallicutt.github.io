<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: "Times New Roman", serif; /* Set Times New Roman as the font for all text */
            margin: 0;
            padding: 0;
            background-color: #f4f4f9; /* Cream/white background */
            color: #000; /* Black text color */
        }
        header {
            background-color: #f4f4f9; /* Same cream/white color as background */
            color: black; /* Black text color in header */
            padding: 1rem;
            width: 100%;
        }
        header h1 {
            font-size: 1.4rem; /* Smaller heading text */
        }
        nav {
            margin: 1rem 0;
            display: block; /* Stack the navigation links vertically */
            position: relative; /* Enable offset positioning */
            top: -40px; /* Move navigation bar up further */
            left: 18px; /* Move navigation bar slightly to the right */
        }
        nav a {
            display: block; /* Make each link a block-level element */
            margin: 0.5rem 0; /* Add vertical spacing between links */
            text-decoration: none;
            color: black; /* Black link color */
            font-weight: bold;
            font-size: 0.9rem; /* Slightly smaller nav links */
        }
        nav a:hover {
            color: #007BFF;
        }
        section {
            display: flex;
            flex-direction: column; /* Stack the images vertically */
            align-items: flex-end; /* Align images to the right */
            margin: 1rem;
        }
        section div.text {
            flex: 1;
            padding-right: 1rem;
            font-size: 0.8rem; /* Slightly smaller section text */
        }
        section h2 {
            font-size: 1.2rem; /* Slightly smaller section headings */
        }
        section div.image {
            flex: 1;
            margin: 1rem 0; /* Add vertical spacing between images */
            text-align: right;
        }
        footer {
            text-align: left;
            margin: 2rem 1rem;
            font-size: 0.7rem; /* Slightly smaller footer text */
            color: #777;
        }
    </style>
</head>
<body>
    <header>
        <h1>Emma Callicutt</h1>
    </header>
    <nav>
        <a href="#about">2024</a>
        <a href="#projects">2023</a>
        <a href="#projects">2022</a>
        <a href="#contact">about / cv</a>
    </nav>
    <section id="about">
        <div class="text">
            <h2></h2>
            <p></p>
        </div>
        <div class="image">
            <!-- Place an image here -->
            <img src="ooo" alt="Image 1" style="max-width: 100%; height: auto;">
        </div>
        <div class="image">
            <!-- Place an image here -->
            <img src="your-image2.jpg" alt="Image 2" style="max-width: 100%; height: auto;">
        </div>
        <div class="image">
            <!-- Place an image here -->
            <img src="your-image3.jpg" alt="Image 3" style="max-width: 100%; height: auto;">
        </div>
    </section>
    <footer>
        &copy; 2025 Emma Callicutt. All rights reserved.
    </footer>
</body>
</html>

