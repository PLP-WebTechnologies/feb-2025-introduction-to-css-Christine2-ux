<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>

    <section class="content-section">
        <h2>About Me</h2>
        <p class="description">This is a brief description about the page. I'm learning how to style HTML using CSS!</p>
        <img src="image/nature image.jpeg" alt="nature image" class="Styled image">
    </section>

    <footer class="footer">
        <p>&copy; 2025 My Website</p>
    </footer>

</body>
</html>



style.css
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

#main-header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
    border-bottom: 5px solid #000;
}

.content-section {
    margin: 20px;
    padding: 20px;
    background-color: white;
    border: 2px solid #ccc;
    border-radius: 10px;
}

.description {
    color: #555;
    line-height: 1.6;
    font-size: 18px;
}

.styled-image {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 20px 0;
    border: 3px solid #000;
    border-radius: 10px;
}

.footer {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
    position: fixed;
    width: 100%;
    bottom: 0;
}

