<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Addy Power Wash | Professional Cleaning Services</title>
    <style>
        /* This section (CSS) controls the entire look of the site */
        :root {
            --main-color: #00AEEF; /* Sky Blue */
            --accent-color: #FFDE00; /* Sunny Yellow */
            --text-color: #333333; /* Dark Gray */
            --background-color: #f9f9f9;
        }

        /* 1. Cartoonish "Drawn-Line" Effects */
        * {
            box-sizing: border-box;
            border-color: #222 !important; /* Thick borders for a cartoon outline */
        }

        body {
            font-family: 'Poppins', sans-serif; /* A rounded, friendly font */
            background-color: var(--background-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* 2. Your Logo Header / Hero Section */
        .hero {
            background-color: var(--main-color);
            background-image: linear-gradient(135deg, var(--main-color) 0%, #a2d9ff 100%); /* Blue gradient for sky */
            text-align: center;
            padding: 100px 20px;
            border-bottom: 5px solid #222; /* Cartoon underline */
        }

        .hero img {
            max-width: 300px; /* Adjust size as needed */
            height: auto;
            border: 5px solid white;
            border-radius: 50%; /* Makes your logo circular */
            box-shadow: 10px 10px 0px rgba(0,0,0,0.2); /* Cartoon shadow effect */
            margin-bottom: 20px;
        }

        /* 3. Rounded "Bubble" Panels */
        .panel {
            background: white;
            border: 5px solid #222; /* Thicker outline */
            border-radius: 25px; /* Fully rounded corners for a bubble look */
            box-shadow: 10px 10px 0px var(--accent-color); /* Bright cartoon shadow */
            padding: 40px;
            margin: 40px auto;
            max-width: 800px;
        }

        .cta-button {
            display: inline-block;
            background-color: var(--accent-color);
            color: var(--text-color);
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 50px; /* Pillow shape for cartoon feel */
            border: 5px solid #222; /* Cartoon outline */
            transition: all 0.2s ease;
            cursor: pointer;
        }

        .cta-button:hover {
            transform: scale(1.05); /* Make it jump a little on hover */
            box-shadow: 5px 5px 0px rgba(0,0,0,0.1);
        }

    </style>
</head>
<body>

    <header class="hero">
        <div class="container">
            <img src="logo.png" alt="Addy Power Wash Logo">
            <h1>Addy Power Wash</h1>
            <p>We Make Things Shine, Shine, Shine!</p>
        </div>
    </header>

    <main class="container">
        <div class="panel">
            <h2>Our Super Cleaning Services</h2>
            <ul>
                <li>House Power Washing</li>
                <li>Roof and Gutter Cleaning</li>
                <li>Deck and Fence Restoration</li>
                <li>Window Cleaning</li>
            </ul>
        </div>

        <div class="panel" style="text-align: center; background-color: white;">
            <h2>Need a Clean?</h2>
            <p>Get a free quote today! We’ll make your home look cartoon-perfect.</p>
            <a href="mailto:addy@yourdomain.com" class="cta-button">Email Addy!</a>
            </div>
    </main>

</body>
</html>
