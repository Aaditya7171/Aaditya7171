<h1 align="center">👋 Hi, I'm Aditya Tomar</h1>
<h3 align="center">🚀 AI-Fueled Full-Stack Developer | 5-Star DSA Gladiator </h3>

<div align="center">
  <a href="https://adityatomar.online" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://linkedin.com/in/adityatomar91" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://leetcode.com/aditya1919" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode">
  </a>
</div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya Tomar - AI-Fueled Full-Stack Developer</title>
    <!-- Google Fonts: Montserrat & Quicksand -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Quicksand:wght@500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 50%, #16213e 100%);
            color: #ffffff;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            min-height: 100vh;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0;
        }

        /* Striking Purple Wave Banner with Reduced Height */
        .banner {
            position: relative;
            width: 100%;
            min-height: 280px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(120deg, #24003e 0%, #8f5cdf 70%, #d9bafd 100%);
            color: #fff;
            overflow: hidden;
            box-shadow: 0 6px 36px 4px #aa49f055;
            margin: 0 auto 3rem auto;
            border-radius: 0;
        }

        .banner-content {
            position: relative;
            z-index: 2;
            text-align: center;
            padding: 1.5rem;
            padding-bottom: 8vw;
            max-width: 1200px;
            width: 100%;
            margin: 0 auto;
        }

        .banner-content h1 {
            font-family: 'Montserrat', 'Poppins', Arial, sans-serif;
            font-size: 4.2rem;
            font-weight: 700;
            margin: 0 0 0.2em 0;
            text-shadow: 0 4px 20px #6e298b88;
            letter-spacing: 2px;
            line-height: 1.1;
        }

        .banner-content h4 {
            font-family: 'Montserrat', 'Poppins', Arial, sans-serif;
            font-size: 2.4rem;
            font-weight: 700;
            margin: 0;
            text-shadow: 0 2px 18px #6e298b66;
            letter-spacing: 1.5px;
            opacity: 0.95;
        }

        .wave-group {
            position: absolute;
            left: 0;
            bottom: 0;
            width: 100%;
            height: 35%;
            z-index: 1;
            pointer-events: none;
            overflow: hidden;
        }

        /* Custom Purple Themed Social Buttons with Reduced White */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 3rem 0;
            flex-wrap: wrap;
            padding: 0 20px;
        }

        .custom-button {
            position: relative;
            padding: 15px 30px;
            background: linear-gradient(45deg, #9d4edd, #c77dff, #d1b3ff);
            border: none;
            border-radius: 50px;
            color: #ffffff;
            font-family: 'Montserrat', sans-serif;
            font-size: 1rem;
            font-weight: 600;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            cursor: pointer;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 8px 25px rgba(157, 78, 221, 0.4);
            animation: breathing 4s ease-in-out infinite;
            overflow: hidden;
            will-change: transform, box-shadow;
        }

        .custom-button::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, #9d4edd, #c77dff, #e0aaff, #d1b3ff, #e0aaff, #c77dff, #9d4edd);
            background-size: 400% 400%;
            border-radius: 50px;
            z-index: -1;
            animation: gradientAura 4s ease-in-out infinite;
            opacity: 0.6;
            transition: opacity 0.4s ease;
        }

        .custom-button:hover {
            transform: translateY(-8px) scale(1.05);
            box-shadow: 0 20px 40px rgba(157, 78, 221, 0.6);
            animation: breathingHover 2s ease-in-out infinite;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            background: linear-gradient(45deg, #a855f7, #c77dff, #e0aaff);
        }

        .custom-button:hover::before {
            animation: gradientAuraHover 2s ease-in-out infinite;
            opacity: 0.8;
        }

        @keyframes breathing {
            0%, 100% {
                transform: scale(1);
                box-shadow: 0 8px 25px rgba(157, 78, 221, 0.4);
            }
            50% {
                transform: scale(1.015);
                box-shadow: 0 12px 35px rgba(157, 78, 221, 0.5);
            }
        }

        @keyframes breathingHover {
            0%, 100% {
                transform: translateY(-8px) scale(1.05);
                box-shadow: 0 20px 40px rgba(157, 78, 221, 0.6);
            }
            50% {
                transform: translateY(-10px) scale(1.06);
                box-shadow: 0 25px 50px rgba(157, 78, 221, 0.7);
            }
        }

        @keyframes gradientAura {
            0%, 100% {
                background-position: 0% 50%;
                opacity: 0.6;
            }
            50% {
                background-position: 100% 50%;
                opacity: 0.7;
            }
        }

        @keyframes gradientAuraHover {
            0%, 100% {
                background-position: 0% 50%;
                opacity: 0.8;
            }
            50% {
                background-position: 100% 50%;
                opacity: 0.7;
            }
        }

        /* Section Styling with Purple Headings */
        .section {
            background: rgba(255, 255, 255, 0.05);
            border: 2px solid rgba(157, 78, 221, 0.3);
            border-radius: 20px;
            padding: 2.5rem;
            margin: 2.5rem 20px;
            backdrop-filter: blur(15px);
            box-shadow: 0 10px 40px rgba(157, 78, 221, 0.15);
            transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
        }

        .section:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 50px rgba(157, 78, 221, 0.25);
            border-color: rgba(199, 125, 255, 0.5);
        }

        .section h2 {
            color: #c77dff;
            font-size: 2.2rem;
            margin-bottom: 2rem;
            text-align: center;
            text-shadow: 0 0 15px rgba(199, 125, 255, 0.6);
            font-weight: 700;
        }

        .section h3 {
            color: #ffffff;
            font-size: 1.4rem;
            margin: 2rem 0 1.5rem 0;
            text-shadow: 0 0 8px rgba(224, 170, 255, 0.5);
            font-weight: 600;
        }

        /* Tech Stack Badges */
        .tech-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 2rem;
            justify-content: center;
        }

        .tech-grid img {
            transition: transform 0.3s ease, filter 0.3s ease, box-shadow 0.3s ease;
            border-radius: 6px;
        }

        .tech-grid img:hover {
            transform: scale(1.15) translateY(-5px);
            filter: brightness(1.1);
            box-shadow: 0 8px 25px rgba(157, 78, 221, 0.4);
        }

        /* Projects Table */
        .projects-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1.5rem;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
        }

        .projects-table th {
            background: linear-gradient(45deg, #9d4edd, #c77dff);
            color: #ffffff;
            padding: 18px;
            text-align: left;
            font-weight: 700;
            font-size: 1.1rem;
        }

        .projects-table td {
            padding: 18px;
            border-bottom: 1px solid rgba(157, 78, 221, 0.2);
            transition: background-color 0.3s ease;
            color: #ffffff;
        }

        .projects-table tr:hover td {
            background-color: rgba(157, 78, 221, 0.15);
        }

        .projects-table a {
            color: #ffffff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease, text-shadow 0.3s ease;
        }

        .projects-table a:hover {
            color: #ffffff;
            text-shadow: 0 0 8px rgba(224, 170, 255, 0.6);
        }

        /* GitHub Stats */
        .stats-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .stats-container img {
            border-radius: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 2px solid rgba(157, 78, 221, 0.3);
        }

        .stats-container img:hover {
            transform: scale(1.08);
            box-shadow: 0 15px 40px rgba(157, 78, 221, 0.4);
        }

        /* Enhanced Divider */
        .divider {
            height: 3px;
            background: linear-gradient(90deg, transparent, #9d4edd, #c77dff, #ffffff, #c77dff, #9d4edd, transparent);
            margin: 4rem 20px;
            border-radius: 2px;
            animation: dividerGlow 3s ease-in-out infinite alternate;
        }

        @keyframes dividerGlow {
            from { box-shadow: 0 0 5px rgba(157, 78, 221, 0.5); }
            to { box-shadow: 0 0 15px rgba(199, 125, 255, 0.8); }
        }

        /* Floating Particles */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .particle {
            position: absolute;
            width: 5px;
            height: 5px;
            background: radial-gradient(circle, rgba(157, 78, 221, 0.8), rgba(199, 125, 255, 0.4));
            border-radius: 50%;
            animation: float-particle 20s linear infinite;
        }

        @keyframes float-particle {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) rotate(360deg);
                opacity: 0;
            }
        }

        /* Enhanced Responsive Design */
        @media (max-width: 1024px) {
            .banner {
                margin: 0 15px 3rem 15px;
                border-radius: 20px;
                min-height: 250px;
            }

            .banner-content {
                padding: 1.5rem;
            }
        }

        @media (max-width: 768px) {
            .banner {
                min-height: 220px;
                margin: 0 10px 2.5rem 10px;
                border-radius: 15px;
            }

            .banner-content {
                padding: 1.2rem 1rem;
                padding-bottom: 10vw;
            }

            .banner-content h1 {
                font-size: 2.8rem;
            }

            .banner-content h4 {
                font-size: 1.8rem;
            }

            .custom-button {
                padding: 12px 24px;
                font-size: 0.9rem;
                transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            }

            .custom-button:hover {
                transform: translateY(-6px) scale(1.03);
                transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            }

            .social-links {
                gap: 20px;
                margin: 2.5rem 0;
            }

            .section {
                padding: 2rem;
                margin: 2rem 15px;
            }

            .section h2 {
                font-size: 1.8rem;
            }

            .projects-table {
                font-size: 0.9rem;
            }

            .projects-table th,
            .projects-table td {
                padding: 12px 10px;
            }

            .stats-container {
                flex-direction: column;
            }

            .stats-container img {
                max-width: 100%;
                height: auto;
            }
        }

        @media (max-width: 480px) {
            .banner {
                min-height: 180px;
                margin: 0 5px 2rem 5px;
                border-radius: 12px;
            }

            .banner-content {
                padding: 1rem 0.5rem;
                padding-bottom: 12vw;
            }

            .banner-content h1 {
                font-size: 2.2rem;
            }

            .banner-content h4 {
                font-size: 1.4rem;
            }

            .custom-button {
                padding: 10px 20px;
                font-size: 0.8rem;
                transition: all 0.25s ease;
            }

            .custom-button:hover {
                transform: translateY(-4px) scale(1.02);
                transition: all 0.25s ease;
            }

            .social-links {
                gap: 15px;
                flex-direction: column;
                align-items: center;
                margin: 2rem 0;
            }

            .section {
                padding: 1.5rem;
                margin: 2rem 10px;
            }

            .section h2 {
                font-size: 1.6rem;
            }

            .section h3 {
                font-size: 1.2rem;
            }

            .projects-table {
                font-size: 0.8rem;
            }
        }

        @media (max-width: 320px) {
            .banner {
                margin: 0 2px 1.5rem 2px;
                border-radius: 10px;
                min-height: 160px;
            }

            .banner-content {
                padding: 0.8rem 0.3rem;
                padding-bottom: 15vw;
            }

            .banner-content h1 {
                font-size: 1.8rem;
            }

            .banner-content h4 {
                font-size: 1.1rem;
            }

            .custom-button {
                padding: 8px 16px;
                font-size: 0.7rem;
            }
        }
    </style>
