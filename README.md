<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jack Lindsay | Resume & Projects</title>
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

        /* Adjusting the size of the skill boxes and reducing font size for cleaner look */
        .skill-box {
            border: 2px solid #ddd;
            border-radius: 8px;
            padding: 10px 20px;
            background-color: #f4f4f4;
            font-size: 16px;
            font-weight: bold;
            text-align: center;
            width: 150px;  /* Increased width to fit text */
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
            <a href="https://www.linkedin.com/in/jack-lindsay-357547298" target="_blank">
                <img src="/mnt/data/Color-of-the-LinkedIn-Logo.jpg" alt="LinkedIn" class="linkedin-logo">
            </a>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>

        <!-- Sports Comm Project restored -->
        <div class="project-card">
            <a href="https://github.com/nosehairs/Jack-Lindsay-Portfolio/blob/main/Sportcomm-project.pdf" target="_blank">
                <div class="project-content">
                    <h3>Sports Communication Project</h3>
                    <p>A comprehensive analysis of communication strategies used in sports, focusing on media relations, community engagement, and fan experience enhancement. This project emphasizes the impact of digital media in modern sports marketing.</p>
                </div>
            </a>
        </div>

        <div class="project-card">
            <a href="https://bosoxinjection.com/posts/new-red-sox-acquisition-lucas-giolito-might-be-andrew-bailey-next-miracle-01hk6mz8pzkd" target="_blank">
                <div class="project-content">
                    <h3>New Red Sox Acquisition Lucas Giolito Might Be Andrew Bailey's Next Miracle</h3>
                    <p>Analyzed the potential impact of Lucas Giolito’s acquisition by the Boston Red Sox and how pitching coach Andrew Bailey might play a key role in revitalizing his performance.</p>
                </div>
            </a>
        </div>

        <div class="project-card">
            <a href="https://bosoxinjection.com/posts/red-sox-are-falling-behind-again-as-boring-offseason-foreshadows-disappointing-2024-01hh57x8sbca" target="_blank">
                <div class="project-content">
                    <h3>Red Sox Falling Behind Again as Boring Offseason Foreshadows Disappointing 2024</h3>
                    <p>Provided insight into the Red Sox’s offseason moves, discussing how their quiet strategy might result in a lackluster 2024 season.</p>
                </div>
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>Skills</h2>
        <div class="skills-container">
            <div class="skill-box">Public Speaking</div>
            <div class="skill-box">Critical Thinking</div>
            <div class="skill-box">Microsoft Word</div>
        </div>
    </section>
</body>
</html>
