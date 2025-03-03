# Aditya-portfolio-
Life is awesome 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya - CS Student & Tech Enthusiast</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #27ae60;
            --light: #ecf0f1;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            line-height: 1.6;
            color: var(--primary);
        }

        .navbar {
            background: var(--primary);
            padding: 1rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
        }

        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('/storage/emulated/0/Pictures/Instagram/ak.jpg') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding-top: 60px;
        }

        section {
            padding: 4rem 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 1rem 0;
        }

        .timeline {
            border-left: 3px solid var(--secondary);
            padding-left: 2rem;
            margin: 2rem 0;
        }

        .event {
            position: relative;
            margin-bottom: 2rem;
            padding-left: 1rem;
        }

        .event::before {
            content: '';
            position: absolute;
            left: -2.35rem;
            top: 0;
            width: 20px;
            height: 20px;
            background: var(--secondary);
            border-radius: 50%;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 2rem;
        }

        @media (max-width: 768px) {
            .navbar {
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#aspirations">Aspirations</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <div class="container">
            <h1>Aditya 👨💻</h1>
            <p>Computer Science Student | Climate Advocate | Tech Mentor</p>
            <p>From the mountains of Nepal to the world of technology</p>
        </div>
    </section>

    <section id="about" class="container">
        <div class="card">
            <h2>About Me 🇳🇵</h2>
            <div class="skills-grid">
                <div>
                    <h3>Interests & Passions</h3>
                    <ul>
                        <li>🌳 Nature Conservation</li>
                        <li>💻 Self-Taught Programmer</li>
                        <li>📚 Chinese Novel Enthusiast</li>
                        <li>🏀 Basketball Player (3rd Place State)</li>
                    </ul>
                </div>
                <div>
                    <h3>Personal Journey</h3>
                    <p>Overcame a serious bike accident in grade 11 that required months of recovery, emerging with renewed determination to pursue tech education.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="education" class="container">
        <div class="card">
            <h2>Education & Teaching</h2>
            <div class="timeline">
                <div class="event">
                    <h3>Computer Science Instructor</h3>
                    <p>Kashi Vidya Niketan, Bihar (Grade 9 Students)</p>
                    <p>Developed curriculum focusing on basic programming and digital literacy</p>
                </div>
                <div class="event">
                    <h3>Self-Taught Developer</h3>
                    <p>Mastered multiple programming languages through online resources and experimentation</p>
                </div>
            </div>
        </div>
    </section>

    <section id="aspirations" class="container">
        <div class="card">
            <h2>Future Goals 🚀</h2>
            <div class="skills-grid">
                <div>
                    <h3>Academic</h3>
                    <ul>
                        <li>BS in Computer Science (USA)</li>
                        <li>AI/ML Research Focus</li>
                        <li>Cybersecurity Specialization</li>
                    </ul>
                </div>
                <div>
                    <h3>Professional</h3>
                    <ul>
                        <li>Healthcare Technology Innovation</li>
                        <li>Nepal Tech Ecosystem Development</li>
                        <li>Student Mentorship Programs</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact">
        <div class="container">
            <h3>Connect With Me</h3>
            <p>📧 Email: adityakarna820@gmail.com</p>
            <p>🌐 Social Media: twitter</p>
            <p>📍 From Nepal to the World</p>
        </div>
    </footer>
</body>
</html>
