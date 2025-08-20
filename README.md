<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Krystal-Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <div class="logo">KR.</div>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>
  <section id="home" class="home-section">
    <div class="text-section"
      <div class="text-overlay">
    <h1>KRYSTAL SIEGA</h1>
    <h2>Everything Happens for a Reason.</h2>
    </div>
  </section>
</body>
</html>

*{
    margin:0;
    padding:0;
}
body{
    height: 100vh; 
    font-family: 'CMUserif', serif;
    background-image: url('camera.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    overflow-y: hidden;
}
header nav{
    display: flex;
    justify-content: space-between;
    align-items: right;
    background-color: none;
    padding: 35px 40px;
    color: black;
    gap:600px;
  }
.home-section{
    position: relative;
    min-height: 600px;
}
.home-section img{
    width: 100%;
    width: 100%;
    object-fit: cover;
}
.text-overlay{
    position: absolute;
    top: 140px;
    right: 40px;
    color: black
    z-index: 1;
    text-align: :right;
}
.text-overlay h1{
    font-size: 1em;
    font-style: 'CMU', serif;
    font-size: 70px;
    margin-botom:0.5em;
}
.text-overlay h2{
    font-size: 2em;
    font-style: 'CanvaSans', serif;
    font-size: 20px;
}
.logo{
    font-size: 16px;
    font-family: 'CMU Serif', serif;
    font-weight: bold;
    padding: 0px 40px;
    gap:97px;
    letter-spacing: 1px;
    color: black;
}
nav ul{
    list-style: none;
    display: flex;
    gap: 50px;

 }
 nav a{
    text-decoration: none;
    color: #000000;
}
Krystal Mae
