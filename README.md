<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aakash Rathee's Portfolio</title>
    <style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: white;
            color: #00aaff;
            line-height: 1.6;
        }

        header {
            background: #000000;
            color: #fff;
            padding: 1rem 0;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header nav ul {
            list-style: none;
            display: flex;
            gap: 1rem;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 6007;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        .hero {
            background: #F0F8FF;
            color: black;
            padding:7rem 0;
            text-align: center;
        }
        span{
            color:aqua
        }

        .hero h1 {
            font-size:3rem;
            transition: color 0.3s ease-in-out;
        }

        .hero p {
            font-size: 1.6rem;
            margin-top: 1rem;
        }

        .hero img {
            border-radius: 50%;
            width: 340px;
            height: 350px;
            margin-top: 2rem;
            transition: transform 0.3s ease-in-out;
            border: 1px solid black;
            box-shadow: 0 0 20px cyan;
        }
 
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Aakash <span>Rathee</span></h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero" id="home">
        <div class="container">
            <h1>Hello, I'm Aakash Rathee</h1>
            <p>And I'm a <b>Web Developer</b></p>
            <img src="AAKASH.jpg" alt="Aakash Rathee's Photo">
        </div>
    </section>
</body>
</html>
