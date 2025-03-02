<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dark Theme Portfolio</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1e1e1e;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 50px;
            max-width: 800px;
            margin: auto;
        }
        section {
            margin-bottom: 40px;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }
        .button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>Dark Theme Portfolio</header>
    <nav>
        <a href="#about">Home</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am a passionate learner and developer with experience in web development, data science, and software engineering.</p>
        </section>
        
        <section id="education">
            <h2>Education</h2>
            <ul>
                <li>Master's in Mathematics and Computing - IIT (ISM) Dhanbad</li>
                <li>Bachelor's in Advanced Mathematics - Royal University of Phnom Penh</li>
            </ul>
        </section>
        
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Programming: C++, Python, JavaScript</li>
                <li>Web Development: HTML, CSS, React, Node.js</li>
                <li>Data Science: Machine Learning, Deep Learning, Statistics</li>
                <li>Mathematics: Functional Analysis, Linear Algebra, Probability Theory</li>
            </ul>
        </section>
        
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li>Matrix Exponential for ODEs</li>
                <li>Numerical Integration in C++</li>
                <li>Galois Theory and Field Extensions</li>
                <li>Deep Learning Applications in Computer Vision</li>
            </ul>
        </section>
        
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: example@domain.com</p>
            <p>LinkedIn: linkedin.com/in/example</p>
        </section>
        
        <button class="button" onclick="alert('Thank you for visiting!')">Click Me</button>
    </div>
</body>
</html>
