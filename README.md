<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>James Rivera</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./CSS/style.css">
</head>
<body>
    <nav class="main-nav">
        <p>
            <a href="./contact.html">James Rivera</a>
        </p>
    </nav>

    <section class="intro-section">
        <h1 data-hover="太龙">James Rivera</h1>
        <h2 data-hover="我是乔治亚大学的计算机科学学生">I'm a computer science student at the University of Georgia.</h2>
    </section>

    <section class="about-section">
        
        <div class="centered-text">
        <div class="header-background">
        <h2 data-hover="你好，欢迎来到我的网站">Hello, I'm James</h2>
        </div>
         <p>
            In my free time, I love to workout at Ramsey and read. The current book I am reading is "Call Sign Chaos" by General James Mattis.
        </p>
        </div>
        <hr>
        <section class="about2">
            <h2 data-hover="关于">About</h2>
            <div class="three-col">
                <!-- Language Card -->
                <div class="card">
                    <img src="./images/keyboard.png" alt="Languages Image" class="tilt-image">
                    <h3>Languages</h3>
                    <ul>
                        <li>Java</li>
                        <li>Python</li>
                        <li>C</li>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>Swift</li>
                    </ul>
                </div>
        
                <!-- Leadership and Experience Card -->
                <div class="card">
                    <img src="./images/notebook.png" alt="expierence Image">
                    <h3>Leadership and Experience</h3>
                    <dl>
                        <dt>May 2022 - August 2022</dt>
                        <dd>Rhino, Software Engineering Intern</dd>
                        <br>
                        <dt>May 2023 - August 2023</dt>
                        <dd><a href="https://3vi.us">3Vi, Inc.</a>, Software Engineering Intern</dd>
                    </dl>
                </div>
        
                <!-- Skills Card -->
                
                <div class="card">
                   <img src="./images/skills.png" alt="skills image">
                    <h3>Skills</h3>
                    <dl>
                        <dt>Chinese</dt> <dd>⭐️</dd>
                        <dt>Team Collaborating</dt> <dd>⭐️⭐️⭐️⭐️</dd>
                        <dt>Public Speaking</dt> <dd>⭐️⭐️</dd>
                        <dt>Listening</dt> <dd>⭐️⭐️⭐️⭐️⭐️</dd>
                    </dl>
                </div>
            </div>
        </section>
        

    <footer class="main-footer">
        &#169; <a href="./contact.html">James Rivera</a>
    </footer>

    <script>
        document.querySelectorAll('h1, h2').forEach(element => {
            const originalText = element.textContent;
            const hoverText = element.getAttribute('data-hover');

            element.addEventListener('mouseenter', function() {
                this.textContent = hoverText;
            });

            element.addEventListener('mouseleave', function() {
                this.textContent = originalText;
            });
        });
    </script>
</body>
</html>
