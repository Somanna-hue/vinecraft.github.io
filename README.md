<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinecraft - DIY Wine Kits</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #6b1f1f;
            color: #fff;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 1rem;
        }
        header nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .hero {
            text-align: center;
            padding: 4rem 2rem;
            background-color: #ececec;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .btn {
            background-color: #6b1f1f;
            color: #fff;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .shop {
            padding: 2rem;
            text-align: center;
        }
        .shop h2 {
            margin-bottom: 2rem;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 0 auto;
            max-width: 1200px;
        }
        .product-card {
            background: #fff;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product-card img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 1rem;
        }
        .product-card h3 {
            margin-bottom: 1rem;
        }
        .price {
            color: #6b1f1f;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        footer {
            background-color: #6b1f1f;
            color: #fff;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Vinecraft</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Craft Your Own Wine at Home</h1>
        <p>Discover the joy of winemaking with our eco-friendly DIY wine kits.</p>
        <a href="#shop" class="btn">Shop Now</a>
    </section>

    <section class="shop" id="shop">
        <h2>Our Kits</h2>
        <div class="product-grid">
            <div class="product-card">
                <h3>Basic Kit</h3>
                <p>Perfect for first-time winemakers.</p>
                <p class="price">₹200</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product-card">
                <h3>Premium Kit</h3>
                <p>Enhanced experience with premium ingredients.</p>
                <p class="price">₹600</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product-card">
                <h3>Luxury Kit</h3>
                <p>The ultimate winemaking experience.</p>
                <p class="price">₹1200</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Vinecraft. WhatsApp 9692136350.</p>
    </footer>
</body>
</html>
