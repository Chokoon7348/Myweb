<?php
// Configuration
$site_title = "Your Name - Personal Portfolio";
$name = "Your Name";
$tagline = "Web Developer & Creative Problem Solver";
$about = "I'm a passionate developer who loves creating amazing web experiences. With expertise in modern web technologies, I help bring ideas to life through clean, efficient code.";

$skills = [
    "PHP & Laravel",
    "JavaScript & React",
    "HTML5 & CSS3",
    "MySQL & Database Design",
    "Git & Version Control",
    "Responsive Design"
];

$projects = [
    [
        "title" => "E-commerce Platform",
        "description" => "Full-stack PHP application with payment integration",
        "tech" => "PHP, MySQL, Bootstrap"
    ],
    [
        "title" => "Task Management App",
        "description" => "Collaborative project management tool",
        "tech" => "Laravel, Vue.js, API"
    ],
    [
        "title" => "Portfolio Website",
        "description" => "Responsive personal website with CMS",
        "tech" => "PHP, CSS3, JavaScript"
    ]
];

$contact = [
    "email" => "your.email@example.com",
    "phone" => "+66 XX XXX XXXX",
    "location" => "Thailand",
    "github" => "github.com/yourusername",
    "linkedin" => "linkedin.com/in/yourprofile"
];
?>
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><?php echo $site_title; ?></title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .hero {
            text-align: center;
            padding: 60px 0;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero .tagline {
            font-size: 1.5rem;
            color: #666;
            margin-bottom: 30px;
        }

        .section {
            margin-bottom: 50px;
        }

        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: #333;
            border-bottom: 3px solid #667eea;
            padding-bottom: 10px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .skill-item {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            font-weight: bold;
            transition: transform 0.3s ease;
        }

        .skill-item:hover {
            transform: scale(1.05);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }

        .project-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-10px);
        }

        .project-card h3 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        .project-card .tech {
            background: #f8f9fa;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            color: #666;
            margin-top: 15px;
            display: inline-block;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .contact-item {
            background: white;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .contact-item:hover {
            transform: translateY(-5px);
        }

        .contact-item strong {
            color: #667eea;
            display: block;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        .btn {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 25px;
            font-size: 1.1rem;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: transform 0.3s ease;
        }

        .btn:hover {
            transform: scale(1.05);
        }

        .nav {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            padding: 15px 0;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
        }

        .nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        .nav a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav a:hover {
            color: #667eea;
        }

        body {
            padding-top: 80px;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }

            .hero .tagline {
                font-size: 1.2rem;
            }

            .section h2 {
                font-size: 2rem;
            }

            .card {
                padding: 25px;
            }

            .nav ul {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <nav class="nav">
        <ul>
            <li><a href="#home">หน้าแรก</a></li>
            <li><a href="#about">เกี่ยวกับ</a></li>
            <li><a href="#skills">ทักษะ</a></li>
            <li><a href="#projects">ผลงาน</a></li>
            <li><a href="#contact">ติดต่อ</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="home" class="hero">
            <h1><?php echo $name; ?></h1>
            <p class="tagline"><?php echo $tagline; ?></p>
            <a href="#contact" class="btn">ติดต่อเรา</a>
        </section>

        <section id="about" class="card">
            <div class="section">
                <h2>เกี่ยวกับเรา</h2>
                <p style="font-size: 1.2rem; line-height: 1.8; text-align: center;">
                    <?php echo $about; ?>
                </p>
            </div>
        </section>

        <section id="skills" class="card">
            <div class="section">
                <h2>ทักษะ</h2>
                <div class="skills-grid">
                    <?php foreach ($skills as $skill): ?>
                        <div class="skill-item">
                            <?php echo $skill; ?>
                        </div>
                    <?php endforeach; ?>
                </div>
            </div>
        </section>

        <section id="projects" class="card">
            <div class="section">
                <h2>ผลงาน</h2>
                <div class="projects-grid">
                    <?php foreach ($projects as $project): ?>
                        <div class="project-card">
                            <h3><?php echo $project['title']; ?></h3>
                            <p><?php echo $project['description']; ?></p>
                            <span class="tech"><?php echo $project['tech']; ?></span>
                        </div>
                    <?php endforeach; ?>
                </div>
            </div>
        </section>

        <section id="contact" class="card">
            <div class="section">
                <h2>ติดต่อเรา</h2>
                <div class="contact-grid">
                    <div class="contact-item">
                        <strong>อีเมล</strong>
                        <?php echo $contact['email']; ?>
                    </div>
                    <div class="contact-item">
                        <strong>โทรศัพท์</strong>
                        <?php echo $contact['phone']; ?>
                    </div>
                    <div class="contact-item">
                        <strong>ที่อยู่</strong>
                        <?php echo $contact['location']; ?>
                    </div>
                    <div class="contact-item">
                        <strong>GitHub</strong>
                        <?php echo $contact['github']; ?>
                    </div>
                    <div class="contact-item">
                        <strong>LinkedIn</strong>
                        <?php echo $contact['linkedin']; ?>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('.nav');
            if (window.scrollY > 50) {
                nav.style.background = 'rgba(255, 255, 255, 0.95)';
            } else {
                nav.style.background = 'rgba(255, 255, 255, 0.9)';
            }
        });
    </script>
</body>
</html>
