<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://hovertree.com/texiao/html5/index/hovertreewelcome.css" type="text/css" rel="stylesheet" />
    <style>
        body {
            background-color: black;
            color: white;
        }

        .header {
            position: relative;
            display: flex;
            gap: 40vw;
        }

        .logo {
            position: relative;
        }

        .logo img {
            width: 10vw;
        }

        .nav {
            position: relative;
            list-style: none;
            display: flex;
            width: 100%;
            justify-content: space-around;
            align-items: center;
        }

        .nav li {
            position: relative;
            font-size: 1.5vw;
        }

        .nav li a {
            color: white;
            text-decoration: none;
            background: linear-gradient(to right, #08FDD8, #9C8CB9, rgb(171, 255, 194), rgb(63, 121, 224), #E6F2FF, white);
            background-size: 500% 100%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: flow 5s linear infinite;
            border: 5px solid transparent;
            -webkit-box-decoration-break: clone;
            box-decoration-break: clone;
        }

        @keyframes flow {
            0% {
                background-position: 0 0;
            }

            100% {
                background-position: 100% 0;
            }
        }

        .nav li :hover {
            color: wheat;
        }

        .first {
            position: relative;
            display: flex;
            justify-content: space-around;
            margin: 5vw 0;
        }

        .intro {
            position: relative;
            font-size: 2vw;
            font-family: Inconsolata, monospace;
            font-weight: 700;
            margin: 2vw 0;
        }

        .intro p {
            font-size: 1.7vw;
            margin: 0.3vw 0 0;
            font-family: Inconsolata, monospace;

        }

        .duction {
            position: relative;
            width: 30vw;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 1.1vw;
            margin: 1vw 0;

        }

        .duction a {
            position: relative;
            font-size: 1.2vw;
            color: #08FDD8;
            border: 1px solid #08FDD8;
            padding: 0.8vw;
            top: 2vw;
            animation: colorFlow 5s ease-in-out infinite;

        }

        .duction a:hover {
            background-color: #08FDD8;
            color: black;
        }

        @keyframes colorFlow {
            0% {
                border-color: #08FDD8;
                /* turquoise */
            }

            25% {
                border-color: #F7B32B;
                /* gold */
            }

            50% {
                border-color: #9C8CB9;
                /* lavender */
            }

            75% {
                border-color: #EF6C00;
                /* orange */
            }

            100% {
                border-color: #08FDD8;
                /* turquoise */
            }
        }
    </style>

</head>

<body>
    <div class="header">
        <div class="logo"><img src="logo.png" alt=""></div>
        <div class="nav">
            <li><a href="portfolio.html"> Portfolio</a></li>
            <li><a href=""> About</a></li>
            <li><a href=""> Blog</a></li>
            <li><a href=""> Conatact</a></li>
        </div>
    </div>
    <canvas id="canvas" style="position: absolute; left: 0; z-index: -1;"></canvas>

    <div class="first">
        <div class="intro">
            Ritik kratzel
            <p>Frontend & Backend <br>Web Developer</p>
            <div class="duction">
                "Hi, I'm Ritik, a full stack web developer specializing in building user-friendly websites and web
                applications using HTML, CSS, JavaScript, Wix, and WordPress. With expertise in front-end and back-end
                technologies like PHP, MySQL, Apache, NGINX, VPS, and Linux, I'm confident in my ability to bring your
                vision to life."
                <br>
                <a href="portfolio.html">View portfolio</a>
            </div>
        </div>
        <div class="profile">
            <img src="profile.png" alt="">
        </div>
    </div>
    <script type="text/javascript" src="https://hovertree.com/texiao/html5/index/hovertreewelcome.js">
    </script>
    <script src="java.js"></script>
</body>

</html>
