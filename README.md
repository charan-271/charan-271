<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Charan's Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }
        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 30px;
            margin-bottom: 20px;
        }
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #0366d6;
        }
        h3 {
            font-size: 1.5rem;
            font-weight: 400;
            color: #6c757d;
            margin-top: 0;
        }
        .profile-section {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 30px;
        }
        .stats-card {
            flex: 1;
            min-width: 300px;
            transition: transform 0.3s ease;
        }
        .stats-card:hover {
            transform: translateY(-5px);
        }
        .section-title {
            font-size: 1.5rem;
            padding-bottom: 10px;
            border-bottom: 2px solid #0366d6;
            margin-bottom: 20px;
            color: #0366d6;
        }
        .social-links {
            display: flex;
            gap: 15px;
            margin-bottom: 30px;
            justify-content: center;
        }
        .social-links a {
            transition: transform 0.3s ease;
        }
        .social-links a:hover {
            transform: translateY(-3px);
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        .skill-item {
            text-align: center;
            transition: transform 0.3s ease;
        }
        .skill-item:hover {
            transform: translateY(-5px);
        }
        .skill-item img {
            max-width: 40px;
            max-height: 40px;
            margin-bottom: 5px;
        }
        .skill-item span {
            font-size: 0.8rem;
            color: #6c757d;
            display: block;
        }
        .skill-category {
            margin-bottom: 30px;
        }
        @media (max-width: 768px) {
            .skills-grid {
                grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="container header">
        <h1>Hi there, I'm Charan 👋</h1>
        <h3>Full-stack developer & embedded systems enthusiast, crafting digital experiences & hardware solutions</h3>
        <div class="social-links">
            <a href="https://twitter.com/charan_271" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30" width="40"/></a>
            <a href="https://linkedin.com/in/charan271" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40"/></a>
            <a href="https://instagram.com/_charan._____" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40"/></a>
        </div>
        <p>
            <img src="https://komarev.com/ghpvc/?username=charan-271&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
            <a href="https://twitter.com/charan_271" target="_blank"><img src="https://img.shields.io/twitter/follow/charan_271?logo=twitter&style=for-the-badge" alt="Twitter Follow" /></a>
        </p>
    </div>

    <div class="container">
        <h2 class="section-title">Skills & Technologies</h2>
        
        <div class="skill-category">
            <h4>Frontend</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" />
                    <span>HTML5</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" />
                    <span>CSS3</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" />
                    <span>JavaScript</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" />
                    <span>React</span>
                </div>
                <div class="skill-item">
                    <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js" />
                    <span>Next.js</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" />
                    <span>Tailwind</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" />
                    <span>Bootstrap</span>
                </div>
            </div>
        </div>
        
        <div class="skill-category">
            <h4>Backend & Databases</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" />
                    <span>Node.js</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" />
                    <span>Express</span>
                </div>
                <div class="skill-item">
                    <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="Django" />
                    <span>Django</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" />
                    <span>MongoDB</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" />
                    <span>MySQL</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" />
                    <span>PostgreSQL</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" />
                    <span>Firebase</span>
                </div>
            </div>
        </div>
        
        <div class="skill-category">
            <h4>Languages & Tools</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" />
                    <span>Python</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" />
                    <span>C</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" />
                    <span>C++</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" />
                    <span>Java</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" />
                    <span>Git</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" />
                    <span>Linux</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" />
                    <span>AWS</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" alt="Docker" />
                    <span>Docker</span>
                </div>
            </div>
        </div>
        
        <div class="skill-category">
            <h4>Hardware Design & Embedded Systems</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/autodesk.svg" alt="Fusion 360" />
                    <span>Fusion 360</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/kicad.svg" alt="KiCad" />
                    <span>KiCad</span>
                </div>
                <div class="skill-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/materialui/materialui-original.svg" alt="3D Printing" />
                    <span>3D Printing</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/arduino/arduino-original.svg" alt="Arduino" />
                    <span>Arduino</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/espressif.svg" alt="ESP" />
                    <span>ESP</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/stmicroelectronics.svg" alt="STM32" />
                    <span>STM32</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/raspberrypi/raspberrypi-original.svg" alt="Raspberry Pi" />
                    <span>Raspberry Pi</span>
                </div>
            </div>
        </div>
        
        <div class="skill-category">
            <h4>IoT & Automation</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/eclipsemosquitto.svg" alt="MQTT" />
                    <span>MQTT</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/platformio.svg" alt="PlatformIO" />
                    <span>PlatformIO</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/nodered.svg" alt="Node-RED" />
                    <span>Node-RED</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/homeassistant.svg" alt="Home Assistant" />
                    <span>Home Assistant</span>
                </div>
                <div class="skill-item">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 32 32">
                        <path fill="#26B7FB" d="M24.093 12.297L17.757 6L5 6.006v19.988h19.093V12.297zm-11.093 9.703H8v-10h5v10zm8 0h-5v-10h5v10z"/>
                    </svg>
                    <span>Blynk</span>
                </div>
                <div class="skill-item">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 32 32">
                        <path fill="#326DE6" d="M16 5a8 8 0 0 0-7.8 6.287a6.61 6.61 0 1 0 0 9.426A8 8 0 1 0 16 5zm0 12a4 4 0 1 1 4-4a4.005 4.005 0 0 1-4 4z"/>
                    </svg>
                    <span>Matter</span>
                </div>
            </div>
        </div>

        <div class="skill-category">
            <h4>Data Science & AI</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="Pandas" />
                    <span>Pandas</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" />
                    <span>TensorFlow</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch" />
                    <span>PyTorch</span>
                </div>
                <div class="skill-item">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" />
                    <span>Scikit-learn</span>
                </div>
                <div class="skill-item">
                    <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" />
                    <span>Seaborn</span>
                </div>
            </div>
        </div>
        
        <div class="skill-category">
            <h4>Design Tools</h4>
            <div class="skills-grid">
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" />
                    <span>Figma</span>
                </div>
                <div class="skill-item">
                    <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="Illustrator" />
                    <span>Illustrator</span>
                </div>
                <div class="skill-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="Photoshop" />
                    <span>Photoshop</span>
                </div>
                <div class="skill-item">
                    <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="Blender" />
                    <span>Blender</span>
                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <div class="profile-section">
            <div class="stats-card">
                <img width="100%" src="https://github-readme-stats.vercel.app/api/top-langs?username=charan-271&show_icons=true&locale=en&layout=compact&theme=tokyonight" alt="Most Used Languages" />
            </div>
            <div class="stats-card">
                <img width="100%" src="https://github-readme-stats.vercel.app/api?username=charan-271&show_icons=true&locale=en&theme=tokyonight" alt="GitHub Stats" />
            </div>
        </div>
        <div class="stats-card">
            <img width="100%" src="https://github-readme-streak-stats.herokuapp.com/?user=charan-271&theme=tokyonight" alt="GitHub Streak" />
        </div>
    </div>
</body>
</html>
