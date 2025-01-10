<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Febriandana Akbar - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #121212;
            color: #ffffff;
            line-height: 1.6;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #1f1f1f;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #f05454;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #ffffff;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #f05454;
        }

        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            background: linear-gradient(145deg, #1f1f1f, #121212);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
        }

        .hero .btn {
            margin-top: 30px;
            padding: 10px 20px;
            font-size: 1rem;
            font-weight: 700;
            color: #ffffff;
            background-color: #f05454;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .hero .btn:hover {
            background-color: #c74444;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Febriandana Akbar</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>I'm Febriandana Akbar, a modern and manly designer & developer, crafting elegant solutions with cutting-edge technology.</p>
        <button class="btn">Explore My Work</button>
    </section>
</body>
</html>
