# yalsorogi.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Portfolio - Youssef Alsorogi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <img src="website/pfp.jpg" alt="pfp" class="profile-pic">
                <div class="header-text">
                    <h1>Youssef Alsorogi</h1>
                    <p>Cybersecurity Enthusiast | Web Developer | Entrepreneur</p>
                </div>
            </div>
            <nav>
                <ul>
                <li><a href="#about" class="nav-button">About Me</a></li>
                <li><a href="#skills" class="nav-button">Skills</a></li>
                <li><a href="#work" class="nav-button">Work</a></li>
                <li><a href="#education" class="nav-button">Education</a></li>
                <li><a href="#contact" class="nav-button">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
        

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I am Youssef Alsorogi, a passionate cybersecurity student at Indiana University, with experience in both Information Security internships and entrepreneurial ventures. I enjoy solving technical challenges and creating impactful digital solutions.</p>
        </div>
    </section>
    
    <section id="education">
        <div class="container">
            <h2>Education</h2>
            <div class="education-item">
                <h3>Bachelor of Science in Cyber Security and Global Policy - Indiana University</h3>
                <p>Expected Graduation: May 2026 | GPA: 3.64</p>
                <p>Relevant Coursework: Informatics, Information Infrastructure, Security Foundations, Analytical Foundations, Mathematical Foundations of Informatics.</p>
            </div>
        </div>
    </section>    
    <hr> 
    <section id="work">
        <div class="container">
            <h2>Work Experience</h2>
            
            <section id="work">
                <div class="container">
                    <!-- First Job (Cetera Financial Group) -->
                    <div class="job">
                        <div class="job-title">
                            <span class="company">Cetera Financial Group:</span><br>
                            <span class="role">Information Security Intern</span><br>
                            <span class="date">May 2024 - Aug 2024</span>
                        </div>
                        <ul>
                            <li>Analyzed 500+ security alerts per week using Splunk and identified 20+ potential threats.</li>
                            <li>Utilized NetSkope for cloud monitoring, reducing security incidents by 6%.</li>
                            <li>Conducted SOC audits to identify compliance gaps and recommend improvements.</li>
                        </ul>
                        <img src="website/cetera-image.jpg" alt="Cetera Financial Group" class="job-image">
                    </div>
            
                    <!-- Second Job (UNGRATEFUL DEAD) -->
                    <div class="job">
                        <div class="job-title">
                            <span class="company">UNGRATEFUL DEAD:</span><br>
                            <span class="role">Chief Executive Officer</span><br>
                            <span class="date">Oct 2021 - Mar 2022</span>
                        </div>
                        <ul>
                            <li>Launched a clothing brand inspired by the Grateful Dead, achieving $1,000 profit within six months.</li>
                            <li>Produced merchandise via silk-screening and leveraged social media for promotion.</li>
                            <li>Generated local buzz through word-of-mouth and grassroots marketing strategies.</li>
                        </ul>
                        <img src="website/ugd-image.jpg" alt="UNGRATEFUL DEAD" class="job-image">
                    </div>
            
                    <!-- Third Job (MESA) -->
                    <div class="job">
                        <div class="job-title">
                            <span class="company">Middle Eastern Student Association (MESA):</span><br>
                            <span class="role">Treasurer and Philanthropy Chair</span><br>
                            <span class="date">Aug 2023 - Present</span>
                        </div>
                        <ul>
                            <li>Managed club finances and ensured effective budget allocation for on-campus events.</li>
                            <li>Organized philanthropic activities and demonstrated leadership in club initiatives.</li>
                        </ul>
                        <img src="website/mesa.jpg" alt="MESA" class="job-image">
                    </div>
                </div>
            </section>
            
    <hr> 
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul class="skills-list">
                <li>Python</li>
                <li>Linux</li>
                <li>HTML/CSS</li>
                <li>MS Excel</li>
                <li>MS Acess</li>
                <li>Unity</li>
                <li>Virtual Machines</li>
            </ul>
        </div>
    </section>
    <hr> 
    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:yalsorog@iu.edu">yalsorog@iu.edu</a></p>
            <p>Phone: (502) 744-4984</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/yalsorogi" target="_blank">linkedin.com/in/yalsorogi</a></p>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <p>&copy; 2024 Youssef Alsorogi. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>


# styles sheet

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Times New Roman', Times, serif, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0.5rem 0;
}

header p {
    font-style: italic;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

nav ul li a.nav-button {
    display: inline-block;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: white;
    background-color: #677e9e; /* Bluish Gray background */
    border: none;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

nav ul li a.nav-button:hover {
    background-color: #384a74; /* Darker blue on hover */
}

nav ul li a.nav-button:active {
    background-color: #4c5a68; /* Even darker when clicked */
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

section {
    padding: 2rem 0;
    text-align: center;
}

.header-content {
    display: flex;
    align-items: center; /* Vertically center the image and text */
    justify-content: center; /* Center the content horizontally */
}

.profile-pic {
    width: 125px; /* Set the size of the image */
    height: 125px; /* Make the height equal to the width to ensure a square */
    border-radius: 50%; /* This makes the image a circle */
    object-fit: cover; /* Ensures the image covers the entire circle */
    margin-right: 20px; /* Add some space between the image and the text */
    border: 3px solid #333; /* Optional: Add a border around the circle */
}

#skills .skills-list {
    list-style: none;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

#skills .skills-list li {
    background-color: #e4e4e4;
    padding: 1rem;
    margin: 0.5rem;
    border-radius: 5px;
    width: 150px;
    text-align: center;
}

/* Style for work section */
#work {
    text-align: left; /* Ensure text is aligned to the left */
}

.job, .education-item {
    margin-bottom: 1.5rem;
}

.job {
    display: flex;
    justify-content: space-between; /* Space the content and image apart */
    align-items: center; /* Vertically align the text and image */
    margin-bottom: 20px; /* Add spacing between job entries */
}

/* Style for the job description */
.job ul {
    list-style-type: none; /* Remove default bullets */
}

.job ul li {
    position: relative;
    padding-left: 20px;
}

.job ul li:before {
    content: "◆"; /* Unicode character for a diamond */
    position: absolute;
    left: 0;
    color: #333;
    font-size: 14px;
}

/* Style the images */
.job-image {
    width: 150px; /* Set width of the image */
    height: auto; /* Keep the aspect ratio */
    margin-left: 20px; /* Add some space between the text and the image */
    border-radius: 8px; /* Optional: Add rounded corners */
}

/* Job Title and Description Styles */
.job-title {
    font-family: 'Times New Roman', Times, serif, sans-serif;
    margin-bottom: 14px;
}

.company {
    font-weight: bold;
    font-size: 18px; /* Larger font size for company */
}

.role {
    font-size: 16px; /* Slightly smaller font for role */
    font-style: italic; /* Italicized job title (optional) */
    display: block; /* Ensures each role starts on a new line */
}

.date {
    font-size: 14px; /* Smaller font for the date */
    color: #666; /* Lighter color for the date (optional) */
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
    width: 100%; /* Ensures the footer stretches across the page */
}

.footer-content {
    width: 80%; /* Keep the content constrained to the same width as the rest of the page */
    margin: 0 auto; /* Center the content within the full-width footer */
}




