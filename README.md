# MDAP-EX_01-Portfolio
## Date: 13-08-25

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
index.js
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jackson Raj - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container header-content">
            <img src="photo.jpg" alt="Jackson Raj" class="profile-pic">
            <h1>Jackson Raj</h1>
            <p>Full Stack Developer | MERN Stack Enthusiast</p>
        </div>
        <nav>
            <ul>
                <li><a href="#intro">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Introduction Section -->
    <section id="intro" class="section">
        <div class="container">
            <h2>Welcome</h2>
            <p>Hello! I'm Jackson Raj, a passionate Full Stack Developer specializing in the MERN stack. I enjoy creating dynamic, responsive, and user-friendly applications.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>I am a dedicated developer with hands-on experience in building scalable web applications. My expertise lies in MongoDB, Express.js, React.js, and Node.js. I thrive in collaborative environments and love solving real-world problems with technology.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <div class="container">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Employee Management System</h3>
                    <p>A MERN stack-based platform for onboarding, tracking, and managing employee lifecycle.</p>
                </div>
                <div class="project-card">
                    <h3>Portfolio Website</h3>
                    <p>A personal portfolio showcasing my skills, projects, and contact details.</p>
                </div>
                <div class="project-card">
                    <h3>E-Commerce Platform</h3>
                    <p>A full-featured e-commerce site with product listing, cart, and payment integration.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:jacksonraj0711@gmail.com">jacksonraj0711@gmail.com</a></p>
            <p>LinkedIn: <a href="#" target="_blank">LinkedIn Profile</a></p>
            <p>GitHub: <a href="#" target="_blank">GitHub Profile</a></p>
        </div>
    </section>

    <footer>
        <p>© 2025 Jackson Raj. All Rights Reserved.</p>
    </footer>

</body>
</html>

```
style.css
```
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: #ffffff;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

/* Header */
header {
    background: #1e1e1e;
    padding: 20px 0;
    text-align: center;
}

header .profile-pic {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid #00adb5;
    margin-bottom: 10px;
}

header h1 {
    margin-bottom: 5px;
    color: #00adb5;
}

header p {
    color: #cccccc;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: 15px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #00adb5;
}

/* Sections */
.section {
    padding: 50px 0;
    text-align: center;
}

.section h2 {
    margin-bottom: 20px;
    color: #00adb5;
}

.section p {
    max-width: 700px;
    margin: auto;
}

/* Projects Grid */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.project-card {
    background: #1e1e1e;
    padding: 20px;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: scale(1.05);
    background: #292929;
}

footer {
    background: #1e1e1e;
    text-align: center;
    padding: 15px 0;
    margin-top: 20px;
}

```
## OUTPUT
<img width="1919" height="862" alt="image" src="https://github.com/user-attachments/assets/d4df0b45-f917-406d-9cb8-a2a05eccc714" />

<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/23ba3399-e552-4189-b238-0329890bba2e" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
