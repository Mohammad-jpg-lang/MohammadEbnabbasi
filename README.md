<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Portfolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS file if needed -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            float: left;
            display: block;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Name</h1>
        <p>Computer Science Enthusiast | Developer | Problem Solver</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>I am a passionate developer with a keen interest in AI, machine learning, and software development. My goal is to create innovative solutions that solve real-world problems. I love coding, learning new technologies, and collaborating with others to build impactful projects.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>AI-Powered Chatbot</strong>: A chatbot designed to help users with common queries using machine learning algorithms to improve responses over time.</li>
                <li><strong>Personal Portfolio Website</strong>: A responsive and interactive website showcasing my projects, skills, and experience.</li>
                <li><strong>Blockchain-Based Voting System</strong>: A decentralized system using blockchain to ensure secure and transparent elections.</li>
            </ul>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Programming Languages: Python, JavaScript, C++</li>
                <li>Web Development: HTML, CSS, JavaScript, React</li>
                <li>Machine Learning: TensorFlow, Keras, Scikit-learn</li>
                <li>Version Control: Git, GitHub</li>
                <li>Databases: MySQL, MongoDB</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you'd like to get in touch, feel free to reach out to me via email or LinkedIn:</p>
            <ul>
                <li>Email: your.email@example.com</li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/your-profile">your-profile</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Name. All Rights Reserved.</p>
    </footer>

</body>
</html>
