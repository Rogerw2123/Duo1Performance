<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional baseball and softball training for athletes of all levels.">
    <title>Baseball & Softball Training</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background: #00274d;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #00509e;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x400') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
        }
        .hero h2 {
            font-size: 3em;
            margin: 0;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .card {
            background: #fff;
            margin: 15px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            width: 300px;
            text-align: left;
        }
        .card img {
            max-width: 100%;
            border-radius: 8px;
        }
        .card h3 {
            margin: 15px 0 10px;
        }
        footer {
            background: #00274d;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Baseball & Softball Training</h1>
        <p>Reach Your Full Potential with Expert Coaching</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#programs">Programs</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h2>Train Like a Pro</h2>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We specialize in helping baseball and softball players of all skill levels improve their game. With personalized training plans and state-of-the-art facilities, we ensure every athlete achieves their goals.</p>
    </section>
    <section id="programs" class="content">
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Hitting Training">
            <h3>Hitting Training</h3>
            <p>Enhance your batting technique with advanced drills and analysis.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Pitching Training">
            <h3>Pitching Training</h3>
            <p>Develop power and accuracy with our expert pitching coaches.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Fielding Training">
            <h3>Fielding Training</h3>
            <p>Master your defensive skills with personalized fielding programs.</p>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: training@baseballsoftball.com</p>
        <p>Phone: (123) 456-7890</p>
        <p>Address: 123 Training Lane, Sports City, USA</p>
    </section>
    <footer>
        <p>&copy; 2024 Baseball & Softball Training. All rights reserved.</p>
    </footer>
</body>
</html>
