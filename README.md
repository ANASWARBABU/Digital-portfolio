# Digital-portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #5a5163;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            overflow: hidden;
        }

        header {
            background: rgba(254, 254, 253, 0.6);
            color: #020202;
            text-align: center;
            padding-top: 30px;
            cursor: pointer;
        }

        .profile-image {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }

        .name {
            margin: 10px 0;
            font-size: 36px;
        }

        .domain {
            font-size: 18px;
        }

        .section-content {
            display: none;
            padding: 20px 0;
        }

        .section-heading {
            background-color: rgba(254, 254, 253, 0.6);
            color: #040404;
            padding: 10px;
            cursor: pointer;
        }

        .section-heading:hover {
            background-color: #bab5f6;
        }
    </style>
</head>

<body>
    <div class="container">
        <header id="heading">
            <img src="senthil.jpg" alt="Profile Image" class="profile-image">
            <h1 class="name">ANASWAR BABU</h1>
            <p class="domain">Web Developer</p>
        </header>

        <div class="section-heading" id="education-heading">Education</div>
        <div class="section-content" id="education-content">
            <ul>
                <li><b>Bachelor's Degree in Computer Science - Snmv College Of Arts and Science, 2023</b></li>
                <li><b>School- T.V shekaran matric hr sec school, 2021</b></li>
            </ul>
        </div>

        <div class="section-heading" id="resume-heading">Resume</div>
        <div class="section-content" id="resume-content">
            <a href="ANASWAR BABU RESUME.docx" target="_blank">View Resume</a>
        </div>

        <div class="section-heading" id="project-heading">Projects</div>
        <div class="section-content" id="project-content">
            <div>
                <h3><a href="https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-900/">AI 900</a></h3>
                <p> </p>
            </div>
            <div>
                <h3><a href="https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-102/">AI 102</a></h3>
                <p>I successfully completed my AI 102 project in ICT academy</p>
            </div>
        </div>
    </div>

    <script>
        // Get section headings and contents
        const educationHeading = document.getElementById("education-heading");
        const resumeHeading = document.getElementById("resume-heading");
        const projectHeading = document.getElementById("project-heading");
        const educationContent = document.getElementById("education-content");
        const resumeContent = document.getElementById("resume-content");
        const projectContent = document.getElementById("project-content");

        // Toggle content visibility when clicking the headings
        educationHeading.addEventListener("click", () => {
            educationContent.style.display = educationContent.style.display === "none" ? "block" : "none";
        });

        resumeHeading.addEventListener("click", () => {
            resumeContent.style.display = resumeContent.style.display === "none" ? "block" : "none";
        });

        projectHeading.addEventListener("click", () => {
            projectContent.style.display = projectContent.style.display === "none" ? "block" : "none";
        });
    </script>
     <footer style="background-color: rgba(254, 254, 253, 0.6); color: #0e0e0e; text-align: center; padding: 10px;">
        &copy; 2023 Anaswar babu
    </footer>
</body>

</html>
