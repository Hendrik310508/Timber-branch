
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Timber-Branch</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #111;
            color: #f5f5f5;
        }
        header {
            background-color: #222;
            padding: 2rem;
            text-align: center;
            border-bottom: 4px solid #FFD700;
        }
        header h1 {
            font-size: 3rem;
            color: #FFD700;
            text-transform: uppercase;
            letter-spacing: 3px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 1rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 2rem;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FFD700;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1616627450086-1b2c6f4f3b24') center/cover no-repeat;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 2rem;
        }
        .hero h2 {
            font-size: 3rem;
            background: rgba(0, 0, 0, 0.6);
            padding: 1rem 2rem;
            border: 2px solid #FFD700;
        }
        .section {
            padding: 3rem;
            text-align: center;
        }
        .section h3 {
            font-size: 2rem;
            color: #FFD700;
            margin-bottom: 1rem;
        }
        .contact {
            background-color: #222;
            padding: 2rem;
        }
        footer {
            background-color: #111;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
            color: #888;
        }
    </style>
</head>
<body>

<header>
    <h1>Timber-Branch</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h2>Custom Wood Décor with Soul</h2>
</section>

<section class="section">
    <h3>About Us</h3>
    <p>We craft unique wood-based home décor items that add warmth and style to any space. From stands and cabinets to candle holders and lanterns — each piece tells a story.</p>
</section>

<section class="section" style="background-color: #1a1a1a;">
    <h3>Services</h3>
    <p>Custom orders made to your reference photos. High quality, one-of-a-kind woodwork tailored just for you.</p>
</section>

<section class="section contact">
    <h3>Contact</h3>
    <p>Email us with reference photos at <strong>timberbranch@example.com</strong></p>
</section>

<footer>
    &copy; 2025 Timber-Branch. All rights reserved.
</footer>

</body>
</html>

