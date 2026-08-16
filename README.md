<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerald | Personal Website</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f6f8;
            color: #222;
        }

        header {
            background: #1f2937;
            color: white;
            padding: 20px 40px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        .hero {
            text-align: center;
            padding: 80px 20px;
            background: white;
        }

        .hero h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
            color: #555;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 22px;
            background: #2563eb;
            color: white;
            text-decoration: none;
            border-radius: 6px;
        }

        section {
            max-width: 900px;
            margin: auto;
            padding: 50px 20px;
        }

        .card {
            background: white;
            padding: 25px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #1f2937;
            color: white;
        }
    </style>
</head>

<body>

<header>
    <nav>
        <strong>Gerald</strong>

        <div>
            <a href="#about">About</a>
            <a href="#interests">Interests</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
</header>

<div class="hero">
    <h1>Hello, I'm Gerald</h1>

    <p>
        Welcome to my personal website.
        I am learning technology, web development, and GitHub.
    </p>

    <a class="button" href="#about">Learn More</a>
</div>

<section id="about">
    <div class="card">
        <h2>About Me</h2>

        <p>
            I enjoy learning new things, exploring technology,
            creating content, and developing ideas that can help people.
        </p>
    </div>
</section>

<section id="interests">
    <div class="card">
        <h2>My Interests</h2>

        <ul>
            <li>Technology</li>
            <li>Web Development</li>
            <li>Content Creation</li>
            <li>Personal Development</li>
            <li>Artificial Intelligence</li>
        </ul>
    </div>
</section>

<section id="contact">
    <div class="card">
        <h2>Contact Me</h2>

        <p>
            Thanks for visiting my website.
        </p>

        <a class="button" href="mailto:your-email@example.com">
            Send Me an Email
        </a>
    </div>
</section>

<footer>
    <p>© 2026 Gerald. My First GitHub Website.</p>
</footer>

</body>
</html>
