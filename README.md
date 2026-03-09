# web-sekolah
tugas web sekolah
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple School Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            display: inline-block;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        h2 {
            color: #4CAF50;
        }
    </style>
</head>
<body>

<header>
    <h1>Green Valley School</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
</nav>

<main>
    <section id="home">
        <h2>Welcome to Green Valley School</h2>
        <p>We provide quality education for students to grow and succeed in life.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Green Valley School has been shaping young minds since 1995. Our mission is to foster a safe and inspiring learning environment.</p>
    </section>

    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>Mathematics</li>
            <li>Science</li>
            <li>English</li>
            <li>Art & Music</li>
            <li>Physical Education</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@greenvalleyschool.edu</p>
        <p>Phone: +123 456 7890</p>
    </section>
</main>

<footer>
    &copy; 2026 Green Valley School. All Rights Reserved.
</footer>

</body>
</html>