</head>
<body>
    <!-- Floating Particles -->
    <div class="particles">
        <div class="particle" style="left: 10%; animation-delay: 0s;"></div>
        <div class="particle" style="left: 20%; animation-delay: 3s;"></div>
        <div class="particle" style="left: 30%; animation-delay: 6s;"></div>
        <div class="particle" style="left: 40%; animation-delay: 9s;"></div>
        <div class="particle" style="left: 50%; animation-delay: 12s;"></div>
        <div class="particle" style="left: 60%; animation-delay: 15s;"></div>
        <div class="particle" style="left: 70%; animation-delay: 18s;"></div>
        <div class="particle" style="left: 80%; animation-delay: 21s;"></div>
        <div class="particle" style="left: 90%; animation-delay: 24s;"></div>
    </div>

    <div class="container">
        <!-- Striking Purple Wave Banner -->
        <div class="banner">
            <div class="banner-content">
                <h1>Hi👋, I'm Aditya Tomar</h1>
                <h4>Full-Stack Developer</h4>
            </div>
            <div class="wave-group">
                <svg viewBox="0 0 1440 320" preserveAspectRatio="none" style="width: 100%; height: 100%;">
                    <defs>
                        <linearGradient id="waveGradA" x1="0" y1="0" x2="1" y2="0">
                            <stop offset="0%" stop-color="#8f5cdf" />
                            <stop offset="100%" stop-color="#d9bafd" />
                        </linearGradient>
                        <linearGradient id="waveGradB" x1="0" y1="0" x2="1" y2="0">
                            <stop offset="0%" stop-color="#3d1766" />
                            <stop offset="100%" stop-color="#a96afe" />
                        </linearGradient>
                    </defs>
                    <!-- Higher, stronger behind wave -->
                    <path fill="url(#waveGradB)" fill-opacity="0.55">
                        <animate attributeName="d" dur="8s" repeatCount="indefinite"
                            values="
                                M0,180 C360,350 1080,100 1440,300 L1440,320 L0,320 Z;
                                M0,330 C480,80 960,370 1440,180 L1440,320 L0,320 Z;
                                M0,180 C360,350 1080,100 1440,300 L1440,320 L0,320 Z
                            " />
                    </path>
                    <!-- Higher, stronger front wave -->
                    <path fill="url(#waveGradA)" fill-opacity="0.85">
                        <animate attributeName="d" dur="6s" repeatCount="indefinite"
                            values="
                                M0,160 C480,60 1000,360 1440,160 L1440,320 L0,320 Z;
                                M0,310 C400,320 1100,80 1440,300 L1440,320 L0,320 Z;
                                M0,160 C480,60 1000,360 1440,160 L1440,320 L0,320 Z
                            " />
                    </path>
                </svg>
            </div>
        </div>

        <!-- Custom Purple Themed Social Buttons -->
        <div class="social-links">
            <a href="https://adityatomar.online" target="_blank" class="custom-button">
                🌐 Portfolio
            </a>
            <a href="https://linkedin.com/in/adityatomar91" target="_blank" class="custom-button">
                💼 LinkedIn
            </a>
        </div>

        <div class="divider"></div>

        <!-- Tech Stack Section -->
        <div class="section">
            <h2>🛠️ Tech Stack</h2>
            
            <h3>Programming Languages</h3>
            <div class="tech-grid">
                <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
                <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
                <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++">
            </div>

            <h3>Frontend Development</h3>
            <div class="tech-grid">
                <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
                <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
                <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap">
                <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" alt="Tailwind">
                <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
                <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white" alt="Vue.js">
                <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white" alt="jQuery">
                <img src="https://img.shields.io/badge/EJS-8A2BE2?style=flat&logo=ejs&logoColor=white" alt="EJS">
            </div>

            <h3>Backend Development</h3>
            <div class="tech-grid">
                <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js">
                <img src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white" alt="Express.js">
                <img src="https://img.shields.io/badge/REST_APIs-000000?style=flat&logo=rest&logoColor=white" alt="REST APIs">
                <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
                <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis">
                <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase">
                <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white" alt="Prisma">
            </div>

            <h3>Authentication & Security</h3>
            <div class="tech-grid">
                <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white" alt="JWT">
                <img src="https://img.shields.io/badge/Google_Auth-4285F4?style=flat&logo=google&logoColor=white" alt="Google Auth">
                <img src="https://img.shields.io/badge/bcrypt-00599C?style=flat&logo=security&logoColor=white" alt="bcrypt">
                <img src="https://img.shields.io/badge/HTTP--only_Cookies-000000?style=flat&logo=cookiecutter&logoColor=white" alt="HTTP-only Cookies">
                <img src="https://img.shields.io/badge/CORS-000000?style=flat&logo=security&logoColor=white" alt="CORS">
            </div>

            <h3>Deployment & Tools</h3>
            <div class="tech-grid">
                <img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white" alt="Netlify">
                <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel">
                <img src="https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white" alt="Render">
                <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
                <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
                <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub">
                <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white" alt="Postman">
                <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white" alt="Bash">
                <img src="https://img.shields.io/badge/Railway-0A0A0A?style=flat&logo=railway&logoColor=white" alt="Railway">
                <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" alt="Vite">
                <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white" alt="Cloudinary">
            </div>

            <h3>Libraries & Frameworks</h3>
            <div class="tech-grid">
                <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io&logoColor=white" alt="Socket.IO">
                <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=react-query&logoColor=white" alt="React Query">
                <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white" alt="Framer Motion">
                <img src="https://img.shields.io/badge/Shadcn_UI-000000?style=flat&logo=shadcn-ui&logoColor=white" alt="Shadcn UI">
                <img src="https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white" alt="Three.js">
                <img src="https://img.shields.io/badge/Recharts-00BFFF?style=flat&logo=recharts&logoColor=white" alt="Recharts">
                <img src="https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white" alt="Leaflet">
            </div>
        </div>

        <div class="divider"></div>

        <!-- Projects Section -->
        <div class="section">
            <h2>🚀 Featured Projects</h2>
            <table class="projects-table">
                <thead>
                    <tr>
                        <th>Project</th>
                        <th>Description</th>
                        <th>Tech Stack</th>
                        <th>Live Demo</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><a href="https://github.com/Aaditya7171/FootageFlow"><strong>FootageFlow</strong></a></td>
                        <td>Video management platform powered by Whisper and Gemini</td>
                        <td>React, TypeScript, Node.js, Express.js, PostgreSQL, Cloudinary, Prisma</td>
                        <td><a href="https://footage-flow-zeta.vercel.app/login">Live Demo</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://github.com/Aaditya7171/FilmFusion"><strong>FilmFusion</strong></a></td>
                        <td>Movie discovery platform with 1,000 users and 67% faster APIs</td>
                        <td>React, TypeScript, Node.js, Express.js, PostgreSQL, Redis</td>
                        <td><a href="https://filmfusion-live.netlify.app/">Live Demo</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://github.com/Aaditya7171/EcoVolt"><strong>EcoVolt</strong></a></td>
                        <td>EV charging station locator managing 50+ stations</td>
                        <td>Vue.js, Node.js, Express.js, PostgreSQL</td>
                        <td><a href="https://ecovolt-nu.vercel.app/">Live Demo</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://github.com/Aaditya7171/taskio"><strong>Taskio</strong></a></td>
                        <td>Modern todo list app with Kanban, habit tracking, and analytics</td>
                        <td>React, TypeScript, Node.js, Express.js, PostgreSQL, Tailwind CSS</td>
                        <td><a href="https://livetaskio.netlify.app/">Live Demo</a></td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="divider"></div>

        <!-- GitHub Stats Section -->
        <div class="section">
            <h2>📊 GitHub Stats</h2>
            <div class="stats-container">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aaditya7171&layout=compact&theme=vision-friendly-dark&hide=php&title_color=ffffff&text_color=ffffff&bg_color=0f0f23&border_color=9d4edd" alt="Top Languages">
                <img src="https://github-readme-stats.vercel.app/api?username=aaditya7171&show_icons=true&theme=vision-friendly-dark&include_all_commits=true&title_color=ffffff&text_color=ffffff&bg_color=0f0f23&border_color=9d4edd&icon_color=ffffff" alt="GitHub Stats">
            </div>
        </div>
    </div>
