<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="stylesheet.css">
</head>

<body>

<header class="header">
    <a href="#" class="logo">Portfolio</a>
    <nav class="navbar">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Skill</a> <!-- Fixed: missing closing tag -->
        <a href="#">Portfolio</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="home">
    <div class="home-content">
        <h3>Hello, It's Me</h3>
        <h1>Havindu Hemal</h1> <!-- Fixed: incorrect closing tag 'hi' to 'h1' -->
        <h3>And I'm a</h3>
        <p>I'm a web Designer with extensive experience for over 3 years.<br> Expertise is to create and design websites, Frontend design, and more.</p> <!-- Fixed: added missing closing tags and text -->
        <div class="home-sci">
            <!-- Social media icons or other elements can be added here -->
        </div>
    </div>
</section>

</body>

</html>
header {
    padding: 20px 10%;
    background: transparent;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.logo {
    position: relative;
    font-size: 25px;
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}

.navbar a {
    display: inline-block;
    font-size: 25px;
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    margin-left: 35px;
    transition: 0.3s;
}

.navbar a:hover {
    color: #efefef; /* Fixed the color value */
}

.home {
    position: relative;
    width: 100%;
    justify-content: space-between;
    height: 100vh;
    background: url('Purple Illustrated Mountain/Desktop Wallpaper.png') no-repeat; /* Fixed the URL path */
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 70px 10% 0;
}
