# Maurevive
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maurevive - NGO for a Better Mauritius</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <div class="logo">Maurevive</div>
        <nav>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#pillars">Our Five Pillars</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="home">
        <h1>Welcome to Maurevive</h1>
        <p>Join us in making Mauritius a cleaner, more inclusive, and sustainable place for everyone.</p>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>
            Founded by Rishabh Jaunky, Reezvi Pydiah, and Enzo, Maurevive focuses on solving environmental and social challenges.
        </p>
    </section>

    <section id="pillars" class="pillars">
        <h2>Our Five Pillars</h2>
        <ul>
            <li>Environmental Clean-Ups</li>
            <li>Homeless Assistance</li>
            <li>Sanitary Support</li>
            <li>Youth Inclusivity</li>
            <li>Marine Conservation</li>
        </ul>
    </section>

    <section id="projects" class="projects">
        <h2>Our Projects</h2>
        <p>Discover our latest initiatives, like the Mega Clean-Up Day and feeding programs.</p>
    </section>

    <section id="blog" class="blog">
        <h2>Blog</h2>
        <p>Explore stories, tips, and updates on our activities in Mauritius.</p>
    </section>

    <footer class="footer">
        <p>Designed with care for Mauritius | Maurevive NGO</p>
    </footer>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f8f5;
    color: #333;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

.nav-links li a:hover {
    text-decoration: underline;
}

.home, .about, .pillars, .projects, .blog {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 10px 0;
}
