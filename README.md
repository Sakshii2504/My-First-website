# My-First-website
My first website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harmony Music</title>
<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f4f4;
}
header{
    background:#111;
    color:white;
    text-align:center;
    padding:40px;
}
nav{
    background:#333;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}
section{
    padding:30px;
}
.card{
    background:white;
    padding:20px;
    margin:15px 0;
    border-radius:10px;
    box-shadow:0 2px 5px rgba(0,0,0,0.2);
}
footer{
    background:#111;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>
<body>

<header>
    <h1>Harmony Music Company</h1>
    <p>Creating Sounds That Inspire</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#artists">Artists</a>
    <a href="#albums">Albums</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <div class="card">
        <h2>About Us</h2>
        <p>Harmony Music is a creative music company dedicated to discovering talented artists and producing quality music.</p>
    </div>
</section>

<section id="artists">
    <div class="card">
        <h2>Our Artists</h2>
        <ul>
            <li>Arjun Beats</li>
            <li>Melody Queen</li>
            <li>Rhythm Band</li>
        </ul>
    </div>
</section>

<section id="albums">
    <div class="card">
        <h2>Popular Albums</h2>
        <ul>
            <li>Dream Sounds</li>
            <li>Night Vibes</li>
            <li>Musical Journey</li>
        </ul>
    </div>
</section>

<section id="contact">
    <div class="card">
        <h2>Contact Us</h2>
        <p>Email: info@harmonymusic.com</p>
        <p>Phone: +91 9876543210</p>
    </div>
</section>

<footer>
    <p>© 2026 Harmony Music Company. All Rights Reserved.</p>
</footer>

</body>
</html>