</body>
</html>

<hr>

<hr>

<h2>🛠️ Tech Stack</h2>

<h3>Programming Languages</h3>
<div style="display: flex; flex-wrap: nowrap; gap: 8px; overflow-x: auto;">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++">
</div>

<h3>Frontend Development</h3>
<div style="display: flex; flex-wrap: nowrap; gap: 8px; overflow-x: auto;">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white" alt="Vue.js">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white" alt="jQuery">
  <img src="https://img.shields.io/badge/EJS-8A2BE2?style=flat&logo=ejs&logoColor=white" alt="EJS">
</div>

<h3>Backend Development</h3>
<div style="display: flex; flex-wrap: nowrap; gap: 8px; overflow-x: auto;">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor.white" alt="Express.js">
  <img src="https://img.shields.io/badge/REST_APIs-000000?style=flat&logo=rest&logoColor=white" alt="REST APIs">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white" alt="Prisma">
</div>

<h3>Authentication & Security</h3>
<div style="display: flex; flex-wrap: nowrap; gap: 8px; overflow-x: auto;">
  <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white" alt="JWT">
  <img src="https://img.shields.io/badge/Google_Auth-4285F4?style=flat&logo=google&logoColor=white" alt="Google Auth">
  <img src="https://img.shields.io/badge/bcrypt-00599C?style=flat&logo=security&logoColor=white" alt="bcrypt">
  <img src="https://img.shields.io/badge/HTTP--only_Cookies-000000?style=flat&logo=cookiecutter&logoColor=white" alt="HTTP-only Cookies">
  <img src="https://img.shields.io/badge/CORS-000000?style=flat&logo=security&logoColor=white" alt="CORS">
