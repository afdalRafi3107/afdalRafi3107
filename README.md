import { PacmanRenderer } from 'pacman-contribution-graph';

<h1 align="center">Hi 👋, I'm Muhammad Afdal Rafi</h1>
<h3 align="center">I am a Fullstack Web Developer focused on building web-based applications that are functional, intuitive, and scalable. I have applied my skills in various projects, utilizing a modern tech stack such as React, Next.js, Express.js, TypeScript, and Prisma. I genuinely enjoy the problem-solving process and always strive to enhance application quality through clean code implementation and database optimization. I am enthusiastic about continuously learning and adapting to new challenges and technologies. I am currently open to work for Fullstack / Frontend / Backend Developer opportunities.</h3>

;; pacman
const pr = new PacmanRenderer({
    platform: 'github',
    username: 'afdalRafi3107',
    canvas: document.getElementById('canvas'),
    outputFormat: 'canvas',
    gameTheme: 'github'
});
pr.start();
