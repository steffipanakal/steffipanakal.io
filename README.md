<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Steffi George Panakal | Cybersecurity Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #0D1117;
            color: #C9D1D9;
        }
        header {
            background-color: #161B22;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            color: #9858ff;
            font-size: 2.5em;
            margin: 0;
            text-align: center;
        }
        .intro {
            padding: 50px;
            text-align: center;
            background-color: #161B22;
        }
        .intro p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 700px;
            margin: 0 auto;
            color: #8B949E;
        }
        
        .section-title {
            font-size: 2em;
            margin: 50px 0 20px 0;
            color: #9858ff;
            text-align: center;
        }
        .project-container {
            width: 100%;
            padding: 20px;
        }
        .project-card {
            background-color: #21262D;
            margin: 15px auto;
            padding: 20px;
            border-radius: 10px;
            width: 100%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 900px;
        }
        .project-card h3 {
            font-size: 1.8em;
            color: #a482da;
        }
        .project-card p {
            font-size: 1.1em;
            color: #8B949E;
            margin-bottom: 10px;
        }
        .project-card a {
            color: #58A6FF;
            text-decoration: none;
            font-weight: bold;
        }
        .project-card a:hover {
            text-decoration: underline;
        }
        .project-card button {
            margin-top: 10px;
            padding: 5px 10px;
            background-color: #37284f;
            border: none;
            color: #fff;
            border-radius: 5px;
            cursor: pointer;
        }
        .project-card button:hover {
            background-color: #1F6FEB;
        }
        .carousel-container {
            width: 100%;
            overflow: hidden;
            padding: 20px;
        }
        .carousel {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .card {
            background-color: #21262D;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .card h3 {
            font-size: 1.5em;
            color: #58A6FF;
        }
        .card p {
            font-size: 1em;
            color: #8B949E;
        }
        .card a {
            color: #58A6FF;
            text-decoration: none;
            font-weight: bold;
        }
        .card a:hover {
            text-decoration: underline;
        }
        .card-details {
            display: none;
            font-size: 0.9em;
            margin-top: 10px;
            color: #A8A8A8;
        }
        .card button {
            margin-top: 10px;
            padding: 5px 10px;
            background-color: #4d2987;
            border: none;
            color: #fff;
            border-radius: 5px;
            cursor: pointer;
        }
        .card button:hover {
            background-color: #561090;
        }
        .carousel-controls {
            text-align: center;
            margin-top: 20px;
        }
        .carousel-controls button {
            padding: 10px 20px;
            background-color: #561090;
            border: none;
            color: white;
            margin: 5px;
            cursor: pointer;
            border-radius: 5px;
        }
        .carousel-controls button:hover {
            background-color: #561090;
        }
        footer {
            background-color: #161B22;
            text-align: center;
            padding: 20px;
            color: #8B949E;
        }
        a {
            color: #58A6FF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .resume-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #58A6FF;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .resume-btn:hover {
            background-color: #1F6FEB;
        }
    </style>
</head>
<body>

<header>
    <h1>Steffi George Panakal</h1>
    <img style="align-items: center; width: 20%; margin: 50px 50px 50px; border-radius: 10px;" src="Screenshot 2024-09-29 214817.png" alt="">
</header>

<section class="intro">
    <h2 class="section-title">About Me</h2>
    <p>
        Currently leveling up my Cybersecurity game at the University of Maryland, I'm fresh off a year-long adventure at Cleared Europe Services where I honed my skills in Splunk, AWS, and purple teaming (think of me as the cyber equivalent of an Avengers team member!). With a solid foundation in IT and honors in Cybersecurity from K. J. Somaiya Institute, I like to mix tech savvy with a dash of hacker-chic, specializing in social and reverse engineering.
    </p>
    <a href="path_to_resume/Steffi_George_Panakal_Resume.pdf" class="resume-btn" download>Download My Resume</a>
</section>

<section class="projects">
    <h2 class="section-title">Projects</h2>
    
    <div class="project-container">

        <!-- Project 1 -->
        <div class="project-card">
            <h3 >Android Malware Detection</h3>
            <p>
                Users
interact with the system by uploading APK files for analysis, initiating the "Upload APK for Analysis"
use case. Upon receiving the APK file, the system proceeds to conduct both static and dynamic analyses,
depicted as the "Perform Static Analysis" and "Perform Dynamic Analysis" use cases, respectively.
Through static analysis, the system examines the structure and components of the APK file without
execution, while dynamic analysis involves executing the APK in a controlled environment to monitor its
behavior. Following analysis, the system generates a comprehensive report detailing the findings,
including any detected malware or suspicious activities, as part of the "Generate Analysis Report" use
case. If malicious behavior is identified, the system notifies the user accordingly, ensuring prompt action
against potential threats.
            </p>
            <a style="align-content: center;" href="https://drive.google.com/file/d/1SsDtk7QOu7KC0sl-JlkD6y9MzBx_mhZZ/view?usp=sharing" target="_blank">View Demo</a>
            <div class="card-details">
                <p>Role: Simulated attacks, analyzed vulnerabilities, and worked on countermeasures using Splunk dashboards.</p>
            </div>
        </div>
        
        <div class="project-card">
            <h3 style="margin-left: 55%;">Phishing Link Detection using ML</h3>
            <p>
                The web user surfs a URL, that URL is automatically fetched by the system and sent to the
URL Testing File. There, the URL is checked for 16 Phishing Identification Parameters. The output
for each parameter is then multiplied with its corresponding weights which are generated by the ML
model which is trained on a training dataset. Finally, the predicted outcome is sent to the browser
extension file and an alert is displayed to the user indicating whether the URL being surfed is
Phishing or not.
            </p>
            <a href="https://drive.google.com/file/d/1ZSjx1-ncqVj9uo57sgbYwj7xBUOS32qj/view?usp=sharing" target="_blank">View Demo</a>
            <div class="card-details">
                <p>Role: Created a classification model for real-time detection of phishing websites using scikit-learn.</p>
            </div>
        </div>
        </div>

        <!-- Project 2 -->
        

        <!-- Project 3 -->
        

    </div>
</section>

<p class="intro">
    At Cleared, we tackled the ever-evolving world of security head-on, like the cyber-version of "The Matrix," staying one step ahead of threats. Whether it was diving deep into feasibility reports or flexing my MITRE ATT&CK Navigator expertise (yep, I’ve got the framework down), I was all about operational excellence and innovation. I’ve even teamed up with the best to lock down account recovery like it’s Fort Knox. So, if you’re looking for someone to bring fresh ideas and a little sass to the cybersecurity table, I’m ready to roll!</p>

<section class="certifications">
    <h2 class="section-title">Certifications</h2>
    <div class="carousel-container">
        <div class="carousel">

            <!-- Certification 2 -->
            <div class="card">
                <h3>Bits and Bytes of Computer Networking</h3>
                <p>Completed: Jan 2022</p>
                <a href="https://drive.google.com/file/d/1zGQOlLY3cbvncYsz1VL3B7WoteFJfM5A/view?usp=sharing" target="_blank">View Certificate</a>
            </div>

            <!-- Certification 3 -->
            <div class="card">
                <h3>Configuration Management and the Cloud</h3>
                <p>Completed: Feb 2022</p>
                <a href="https://drive.google.com/file/d/19vuZc3SYml7UfvBxtm7-BkDGEmTxEqZ5/view?usp=sharing" target="_blank">View Certificate</a>
            </div>

            <!-- Certification 4 -->
            <div class="card">
                <h3>Git and GitHub</h3>
                <p>Completed: April 2022</p>
                <a href="https://drive.google.com/file/d/1w-5vFpe4mCH3t7XmYmm5z3CaW8CtCgc7/view?usp=sharing" target="_blank">View Certificate</a>
            </div>

            <!-- Certification 4 -->
            <div class="card">
                <h3>Using Python to Interact with the Operating
                    System</h3>
                <p>Completed: Nov 2022</p>
                <a href="https://drive.google.com/file/d/1xkQ8RljeLADNne9gIg05yjDFy9ReqjW3/view?usp=sharing" target="_blank">View Certificate</a>
            </div>
            <!-- Certification 4 -->
            <div class="card">
                <h3>AWS Academy Cloud Foundations</h3>
                <p>Completed: Sept 2023</p>
                <a href="https://drive.google.com/file/d/17-xnHKSGQ8TEJZrZ-4XYY43Nyc36jo-K/view?usp=sharing" target="_blank">View Certificate</a>
            </div>
        </div>
    </div>

    <div class="carousel-controls">
        <button onclick="moveCarousel(-1)">Previous</button>
        <button onclick="moveCarousel(1)">Next</button>
    </div>
</section>

<footer>
    <p>Find me on <a href="https://www.linkedin.com/in/steffi-george-2ba404206/" target="_blank">LinkedIn</a> | Contact me: steffigeorge222@gmail.com</p>
</footer>

<script>
