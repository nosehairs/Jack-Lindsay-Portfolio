<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luke Hamm | Resume & Projects</title>
    <style>
        /* Centering the resume and LinkedIn container */
        .resume-linkedin-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin: 20px auto;
        }

        /* Styling for the resume box */
        .resume-box {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100px;
            width: 150px;
            border: 2px solid #ddd;
            border-radius: 8px;
            background-color: #f4f4f4;
            transition: background-color 0.3s ease, color 0.3s ease;
            text-align: center;
            cursor: pointer;
        }

        /* Resume box hover effect */
        .resume-box:hover {
            background-color: #007BFF;
            color: #fff;
        }

        /* Styling for the text inside the resume box */
        .resume-box a {
            text-decoration: none;
            color: inherit;
            font-size: 24px;
            font-weight: bold;
        }

        /* Styling for the LinkedIn logo */
        .linkedin-logo {
            width: 50px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        /* Hover effect for LinkedIn logo */
        .linkedin-logo:hover {
            transform: scale(1.1);
        }

        /* Project card styling */
        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin: 15px 0;
            background-color: #f4f4f4;
            transition: transform 0.3s ease, background-color 0.3s ease;
            position: relative;
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
        }

        /* On hover, the background color changes, and the project card "moves" slightly */
        .project-card:hover {
            background-color: #333;
            transform: translateY(-10px);
            cursor: pointer;
        }

        /* Styling for the project content inside the card */
        .project-card a {
            text-decoration: none;
            color: inherit;
        }

        .project-card:hover .project-content h3,
        .project-card:hover .project-content p {
            color: #fff;
        }

        /* Download icon positioning and styling */
        .download-icon {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 30px;
            height: 30px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .download-icon:hover {
            transform: scale(1.1);
        }

        /* Center the skills section heading */
        #about h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        /* Styling for the skills boxes */
        .skills-container {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .skill-box {
            border: 2px solid #ddd;
            border-radius: 8px;
            padding: 10px 20px;
            background-color: #f4f4f4;
            font-size: 18px;
            font-weight: bold;
            text-align: center;
            width: 100px;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        /* Hover effect for the skill boxes */
        .skill-box:hover {
            background-color: #007BFF;
            color: white;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <!-- Resume and LinkedIn Section -->
    <section id="resume-linkedin">
        <div class="resume-linkedin-container">
            <!-- Resume box -->
            <a href="https://github.com/nosehairs/Jack-Lindsay-Portfolio/blob/main/rume.pdf" target="_blank">
                <div class="resume-box">
                    Resume
                </div>
            </a>

            <!-- LinkedIn logo -->
            <a href="https://www.linkedin.com/in/luke-hamm-93ab3527b" target="_blank">
                <img src="path/to/LinkedIn-logo.png" alt="LinkedIn" class="linkedin-logo">
            </a>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>

        <div class="project-card">
            <a href="https://github.com/nosehairs/Jack-Lindsay-Portfolio/blob/main/Sportcomm-project.pdf" target="_blank">
                <div class="project-content">
                    <h3>Sports Communication Project</h3>
                    <p>Explored various sports communication strategies including public relations, social media, and fan engagement. This project analyzes case studies and the impact of communication efforts on brand awareness and fan loyalty in sports teams.</p>
                </div>
            </a>
            <a href="https://github.com/yourgithubprofile/SportsCommProject.Rmd" download class="download-icon">
                <img src="path/to/R-logo.jpg" alt="Download R Code">
            </a>
        </div>

        <div class="project-card">
            <a href="path/to/Hackathon.pdf" target="_blank">
                <div class="project-content">
                    <h3>Reds Hackathon</h3>
                    <p>Collaborative advanced data analysis working with large data sets of MLB statistics. Used predictive modeling to estimate which pitchers would be better suited in a new role.</p>
                </div>
            </a>
            <a href="https://github.com/yourgithubprofile/RedsHackathon.Rmd" download class="download-icon">
                <img src="path/to/R-logo.jpg" alt="Download R Code">
            </a>
        </div>

        <div class="project-card">
            <a href="path/to/Unit_1_Project.pdf" target="_blank">
                <div class="project-content">
                    <h3>Fantasy Football Player Value</h3>
                    <p>Developed an analytical tool using historical NFL data to assess fantasy football player performance, tracking week-by-week trends to determine how long a player must consistently over- or under-perform to justify reassessing their value. The analysis leverages statistical methods to offer insights for decision-making in player trades, adds, or drops.</p>
                </div>
            </a>
            <a href="https://github.com/yourgithubprofile/fantasyplayervaluecode.ipynb" download class="download-icon">
                <img src="path/to/Python-logo.jpg" alt="Download Python Code">
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>Skills</h2>
        <div class="skills-container">
            <div class="skill-box">R</div>
            <div class="skill-box">Python</div>
            <div class="skill-box">Excel</div>
        </div>
    </section>
</body>
</html>
