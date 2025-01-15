<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhaya Bikram Shahi - Portfolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" />
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: #f7f7f7;
            color: #333;
        }
        .header, .skills, .contact {
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
            background: #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .header h1 {
            text-align: center;
            font-size: 36px;
            color: #4C51BF;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .skill {
            flex: 1 1 30%;
            text-align: center;
            padding: 20px;
            background: #f0f0f0;
            border-radius: 10px;
        }
        .skills img {
            width: 50px;
            height: 50px;
        }
        .contact {
            text-align: center;
            background: #4C51BF;
            color: #fff;
            border-radius: 8px;
        }
        .contact a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header" data-aos="fade-up">
        <h1>Hi 👋, I'm Abhaya Bikram Shahi</h1>
        <h3>A passionate frontend developer from Nepal.</h3>
        <p>Currently learning <strong>React JS</strong> and looking to collaborate on <strong>Clothing Store Website</strong></p>
    </div>

    <!-- Skills Section -->
    <div class="skills" data-aos="fade-up">
        <div class="skill" data-aos="flip-left">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5"/>
            <p>HTML</p>
        </div>
        <div class="skill" data-aos="flip-left">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3"/>
            <p>CSS</p>
        </div>
        <div class="skill" data-aos="flip-left">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript"/>
            <p>JavaScript</p>
        </div>
        <div class="skill" data-aos="flip-left">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React"/>
            <p>React</p>
        </div>
    </div>

    <!-- Contact Section -->
    <div class="contact" data-aos="zoom-in">
        <h3>Connect with me:</h3>
        <p>
            <a href="https://linkedin.com/in/abhaya-bikram-shahi">LinkedIn</a> |
            <a href="https://twitter.com/abhaya_dev">Twitter</a> |
            <a href="https://github.com/developer-abhaya">GitHub</a>
        </p>
    </div>

    <!-- Script to Initialize AOS (Animate on Scroll) -->
    <script>
        AOS.init({
            duration: 1000,
            easing: 'ease-in-out',
            delay: 300
        });
    </script>

</body>
</html>
