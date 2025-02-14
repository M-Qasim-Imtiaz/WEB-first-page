# WEB-first-page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anti-Terrorism Agency</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header */
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }

        header .logo h1 {
            font-size: 1.5rem;
        }

        header nav ul {
            list-style: none;
            display: flex;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        header nav ul li a:hover {
            color: #ff6347; /* Tomato color for hover effect */
        }

        /* Hero Section */
        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            color: #fff;
            padding: 4rem 2rem;
            text-align: center;
            position: relative;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, rgba(255, 99, 71, 0.7), rgba(255, 69, 0, 0.7), rgba(255, 0, 0, 0.7));
            z-index: 1;
        }

        .hero-content {
            position: relative;
            z-index: 2;
        }

        .hero-content h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #fff; /* Ensure text is white and clear */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Add shadow for better readability */
        }

        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
            color: #fff; /* Ensure text is white and clear */
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5); /* Add shadow for better readability */
        }

        .hero-content .btn {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            background: #ff6347;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .hero-content .btn:hover {
            background: #e5533d;
        }

        /* Mission Section */
        .mission {
            padding: 2rem;
            text-align: center;
            background: #fff;
        }

        .mission h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .mission p {
            font-size: 1.1rem;
            max-width: 800px;
            margin: 0 auto;
        }

        /* Services Section */
        .services {
            padding: 2rem;
            background: #f4f4f4;
            text-align: center;
        }

        .services h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
        }

        .service-list {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .service {
            background: #fff;
            padding: 1.5rem;
            margin: 1rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 30%;
        }

        .service h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .service p {
            font-size: 1rem;
        }

        /* Footer */
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        footer p {
            margin: 0.5rem 0;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>Anti-Terrorism Agency</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Report Threat</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h2>Protecting Our Nation from Terrorism</h2>
            <p>We are committed to ensuring the safety and security of our citizens through intelligence, prevention, and rapid response.</p>
            <a href="#" class="btn">Report Suspicious Activity</a>
        </div>
    </section>

    <!-- Mission Section -->
    <section class="mission">
        <h2>Our Mission</h2>
        <p>To combat terrorism through collaboration, innovation, and unwavering dedication to protecting lives and preserving peace.</p>
    </section>

    <!-- Services Section -->
    <section class="services">
        <h2>Our Services</h2>
        <div class="service-list">
            <div class="service">
                <h3>Intelligence Gathering</h3>
                <p>We collect and analyze data to identify and prevent potential threats.</p>
            </div>
            <div class="service">
                <h3>Counter-Terrorism Operations</h3>
                <p>Our teams are trained to respond swiftly and effectively to terrorist activities.</p>
            </div>
            <div class="service">
                <h3>Public Awareness</h3>
                <p>We educate the public on recognizing and reporting suspicious behavior.</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 Anti-Terrorism Agency. All rights reserved.</p>
        <p>Contact us: info@antiterrorismagency.com | Hotline: 123-456-7890</p>
    </footer>
</body>
</html>
