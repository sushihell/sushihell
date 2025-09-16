<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sushihell | Game & App Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #f8f8f8;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 30px;
            background: rgba(16, 18, 27, 0.8);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff6b6b, #ffa86b, #ffda6b);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            animation: gradient 3s ease infinite;
            background-size: 200% auto;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #6bc5ff;
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 25px 0 15px;
            color: #6bc5ff;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #cccccc;
            margin-bottom: 20px;
        }
        
        .about {
            margin-bottom: 40px;
            padding: 20px;
            background: rgba(30, 30, 50, 0.3);
            border-radius: 15px;
        }
        
        .about-content {
            display: flex;
            align-items: center;
            gap: 20px;
        }
        
        .about-text {
            flex: 1;
        }
        
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #6bc5ff;
        }
        
        .skills {
            margin-bottom: 40px;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .skill-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            background: rgba(40, 40, 70, 0.5);
            padding: 15px 10px;
            border-radius: 10px;
            transition: transform 0.3s, background 0.3s;
        }
        
        .skill-item:hover {
            transform: translateY(-5px);
            background: rgba(59, 130, 246, 0.3);
        }
        
        .skill-icon {
            font-size: 2rem;
            margin-bottom: 8px;
        }
        
        .stats {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            margin-bottom: 40px;
        }
        
        .stat-card {
            flex: 1;
            background: rgba(30, 30, 50, 0.3);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: #6bc5ff;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-link {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: rgba(40, 40, 70, 0.5);
            color: #6bc5ff;
            border-radius: 50%;
            font-size: 1.5rem;
            transition: all 0.3s;
            text-decoration: none;
        }
        
        .social-link:hover {
            transform: translateY(-5px);
            background: #6bc5ff;
            color: #0f0c29;
        }
        
        .contact {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: linear-gradient(90deg, #6bc5ff, #6b83ff);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s;
            margin-top: 15px;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(107, 197, 255, 0.4);
        }
        
        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        @media (max-width: 768px) {
            .stats {
                flex-direction: column;
            }
            
            .about-content {
                flex-direction: column;
                text-align: center;
            }
            
            h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Sushihell</h1>
            <p class="tagline">Game & App Developer | Bangladesh</p>
        </header>
        
        <section class="about">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>🎮 Passionate game and application developer with experience in creating interactive and engaging digital experiences.</p>
                    <p>🌱 Currently expanding my skills in <strong>C++</strong> to enhance my development capabilities.</p>
                    <p>🕹️ Experienced in <strong>Unity</strong> game development and <strong>Android</strong> application development.</p>
                    <p>💡 Always learning new technologies and methodologies to improve my craft.</p>
                </div>
                <img src="https://avatars.githubusercontent.com/u/158055791?v=4" alt="Sushihell" class="profile-img">
            </div>
        </section>
        
        <section class="skills">
            <h2>Skills & Technologies</h2>
            <div class="skills-grid">
                <div class="skill-item">
                    <i class="fab fa-cuttlefish skill-icon"></i>
                    <span>C++</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-unity skill-icon"></i>
                    <span>Unity</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-android skill-icon"></i>
                    <span>Android</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-java skill-icon"></i>
                    <span>Java</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-js skill-icon"></i>
                    <span>JavaScript</span>
                </div>
                <div class="skill-item">
                    <i class="fas fa-database skill-icon"></i>
                    <span>MySQL</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-docker skill-icon"></i>
                    <span>Docker</span>
                </div>
                <div class="skill-item">
                    <i class="fas fa-server skill-icon"></i>
                    <span>Nginx</span>
                </div>
            </div>
        </section>
        
        <section class="stats">
            <div class="stat-card">
                <div class="stat-number">10+</div>
                <div class="stat-label">Projects</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">5+</div>
                <div class="stat-label">Technologies</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">2+</div>
                <div class="stat-label">Years Experience</div>
            </div>
        </section>
        
        <div class="social-links">
            <a href="#" class="social-link">
                <i class="fab fa-github"></i>
            </a>
            <a href="#" class="social-link">
                <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="#" class="social-link">
                <i class="fab fa-twitter"></i>
            </a>
            <a href="#" class="social-link">
                <i class="fab fa-discord"></i>
            </a>
        </div>
        
        <section class="contact">
            <h2>Get In Touch</h2>
            <p>Feel free to reach out for collaborations or just to say hello!</p>
            <a href="mailto:monowarhossain.mail@gmail.com" class="btn">Contact Me</a>
        </section>
    </div>
    
    <script>
        // Simple animation for stats
        document.addEventListener('DOMContentLoaded', function() {
            const statNumbers = document.querySelectorAll('.stat-number');
            
            statNumbers.forEach(stat => {
                const target = parseInt(stat.textContent);
                let current = 0;
                const increment = target / 50;
                
                const updateNumber = () => {
                    if (current < target) {
                        current += increment;
                        stat.textContent = Math.round(current) + '+';
                        setTimeout(updateNumber, 30);
                    } else {
                        stat.textContent = target + '+';
                    }
                };
                
                updateNumber();
            });
        });
    </script>
</body>
</html>
