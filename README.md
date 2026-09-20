<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Nandhini | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.7;
            color: #222;
            background: #f7f8fc;
        }

        /* Navigation */
        header {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
        }

        .navbar {
            max-width: 1100px;
            margin: auto;
            padding: 18px 25px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .logo {
            font-size: 1.7rem;
            font-weight: bold;
            color: #4f46e5;
            text-decoration: none;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        .nav-links a {
            color: #222;
            text-decoration: none;
            font-weight: 600;
        }

        .nav-links a:hover {
            color: #4f46e5;
        }

        /* Hero */
        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 70px 25px;
            background: linear-gradient(135deg, #eef2ff, #ffffff);
        }

        .hero-content {
            max-width: 850px;
        }

        .greeting {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 3rem;
            line-height: 1.3;
            margin-bottom: 25px;
            color: #111827;
        }

        h1 span {
            color: #4f46e5;
        }

        .hero p {
            font-size: 1.1rem;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            border-radius: 8px;
            background: #4f46e5;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .btn:hover {
            background: #3730a3;
        }

        /* Sections */
        .section {
            max-width: 950px;
            margin: auto;
            padding: 75px 25px;
        }

        .section h2 {
            font-size: 2.2rem;
            color: #4f46e5;
            margin-bottom: 25px;
        }

        .section p {
            font-size: 1.05rem;
        }

        /* Cards */
        .skill-card,
        .project-card {
            background: white;
            margin: 20px 0;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.07);
        }

        .skill-card h3,
        .project-card h3 {
            margin-bottom: 8px;
            font-size: 1.4rem;
        }

        /* Contact */
        .contact a {
            color: #4f46e5;
            font-weight: bold;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 25px;
            background: #111827;
            color: white;
        }

        /* Mobile */
        @media (max-width: 700px) {

            .nav-links {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            h1 {
                font-size: 2rem;
            }

            .hero {
                min-height: 80vh;
            }

            .section {
                padding: 50px 20px;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <header>
        <nav class="navbar">

            <a href="#home" class="logo">
                Nandhini
            </a>

            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

        </nav>
    </header>


    <!-- Home -->
    <section id="home" class="hero">

        <div class="hero-content">

            <p class="greeting">
                Hi, I'm Nandhini 👋
            </p>

            <h1>
                Student
                <span>|</span>
                Python Learner
                <span>|</span>
                SQL
                <span>|</span>
                Data Analytics
            </h1>

            <p>
                I am a student interested in programming and data analytics.
                I am currently learning Python and SQL and developing my
                knowledge in Data Analytics.
            </p>

            <a href="#contact" class="btn">
                Contact Me
            </a>

        </div>

    </section>


    <!-- About -->
    <section id="about" class="section">

        <h2>About Me</h2>

        <p>
            I am a student with an interest in Python, SQL and Data Analytics.
            I enjoy learning new technical concepts and improving my
            programming and analytical skills. Currently, I am focusing on
            strengthening my knowledge and preparing for my upcoming project.
        </p>

    </section>


    <!-- Skills -->
    <section id="skills" class="section">

        <h2>Skills</h2>

        <div class="skill-card">

            <h3>Python</h3>

            <p>
                Learning and practicing Python programming.
            </p>

        </div>


        <div class="skill-card">

            <h3>SQL</h3>

            <p>
                Learning SQL queries and database concepts.
            </p>

        </div>


        <div class="skill-card">

            <h3>Data Analytics</h3>

            <p>
                Learning data analysis and visualization concepts.
            </p>

        </div>

    </section>


    <!-- Projects -->
    <section id="projects" class="section">

        <h2>Projects</h2>

        <div class="project-card">

            <h3>Upcoming Project</h3>

            <p>
                I am currently preparing my first project using my knowledge
                of Python, SQL and Data Analytics. Project details will be
                added soon.
            </p>

        </div>

    </section>


    <!-- Contact -->
    <section id="contact" class="section contact">

        <h2>Contact Me</h2>

        <p>
            📧
            <a href="mailto:nandhini23012007@gmail.com">
                nandhini23012007@gmail.com
            </a>
        </p>

        <p>
            🔗
            <a
                href="https://www.linkedin.com/in/nandhini-g-9870493a2/"
                target="_blank">
                LinkedIn Profile
            </a>
        </p>

    </section>


    <!-- Footer -->
    <footer>

        <p>
            © 2026 Nandhini. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
