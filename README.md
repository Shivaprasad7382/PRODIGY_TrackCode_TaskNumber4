# PRODIGY_TrackCode_TaskNumber4
Portfolio website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Name - Web Developer</title>
</head>

<body>

    <header>
        <div class="container">

            <h1>ShivaPrasad</h1>
            <p>Web Developer</p>
        </div>
    </header>

    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <p>HTML | CSS | JavaScript | React | Node.js</p>
        </div>
    </section>

    <section id="about-me">
        <div class="container">
            <h2>About Me</h2>
            <p>
                Hello! I'm shivaprasad ,I'm passionate web developer with a strong background in building
                responsive and user-friendly websites. I graduated with a degree in Computer
                Science and have X years of professional experience in the Industry.
            </p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>I have developed a portofolio site.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>I had developed a stop watch using html css </p>
            </div>
            <!-- Add more projects as needed -->
        </div>
    </section>

    <footer>
        <div class="container">
            <p>Contact me at: shivaprasad@gmail.com</p>
            <!-- Add links to your social media profiles if desired -->
        </div>
    </footer>

</body>

</html>
//css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}

header img {
    border-radius: 50%;
    max-width: 150px;
}

section {
    margin: 2rem 0;
}

h2 {
    color: #333;
}

project {
    margin-bottom: 1rem;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
