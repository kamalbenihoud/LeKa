<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Online Store</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background: #444;
            display: flex;
            justify-content: center;
            padding: 0.5em 0;
        }
        nav a {
            color: #fff;
            margin: 0 1em;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 2em 1em;
            background: #f4f4f4;
        }
        .hero h2 {
            margin: 0;
            font-size: 2em;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1em;
            padding: 2em;
        }
        .product {
            border: 1px solid #ddd;
            padding: 1em;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            font-size: 1.2em;
            margin: 0.5em 0;
        }
        .product p {
            margin: 0.5em 0;
            color: #666;
        }
        .product button {
            background: #333;
            color: #fff;
            border: none;
            padding: 0.5em 1em;
            cursor: pointer;
        }
        .product button:hover {
            background: #555;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Online Store</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <div class="hero">
        <h2>Discover Amazing Products</h2>
        <p>High-quality items at unbeatable prices!</p>
    </div>
    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 1">
            <h3>Product 1</h3>
            <p>$19.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 2">
            <h3>Product 2</h3>
            <p>$29.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 3">
            <h3>Product 3</h3>
            <p>$39.99</p>
            <button>Add to Cart</button>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 My Online Store. All Rights Reserved.</p>
    </footer>
</body>
</html>
