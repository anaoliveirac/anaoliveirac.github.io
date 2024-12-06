<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ana Paula de Oliveira Costa - CV</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <div class="photo">
                <img src="photo.jpg" alt="Your Photo">
            </div>
            <h1>Ana Paula de Oliveira Costa</h1>
            <p>
                <a href="mailto:anapauladeoliveirac@gmail.com">anapauladeoliveirac@gmail.com</a> |
                <a href="https://orcid.org/0000-0002-3511-9971" target="_blank">ORCID</a> |
                <a href="https://github.com/anaoliveirac" target="_blank">GitHub</a> |
                <a href="https://www.linkedin.com/in/ana-paula-de-oliveira-costa/" target="_blank">LinkedIn</a> <br>
                Phone: +351 93 489 5921 | Porto, Portugal
            </p>
        </header>

        <section>
            <h2>Profile Summary</h2>
            <p>
                Data Scientist and AI Developer with a Ph.D. in Mechanical Engineering and a focus on machine learning 
                applications in material science and computational modeling. Extensive expertise in applying AI and ML 
                techniques to optimize material properties and processes...
            </p>
        </section>

        <section>
            <h2>Professional Experience</h2>
            <div class="job">
                <h3>Research Fellow | Ph.D Candidate</h3>
                <p>Faculty of Engineering, University of Porto, Portugal | Oct 2021 – Present</p>
                <ul>
                    <li>Developed ML models to predict steel properties from compositional data...</li>
                    <li>Implemented deep learning frameworks...</li>
                </ul>
            </div>
            <div class="job">
                <h3>Assistant Professor</h3>
                <p>Faculty of Engineering, University of Porto, Portugal | Sep 2023 – Aug 2024</p>
                <ul>
                    <li>Delivered undergraduate courses in Mathematics and Physics...</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>Education</h2>
            <p><strong>Ph.D. in Mechanical Engineering</strong>, University of Porto, Portugal | 2021 – Present</p>
            <p><strong>M.Sc. in Computational Mechanics</strong>, University of Porto, Portugal | 2018 – 2020</p>
            <p><strong>B.Sc. in Mechanical Engineering</strong>, Pontifical Catholic University of Minas Gerais, Brazil | 2012 – 2017</p>
        </section>

        <section>
            <h2>Technical Skills</h2>
            <ul>
                <li><strong>Programming Languages:</strong> Python, SQL, C/C++, MATLAB</li>
                <li><strong>Machine Learning and AI:</strong> NLP, Predictive Modeling, Computer Vision...</li>
            </ul>
        </section>

        <section>
            <h2>Certifications</h2>
            <ul>
                <li>Machine Learning Specialization, University of Porto (2021)</li>
                <li>Data Science Professional Certificate, IBM/Coursera (2024)</li>
            </ul>
        </section>

        <footer>
            <p>&copy; 2024 Ana Paula de Oliveira Costa</p>
        </footer>
    </div>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

.container {
    width: 90%;
    max-width: 800px;
    margin: 20px auto;
    background: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

header {
    text-align: center;
    margin-bottom: 20px;
}

header .photo img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
}

a {
    color: #0066cc;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

section {
    margin-bottom: 20px;
}

section h2 {
    border-bottom: 2px solid #0066cc;
    margin-bottom: 10px;
    padding-bottom: 5px;
}

.job {
    margin-bottom: 15px;
}

.job h3 {
    margin: 5px 0;
    color: #0066cc;
}

footer {
    text-align: center;
    font-size: 0.9em;
    color: #666;
    margin-top: 20px;
}
