# Amazon_demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Amazon-like Layout</title>
    <style>
        /* --- Basic CSS for Visualization --- */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5; /* Light gray background */
        }

        /* 1. Header Styles */
        header {
            background-color: #232f3e; /* Dark Amazon-like blue/black */
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff9900; /* Amazon orange */
        }

        .nav-link {
            color: white;
            text-decoration: none;
            margin-left: 15px;
        }

        /* 2. Main Content Body Styles */
        main {
            padding: 20px;
            min-height: 600px; /* Ensures the body takes up space */
            background-color: white;
            max-width: 1200px; /* Example max width for content */
            margin: 0 auto; /* Center the content */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .product-card {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
        }

        /* 3. Footer Styles */
        footer {
            background-color: #232f3e; /* Same as header */
            color: white;
            padding: 20px 0;
            text-align: center;
            margin-top: 20px;
        }

        .footer-nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">amazon-clone</div>
        <nav>
            <a href="#" class="nav-link">Departments</a>
            <a href="#" class="nav-link">Customer Service</a>
            <a href="#" class="nav-link">Sign In</a>
            <a href="#" class="nav-link">Cart (0)</a>
        </nav>
    </header>

    <main>
        <h1>🛒 Today's Top Deals</h1>
        <p>A section for featured products or advertising banners.</p>

        <div class="product-grid">
            <div class="product-card">
                <h3>Product 1</h3>
                <p>Great Item Description.</p>
                <strong>$19.99</strong>
            </div>
            <div class="product-card">
                <h3>Product 2</h3>
                <p>Amazing New Gadget.</p>
                <strong>$99.50</strong>
            </div>
            <div class="product-card">
                <h3>Product 3</h3>
                <p>Must-Have Book.</p>
                <strong>$12.00</strong>
            </div>
        </div>

        <p style="margin-top: 30px;">More content would go here, such as personalized recommendations, secondary banners, etc.</p>
    </main>

    <footer>
        <div class="footer-nav">
            <a href="#">About Us</a> |
            <a href="#">Careers</a> |
            <a href="#">Sell on Amazon</a> |
            <a href="#">Help</a>
        </div>
        <p style="margin-top: 10px;">&copy; 2025, Amazon Clone Inc. or its affiliates</p>
    </footer>

</body>
</html>
