<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');

        :root {
            --bg-color: #121212;
            --text-color: #ffffff;
            --secondary-text-color: #a0a0a0;
            --icon-color: #a0a0a0;
            --border-color: #333333;
            --card-bg: #1e1e1e;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .section {
            background-color: var(--card-bg);
            padding: 24px;
            border-radius: 12px;
            border: 1px solid var(--border-color);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h1, h2, h3 {
            font-weight: 700;
            margin-top: 0;
        }

        h1 {
            font-size: 2.5em;
            color: var(--text-color);
        }

        h2 {
            font-size: 1.5em;
            color: var(--secondary-text-color);
            margin-bottom: 20px;
        }

        h3 {
            font-size: 1.2em;
            color: var(--secondary-text-color);
            margin-bottom: 10px;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            align-items: center;
        }

        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 8px;
            font-weight: 700;
            font-size: 0.9em;
            text-align: center;
            min-width: 60px;
        }

        .tech-icon img {
            width: 40px;
            height: 40px;
            filter: grayscale(100%) brightness(1.5) contrast(0.5); /* Makes icons look grey */
            transition: filter 0.3s ease;
        }

        .tech-icon img:hover {
            filter: none; /* Colorize on hover for a subtle effect */
        }
        
        .tech-label {
            color: var(--text-color);
        }

        .about p {
            font-size: 1em;
            color: var(--secondary-text-color);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="section about">
            <h1>Hi, I'm [Your Name] 👋</h1>
            <h2>Full Stack Developer & AI Enthusiast</h2>
            <p>I'm passionate about building robust **RAG pipelines**, developing intelligent **AI agents**, and crafting modern **full-stack web applications**. I focus on creating clean, scalable, and efficient solutions.</p>
        </div>

        <div class="section">
            <h3>Tech I Work With</h3>
            <div class="tech-stack">
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" alt="TypeScript">
                    </span>
                    <span class="tech-label">TypeScript</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" alt="JavaScript">
                    </span>
                    <span class="tech-label">JavaScript</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
                    </span>
                    <span class="tech-label">React</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js">
                    </span>
                    <span class="tech-label">Next.js</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-plain.svg" alt="Node.js">
                    </span>
                    <span class="tech-label">Node.js</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express">
                    </span>
                    <span class="tech-label">Express</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-plain.svg" alt="PostgreSQL">
                    </span>
                    <span class="tech-label">Postgres</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB">
                    </span>
                    <span class="tech-label">MongoDB</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" alt="Tailwind CSS">
                    </span>
                    <span class="tech-label">Tailwind</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
                    </span>
                    <span class="tech-label">C++</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
                    </span>
                    <span class="tech-label">Java</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" style="filter: grayscale(100%)">
                    </span>
                    <span class="tech-label">LangChain</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=zustand&logoColor=white" alt="Zustand" style="filter: grayscale(100%)">
                    </span>
                    <span class="tech-label">Zustand</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" style="filter: grayscale(100%)">
                    </span>
                    <span class="tech-label">Vercel</span>
                </div>
                <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://img.shields.io/badge/Socket.io-000000?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io" style="filter: grayscale(100%)">
                    </span>
                    <span class="tech-label">Socket.io</span>
                </div>
                 <div class="tech-item">
                    <span class="tech-icon">
                        <img src="https://img.shields.io/badge/TanStack-000000?style=for-the-badge&logo=tanstack&logoColor=white" alt="TanStack" style="filter: grayscale(100%)">
                    </span>
                    <span class="tech-label">TanStack</span>
                </div>
            </div>
        </div>

        <div class="section">
            <h3>Find me on</h3>
            <p>
                <a href="[Your LinkedIn URL]" style="color: var(--secondary-text-color); text-decoration: none; font-weight: 700; margin-right: 15px;">LinkedIn</a>
                <a href="[Your Twitter URL]" style="color: var(--secondary-text-color); text-decoration: none; font-weight: 700; margin-right: 15px;">Twitter</a>
            </p>
        </div>
    </div>
</body>
</html>
