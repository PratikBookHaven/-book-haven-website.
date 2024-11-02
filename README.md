<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Haven - Quality and Affordable Notebooks</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Book Haven</h1>
        <p>Your one-stop shop for quality and affordable notebooks for schools and colleges</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#products">Our Products</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>At Book Haven, we specialize in providing high-quality, affordable notebooks perfect for students and professionals. From single-line notebooks to graph paper and dotted journals, we have a wide selection to meet all your needs.</p>
    </section>

    <section id="products" class="section">
        <h2>Our Products</h2>
        <div class="product">
            <h3>Single-Line Notebook</h3>
            <p>Perfect for everyday note-taking with premium paper quality. Price: ₹30</p>
        </div>
        <div class="product">
            <h3>Graph Notebook</h3>
            <p>Ideal for math and science students. Price: ₹40</p>
        </div>
        <div class="product">
            <h3>Dotted Journal</h3>
            <p>Great for creative notes and bullet journaling. Price: ₹45</p>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>For inquiries, reach out to us at <a href="mailto:info@bookhaven.com">info@bookhaven.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Book Haven. All rights reserved.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
    background-color: #f4f4f9;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 10px;
    background-color: #444;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.section {
    padding: 20px;
    max-width: 800px;
    margin: 20px auto;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h1, h2, h3 {
    margin-bottom: 10px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
}
