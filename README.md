# Ex01 Portfolio
## Date: 20.05.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Harish B - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Sri Harish B</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internships">Internships</a></li>
                <li><a href="#achievements">Achievements</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <img src="harish.jpg" alt="Sri Harish B" class="profile-pic">
        <p>I am a passionate and highly motivated Information Technology student with a strong foundation in programming, web technologies, and problem-solving. I enjoy tackling new challenges and leveraging my skills in software development, web technologies, and data analysis to create impactful solutions.</p>
        <p><strong>Resume:</strong> <a href="HARISH_RESUME.pdf" target="_blank">Download Here</a></p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Saveetha Engineering College</strong></p>
        <p>B.Tech in Information Technology (2022 - 2026)</p>
        <p>CGPA: 8.0</p>
        <p><strong>H M Matriculation Higher Secondary School</strong></p>
        <p>HSC - 75.3% (2021)</p>
        <p>SSLC - 72% (2019)</p>
    </section>

    <section id="skills">
        <h2>Technical Skills</h2>
        <ul>
            <p>Web Development (HTML, CSS, JavaScript, Node.js)</p>
            <p>Programming Languages: Python, C, Java, SQL</p>
            <p>Tools & Libraries: Git, GitHub, TensorFlow</p>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project One</h3>
            <p>A brief description about your first project goes here. You can include tools used, role, and outcomes.</p>
        </div>
        <div class="project">
            <h3>Project Two</h3>
            <p>A brief description about your second project goes here. Mention any frameworks or technologies involved.</p>
        </div>
    </section>

    <section id="internships">
        <h2>Internships</h2>
        <div class="internship">
            <h3>Company Name - Role</h3>
            <p>Description of your internship experience and responsibilities.</p>
        </div>
    </section>

    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <p>🏆 Certificate of achievement or competition participation.</p>
            <p>📜 Certifications:
                <ul>
                    <p>Web Development Certification</p>
                    <p>Programming Certification</p>
                </ul>
            </p>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:harish@example.com">harish@example.com</a></p>
        <p>Phone: <a href="tel:+911234567890">+91 1234567890</a></p>
        <p><strong>GitHub:</strong> <a href="https://github.com/sriharishb " target="_blank">GitHub Profile</a></p>
        <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sri-harish-b " target="_blank">LinkedIn Profile</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Sri Harish B. All rights reserved. Reg No: 212223220110</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```
## sytle.css

```
/* General Styling */
body {
    font-family: 'Helvetica Neue', Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
    transition: background-color 0.3s, color 0.3s;
}
header {
    background-color: #1e1e2f;
    color: white;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
header h1 {
    margin: 0;
    font-size: 2.5rem;
    letter-spacing: 1px;
    font-weight: 600;
}
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 20px 0 0;
}
nav ul li {
    display: inline;
    margin: 0 15px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
    text-transform: uppercase;
    font-weight: 500;
}
nav ul li a:hover {
    color: #ff6600;
}

#darkModeToggle {
    background-color: #ff6600;
    border: none;
    border-radius: 30px;
    color: white;
    padding: 10px 20px;
    font-size: 1rem;
    font-weight: 600;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.3s;
    margin-top: 15px;
}
#darkModeToggle:hover {
    background-color: #e65c00;
    transform: scale(1.05);
}

section {
    padding: 60px 20px;
    margin: 0 auto;
    max-width: 1000px;
}

#about {
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: background-color 0.3s, color 0.3s;
}
#about .profile-pic {
    border-radius: 50%;
    width: 160px;
    height: 160px;
    object-fit: cover;
    margin-top: 20px;
}
#about h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    font-weight: 600;
    color: #333;
}
#about p {
    font-size: 1.1rem;
    color: #555;
    margin: 20px 0;
}
#about a {
    color: #1e1e2f;
    font-weight: 600;
}
#about a:hover {
    color: #ff6600;
}

#education, #skills, #projects, #internships, #achievements, #contact {
    background-color: #ffffff;
    margin-top: 30px;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    transition: background-color 0.3s, color 0.3s;
}
#education p, #skills p, #achievements p, #contact p {
    font-size: 1.1rem;
    color: #555;
    margin: 10px 0;
}

.project, .internship {
    background-color: #f9f9f9;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 6px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    transition: background-color 0.3s, color 0.3s;
}
.project h3, .internship h3 {
    font-size: 1.6rem;
    color: #333;
    margin-bottom: 10px;
    font-weight: 600;
}
.project p, .internship p {
    font-size: 1rem;
    color: #666;
}

#achievements ul {
    list-style-type: none;
    padding: 0;
}
#achievements ul p {
    margin: 10px 0;
    font-size: 1.1rem;
    color: #555;
}

#contact a {
    color: #ff6600;
    font-weight: 600;
}
#contact a:hover {
    color: #1e1e2f;
}

footer {
    background-color: #1e1e2f;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
}
footer p {
    margin: 0;
    font-size: 1rem;
}

@media screen and (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }
    nav ul li {
        display: block;
        margin: 10px 0;
    }
    nav ul li a {
        font-size: 1rem;
    }
    section {
        padding: 40px 20px;
    }
}

body.dark-mode {
    background-color: #121212;
    color: #e0e0e0;
}
body.dark-mode header {
    background-color: #0d0d0d;
}
body.dark-mode nav ul li a {
    color: #e0e0e0;
}
body.dark-mode nav ul li a:hover {
    color: #ff6600;
}
body.dark-mode section,
body.dark-mode #about,
body.dark-mode #education,
body.dark-mode #skills,
body.dark-mode #projects,
body.dark-mode #internships,
body.dark-mode #achievements,
body.dark-mode #contact {
    background-color: #1e1e1e;
    color: #e0e0e0;
}
body.dark-mode .project,
body.dark-mode .internship {
    background-color: #262626;
    color: #e0e0e0;
}
body.dark-mode #contact a {
    color: #ff6600;
}
body.dark-mode #contact a:hover {
    color: #ffcc00;
}
body.dark-mode footer {
    background-color: #0d0d0d;
    color: #e0e0e0;
}
body.dark-mode #darkModeToggle {
    background-color: #333;
    color: #ffcc00;
}
body.dark-mode #darkModeToggle:hover {
    background-color: #444;
    transform: scale(1.05);
}
```

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.

