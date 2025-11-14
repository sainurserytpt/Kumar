<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GreenLeaf Plants Nursery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f3f7f2;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #2e7d32;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6') no-repeat center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
            font-weight: bold;
            text-shadow: 2px 2px 4px #000;
        }
        .section {
            padding: 40px;
            text-align: center;
        }
        .plants {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            background: white;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.2);
            padding-bottom: 15px;
        }
        .card img {
            width: 100%;
            border-radius: 10px 10px 0 0;
        }
        footer {
            background: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sri Sai Nursery Gardern and Herbal Plants</h1>
        <p>Your Home for Healthy Plants</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#plants">Plants</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">Fresh Plants for Your Garden</div>

    <div id="plants" class="section">
        <h2>Our Plants Collection</h2>
        <div class="plants">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1585314062430-3a3dfc7a6c39" />
                <h3>Rose Plant</h3>
                <p>Beautiful flowering plant.</p>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1518831696273-2c660d1798c5" />
                <h3>Snake Plant</h3>
                <p>Low maintenance indoor plant.</p>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1521940178898-6c6e9c1e6b9a" />
                <h3>Aloe Vera</h3>
                <p>Medicinal and air-purifying plant.</p>
            </div>
        </div>
    </div>

    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: sainurserytpt@goole.com</p>
        <p>Phone: +91 6381864971</p>
        <p>Phone: +91 7904956215</p>
    </div>

    <footer>
        © 2025 Sri Sai Nursery Gardern and Herbal Plants.
    </footer>
</body>
</html>
