<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Vinecraft - Craft your own vintages at home with our DIY wine-making kits. Explore a variety of options and start your winemaking journey today!">
    <title>Vinecraft - DIY Wine Kits</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="https://images.unsplash.com/photo-1510812431401-41d2bd2722f3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80" alt="Vinecraft Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#tutorials">Tutorials</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="cart-icon">
                <a href="#cart">🛒 Cart</a>
            </div>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="hero">
            <div class="hero-content">
                <h1>Craft Your Own Vintages at Home</h1>
                <p>Explore our eco-friendly, customizable DIY wine kits. Perfect for beginners and enthusiasts alike.</p>
                <a href="#shop" class="btn">Shop Now</a>
                <a href="#about" class="btn-outline">Learn More</a>
            </div>
        </section>

        <!-- Shop Section -->
        <section id="shop" class="shop">
            <h2>Our Kits</h2>
            <div class="product-grid">
                <div class="product-card">
                    <img src="basic-kit.jpg" alt="Basic Kit">
                    <h3>Basic Kit</h3>
                    <p>Perfect for first-time winemakers. Includes essentials for a delightful experience.</p>
                    <p class="price">₹200</p>
                    <a href="#" class="btn">Add to Cart</a>
                </div>
                <div class="product-card">
                    <img src="premium-kit.jpg" alt="Premium Kit">
                    <h3>Premium Kit</h3>
                    <p>A step-up for enthusiasts, offering more flavors and ingredients.</p>
                    <p class="price">₹600</p>
                    <a href="#" class="btn">Add to Cart</a>
                </div>
                <div class="product-card">
                    <img src="luxury-kit.jpg" alt="Luxury Kit">
                    <h3>Luxury Kit</h3>
                    <p>For those who want to craft premium-quality wines at home.</p>
                    <p class="price">₹1200</p>
                    <a href="#" class="btn">Add to Cart</a>
                </div>
                <div class="product-card">
                    <img src="royale-kit.jpg" alt="Royale Kit">
                    <h3>Royale Kit</h3>
                    <p>The ultimate winemaking experience with top-notch ingredients.</p>
                    <p class="price">₹1500</p>
                    <a href="#" class="btn">Add to Cart</a>
                </div>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="about">
            <h2>About Us</h2>
            <p>At Vinecraft, we are passionate about bringing the joy of winemaking to everyone. Our kits are designed to be simple, sustainable, and fun, using locally sourced ingredients to create memorable experiences.</p>
        </section>

        <!-- Tutorials Section -->
        <section id="tutorials" class="tutorials">
            <h2>DIY Tutorials</h2>
            <div class="tutorial-grid">
                <div class="tutorial-card">
                    <img src="tutorial1.jpg" alt="Step-by-Step Guide">
                    <h3>Step-by-Step Guide</h3>
                    <p>Learn how to use our kits with easy-to-follow video tutorials.</p>
                    <a href="#" class="btn">Watch Now</a>
                </div>
                <div class="tutorial-card">
                    <img src="tutorial2.jpg" alt="Tips & Tricks">
                    <h3>Tips & Tricks</h3>
                    <p>Discover creative ways to customize your wine flavors.</p>
                    <a href="#" class="btn">Learn More</a>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit" class="btn">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Vinecraft. All Rights Reserved.</p>
        <div class="social-links">
            <a href="#">Instagram</a> |
            <a href="#">Facebook</a> |
            <a href="#">Pinterest</a>
        </div>
    </footer>
</body>
</html>