</div>

<h3>Deployment & Tools</h3>
<div style="display: flex; flex-wrap: nowrap; gap: 8px; overflow-x: auto;">
  <img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white" alt="Netlify">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white" alt="Render">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white" alt="Postman">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Railway-0A0A0A?style=flat&logo=railway&logoColor=white" alt="Railway">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white" alt="Cloudinary">
</div>

<h3>Libraries & Frameworks</h3>
<div style="display: flex; flex-wrap: nowrap; gap: 8px; overflow-x: auto;">
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io&logoColor=white" alt="Socket.IO">
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=react-query&logoColor=white" alt="React Query">
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white" alt="Framer Motion">
  <img src="https://img.shields.io/badge/Shadcn_UI-000000?style=flat&logo=shadcn-ui&logoColor=white" alt="Shadcn UI">
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/Recharts-00BFFF?style=flat&logo=recharts&logoColor=white" alt="Recharts">
  <img src="https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white" alt="Leaflet">
</div>

<hr>

<h2>🚀 Featured Projects</h2>
<table>
  <tr>
    <th>Project</th>
    <th>Description</th>
    <th>Tech Stack</th>
    <th>Live Demo</th>
  </tr>
    <tr>
    <td><a href="https://github.com/Aaditya7171/FootageFlow"><strong>FootageFlow</strong></a></td>
    <td>Video management platform powered by Whisper and Gemini</td>
    <td>React, TypeScript, Node.js, Express.js, PostgreSQL, Cloudinary, Prisma</td>
    <td><a href="https://footage-flow-zeta.vercel.app/login">Live Demo</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Aaditya7171/FilmFusion"><strong>FilmFusion</strong></a></td>
    <td>Movie discovery platform with 1,000 users and 67% faster APIs</td>
    <td>React, TypeScript, Node.js, Express.js, PostgreSQL, Redis</td>
    <td><a href="https://filmfusion-live.netlify.app/">Live Demo</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Aaditya7171/EcoVolt"><strong>EcoVolt</strong></a></td>
    <td>EV charging station locator managing 50+ stations</td>
    <td>Vue.js, Node.js, Express.js, PostgreSQL</td>
    <td><a href="https://ecovolt-nu.vercel.app/">Live Demo</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Aaditya7171/taskio"><strong>Taskio</strong></a></td>
    <td>Modern todo list app with Kanban, habit tracking, and analytics</td>
    <td>React, TypeScript, Node.js, Express.js, PostgreSQL, Tailwind CSS</td>
    <td><a href="https://livetaskio.netlify.app/">Live Demo</a></td>
  </tr>
</table>

<hr>

<h2>📊 GitHub Stats</h2>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aaditya7171&layout=compact&theme=vision-friendly-dark&hide=php" alt="Top Languages">
  <br>
  <img src="https://github-readme-stats.vercel.app/api?username=aaditya7171&show_icons=true&theme=vision-friendly-dark&include_all_commits=true" alt="GitHub Stats">
</div>
