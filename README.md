<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin: 1rem 0;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            background: #007bff;
            padding: 0.5rem 1rem;
            border-radius: 5px;
        }
        nav a:hover {
            background: #0056b3;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 0 2rem;
        }
        section {
            margin: 2rem 0;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        .project {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
        }
        .project img {
            width: 100%;
            border-radius: 5px;
        }
        .project h3 {
            margin: 1rem 0 0.5rem;
        }
        footer {
            text-align: center;
            margin: 2rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tahmid Ahmed</h1>
        <p>Student | Aspiring Programmer</p>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hi! I’m Tahmid Ahmed, currently a student at the University of South Wales. I have a passion for programming and enjoy solving problems through code. My academic journey and personal projects have equipped me with a strong foundation in technology and innovation.</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li><strong>Programming Languages:</strong> C++, HTML</li>
            </ul>
        </section>

        <section id="hobbies">
            <h2>Hobbies</h2>
            <p>When I’m not coding, I love gaming, listening to music, and traveling to explore new places and cultures.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <img src="https://imgs.search.brave.com/EZadOBu3F4kX3zsOvJP44m886qZS40_zCBoVXpx83Y0/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jZG4u/cGl4YWJheS5jb20v/cGhvdG8vMjAxNi8w/My8yNy8xOC81NC90/ZWNobm9sb2d5LTEy/ODM2MjRfNjQwLmpw/Zw" alt="Project Example">
                    <h3>Programming Assessment 1</h3>
                    <ol>
                        <li>A program that calculates the monthly income of an employee including bonuses and medical allowances.</li>
                        <li>A program to convert height from feet and inches to meters.</li>
                        <li>A program to calculate new average high July temperatures after a 15% rise for three cities.</li>
                        <li>A program to determine how many paint tins are needed to cover a fence.</li>
                        <li>A program to calculate daily sales from four types of burgers sold.</li>
                        <li>A program that calculates the yearly average of percentages obtained in terminal exams.</li>
                        <li>A coin-toss simulator where users guess the outcome and win or lose based on a match.</li>
                        <li>A program that calculates the area of a triangle using the lengths of its sides.</li>
                        <li>A program displaying the total distance traveled after each hour of a given time period based on speed.</li>
                    </ol>
                </div>
                <div class="project">
                    <img src="https://imgs.search.brave.com/EZadOBu3F4kX3zsOvJP44m886qZS40_zCBoVXpx83Y0/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jZG4u/cGl4YWJheS5jb20v/cGhvdG8vMjAxNi8w/My8yNy8xOC81NC90/ZWNobm9sb2d5LTEy/ODM2MjRfNjQwLmpw/Zw" alt="Project Example">
                    <h3>Programming Assessment 2</h3>
                    <ol>
                        <li>Functions to convert tons to pounds and kilograms, generating a conversion table.</li>
                        <li>A function to calculate average velocity based on distances and times.</li>
                        <li>A Time24 class for managing time in 24-hour format.</li>
                        <li>A program to count how many students scored above 50% from an array of percentages.</li>
                        <li>A program to find and display the smallest number in an array and its index.</li>
                        <li>A program to count occurrences of a name in a predefined list.</li>
                        <li>A lottery ticket checker for weekly winning numbers.</li>
                        <li>A program to sort dynamically allocated test scores and calculate their average.</li>
                        <li>A program handling name-score pairs, sorting them, and calculating their averages.</li>
                    </ol>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out to me at <a href="mailto:tahmidahmed359@gmail.com">tahmidahmed359@gmail.com</a> for any collaborations or inquiries.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Tahmid Ahmed. All Rights Reserved.</p>
    </footer>
</body>
</html>

