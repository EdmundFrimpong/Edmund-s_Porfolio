<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edmund Frimpong - Data Analysis Portfolio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Proxima+Nova:wght@700&display=swap');

        :root {
            --primary-color: #ff8c00;
            --secondary-color: #ffd700;
            --background-color: black;
            --text-color: white;
        }

        body {
            background-image: url('https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/878114.jpg');
            background-size: cover;
            background-position: center center;
            background-attachment: fixed;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            color: var(--text-color);
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: var(--secondary-color);
        }
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        h1 {
            font-family: 'Proxima Nova', sans-serif; 
            font-size: 48px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            color: transparent;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.6);
        }
        .headshot {
            width: 225px; 
            height: 225px; 
            border-radius: 50%; 
            margin: 20px auto;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .about,
        .project,
        .contact {
            margin-bottom: 20px;
            padding: 15px;
            background: var(--background-color);
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
            color: var(--text-color);
            transition: transform 0.3s, background 0.3s, color 0.3s;
        }
        .project {
            font-size: 20px;
            color: yellow;
        }
        .project span {
            color: red;
            animation: pulse 2s infinite;
        }
        .about:hover,
        .project:hover {
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            color: black;
            transform: scale(1.05);
        }
        .contact a {
            color: blue;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 10px 0;
            transition: transform 0.3s, color 0.3s;
        }
        .contact a:hover {
            transform: scale(1.05);
            color: red;
        }
        section {
            margin: 40px 0;
        }
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
            .headshot {
                width: 150px;
                height: 150px;
            }
            h1 {
                font-size: 36px;
            }
        }
    </style>
    <meta name="description" content="Data Analysis Portfolio of Edmund Frimpong showcasing projects and skills in SQL, Excel, and Power BI.">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <h1>My Data Analysis Portfolio</h1>
        <img src="https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/IMG_20250219_205530%20copy.png" alt="Edmund Frimpong" class="headshot">
        <section id="about" class="about">
            Operations & Risk Analyst | Google Data Analytics Certificate | Data Storytelling & Reporting | SQL, Excel & Power BI
        </section>
        <section id="projects">
            <div class="project">SQL Project - <span>Coming Soon!!!</span></div>
            <div class="project">Capstone Project - <span>Coming Soon!!!</span></div>
            <div class="project">Excel Project - <span>Coming Soon!!!</span></div>
        </section>
        <section id="contact" class="contact">
            <p>Contact Me:</p>
            <a href="mailto:edxfrimpong@gmail.com">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mail_%28iOS%29.svg" alt="Email icon"> edxfrimpong@gmail.com
            </a>
            <a href="https://www.linkedin.com/in/edmund-frimpong-b650a5141/" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn icon"> Edmund Frimpong
            </a>
        </section>
    </div>
</body>
</html>
