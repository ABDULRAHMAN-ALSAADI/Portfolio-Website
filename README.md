# 🌐 Personal Portfolio Website

This is my personal portfolio website built to showcase my background, skills, and projects as a Mechatronics Engineering student and aspiring Robotics Engineer.


### 🌐 About This Portfolio Website
Built using HTML, CSS, and JavaScript

Learned and followed tutorials from W3Schools and YouTube

Used AI tools like ChatGPT, Google AI, and Cloud AI to:

Help write and improve code

Solve bugs and issues I faced during development

Suggest better writing and structure for the content

Still learning web design — not a professional yet, but improving!

This project is a part of my self-learning journey to grow as a Mechatronics Engineer and showcase my work online


### 💻 What I Did in This Project
I designed and built a personal portfolio website from scratch

Used HTML to structure the content (sections like About Me, Projects, Contact)

Styled the website using CSS to make it look clean and simple "I used alot of Ai Here (:" 

Added some basic JavaScript to make the site more interactive

Followed W3Schools guides and YouTube video tutorials to learn and implement key features

Used AI tools (like ChatGPT, Google AI, and Cloud AI) to:

Fix coding errors and bugs I didn’t understand

Improve my HTML/CSS/JS code structure

Get content ideas and help write descriptions

Practiced problem-solving and learned how to search and apply solutions

The design is still basic — I'm still improving, but this is my first solid step toward becoming better at web development


<img width="1920" height="1080" alt="WEB 1" src="https://github.com/user-attachments/assets/22d8ca84-4066-40db-8e61-bf823ec47bbf" />


<img width="1920" height="1080" alt="WEB 2" src="https://github.com/user-attachments/assets/041720ee-b541-475c-9359-208d319a5396" />



```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- --------- UNICONS ---------- -->
    <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">
    <!-- --------- CSS ---------- -->
    <link rel="stylesheet" href="E:\MY VS CODE\HTML&CSS&JAVASCRIPT\TASK 1 SMARMETHOD\style.css">
    <title>Portfolio | ALSAADI</title>
</head>
<body>
   <div class="container">
    <!-- --------------- HEADER --------------- -->
      <nav id="header">
        <div class="nav-logo">
            <p class="nav-name">AA</p>
            <span>.</span>
        </div>
        <div class="nav-menu" id="myNavMenu">
            <ul class="nav_menu_list">
                <li class="nav_list">
                    <a href="#home" class="nav-link active-link">Home</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#about" class="nav-link">About</a>
                    <div class="circle"></div>
                </li>
               
            </ul>
        </div>
        <div class="nav-button">
            <button class="btn">Download CV <i class="uil uil-file-alt"></i></button>
        </div>
        <div class="nav-menu-btn">
            <i class="uil uil-bars" onclick="myMenuFunction()"></i>
        </div>
      </nav>
    <!-- -------------- MAIN ---------------- -->
    <main class="wrapper">
       <!-- -------------- FEATURED BOX ---------------- -->
       <section class="featured-box" id="home">
          <div class="featured-text">
            <div class="featured-text-card">
                <span>ABDULRAHMAN ALSAADI</span>
            </div>
            <div class="featured-name">
                <p>I'm a Robotic Eng. </span></p>
            </div>
            <div class="featured-text-info">
                <p>A Mechatronic Student at Karabuk uni in my 3rd year doing some project now 
                </p>
            </div>
            <div class="social_icons">
                <div class="icon"><i class="uil uil-linkedin-alt"></i></div>
                <div class="icon"><i class="uil uil-github-alt"></i></div>
            </div>
          </div>
          <div class="featured-image">
            <div class="image">
                <img src="E:\MY VS CODE\HTML&CSS&JAVASCRIPT\TASK 1 SMARMETHOD\ROBOT.jpg" alt="avatar">
            </div>
          </div>
       </section>
       <!-- -------------- ABOUT BOX ---------------- -->
       <section class="section" id="about">
          <div class="top-header">
            <h1>About Me</h1>
          </div>
          <div class="row">
            <div class="col">
                <div class="about-info">
                    <h3>My introduction</h3>
                    <p>I’m a dedicated 3rd-year Mechatronics Engineering student with a strong focus on robotics design, 
                        control systems, and embedded programming. I thrive on combining mechanical structures with electronics 
                        and software to build intelligent, practical robots—from AGVs to robotic arms. Constantly honing my skills 
                        through hands-on projects and simulations, I’m driven to create innovative solutions that make a real impact in automation and robotic systems.
                    </p>
                </div>
            </div>
            <div class="col">
                <div class="skills-box">
                    <div class="skills-header">
                        <h3>SKILLS</h3>
                    </div>
                    <div class="skills-list">
                        <span>HTML</span>
                        <span>CSS</span>
                        <span>Bootstrap 5</span>
                        <span>JavaScript</span>
                        <span>C++</span>
                        <span>SOLIDWORKS</span>
                        <span>ARDUINO</span>
                    </div>
                </div>
            </div>
          </div>
       </section>

       <!-- --------------- FOOTER --------------- -->
    <footer>
        <div class="top-footer">
            <p>Abdulrahman Alsaadi .</p>
        </div>
        <div class="bottom-footer">
            <p>Copyright &copy; <a href="#home" style="text-decoration: none;">A.A</a> - All rights reserved</p>
        </div>
    </footer>
    </div>
    <!-- ----- TYPING JS Link ----- -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
       <!-- ----- SCROLL REVEAL JS Link----- -->
    <script src="https://unpkg.com/scrollreveal"></script>
    <!-- ----- MAIN JS ----- -->
    <script src="E:\MY VS CODE\HTML&CSS&JAVASCRIPT\TASK 1 SMARMETHOD\script.js"></script>
</body>
</html>
```





