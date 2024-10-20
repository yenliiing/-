/art-portfolio
│
├── index.html
├── about.html
├── style.css
├── script.js
├── images/
│   ├── artwork1.jpg
│   ├── artwork2.jpg
│   ├── artwork3.jpg
│   └── ... (更多藝術作品圖片)
└── contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art Gallery - Artist's Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="gallery">
        <h1>Artworks</h1>
        <div class="gallery-container">
            <div class="gallery-item">
                <img src="images/artwork1.jpg" alt="Artwork 1">
                <p>Artwork Title 1</p>
            </div>
            <div class="gallery-item">
                <img src="images/artwork2.jpg" alt="Artwork 2">
                <p>Artwork Title 2</p>
            </div>
            <div class="gallery-item">
                <img src="images/artwork3.jpg" alt="Artwork 3">
                <p>Artwork Title 3</p>
            </div>
            <!-- 更多作品 -->
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Artist Name. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About the Artist</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h1>About the Artist</h1>
        <p>Write a biography of the artist, highlighting their background, style, influences, and accomplishments. This page should provide insight into the artist's creative journey and any major exhibitions or recognitions.</p>
    </section>

    <footer>
        <p>&copy; 2024 Artist Name. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact the Artist</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="contact">
        <h1>Contact the Artist</h1>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Artist Name. All rights reserved.</p>
    </footer>
</body>
</html>
/* General website styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    padding: 10px;
    color: white;
}

header nav ul {
    list-style-type: none;
    text-align: center;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 50px;
    text-align: center;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 20px;
    position: absolute;
    width: 100%;
    bottom: 0;
}

#gallery {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.gallery-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.gallery-item {
    margin: 20px;
    width: 250px;
    border: 1px solid #ccc;
    padding: 10px;
    background-color: white;
}

.gallery-item img {
    width: 100%;
    height: auto;
}

form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

form label {
    text-align: left;
    margin-bottom: 5px;
}

form input, form textarea {
    margin-bottom: 15px;
    padding: 10px;
    width: 100%;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    padding: 10px 15px;
    background-color: #333;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
// Simple JavaScript to log a message
console.log("Welcome to the Artist's Portfolio!");
