# Portfolio
<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dilsha P – Front-End & Full Stack Developer</title>
<script src="https://cdn.tailwindcss.com"></script>
<style>
    body {
        font-family: 'Inter', sans-serif;
        scroll-behavior: smooth; /* smooth scrolling */
        transition: background-color 0.3s, color 0.3s;
    }
    .card {
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }
    .dark-mode {
        background-color: #1f2937;
        color: #f3f4f6;
    }
    .nav-link:hover {
        color: #7c3aed;
        transition: color 0.3s;
    }
</style>
</head>
<body class="bg-gray-50 text-gray-800 transition-colors">

<!-- Sticky Navigation -->
<header class="fixed top-0 left-0 w-full bg-white shadow z-50">
    <div class="max-w-6xl mx-auto flex justify-between items-center py-4 px-6">
        <a href="#hero" class="text-2xl font-bold text-purple-700">Dilsha P</a>
        <nav class="space-x-6">
            <a href="#about" class="nav-link text-gray-700 font-medium">About</a>
            <a href="#skills" class="nav-link text-gray-700 font-medium">Skills</a>
            <a href="#experience" class="nav-link text-gray-700 font-medium">Experience</a>
            <a href="#projects" class="nav-link text-gray-700 font-medium">Projects</a>
            <a href="#contact" class="nav-link text-gray-700 font-medium">Contact</a>
        </nav>
        <button id="darkToggle" class="bg-purple-600 text-white px-4 py-2 rounded-lg shadow">Dark Mode</button>
    </div>
</header>

<!-- Hero Section -->
<section id="hero" class="pt-24 py-20 px-6 text-center bg-gradient-to-r from-purple-700 to-indigo-600 text-white">
    <h1 class="text-4xl md:text-6xl font-bold mb-4">Dilsha P</h1>
    <p class="text-xl md:text-2xl mb-6">Front-End & Full Stack Web Developer</p>
    <p class="mb-6">Dubai, UAE ♦ <a href="tel:+971509166465" class="underline">+971 50 916 6465</a> ♦ <a href="mailto:dilshanasar11@gmail.com" class="underline">dilshanasar11@gmail.com</a></p>
    <div class="flex justify-center gap-6 mb-6">
        <a href="https://www.linkedin.com/in/dilsha-p-266456265?lip" target="_blank" class="bg-white text-purple-700 px-6 py-3 rounded-full font-semibold hover:bg-gray-200 transition">LinkedIn</a>
        <a href="https://github.com/dilsha-tech" target="_blank" class="bg-white text-purple-700 px-6 py-3 rounded-full font-semibold hover:bg-gray-200 transition">GitHub</a>
    </div>
    <a href="Dilsha_CV.pdf" download class="bg-white text-purple-700 px-6 py-3 rounded-full font-semibold hover:bg-gray-200 transition">Download Resume</a>
</section>

<!-- About Me -->
<section id="about" class="py-16 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-6">About Me</h2>
    <p class="text-gray-700 leading-relaxed">
        Front-End Web Developer with 3 years of experience building scalable, high-performance web applications. Skilled in <strong>HTML5, CSS3 (SCSS/SASS), JavaScript (ES6+), TypeScript, React.js, Redux, GraphQL, RESTful APIs, JQuery, Angular, Next.js, Node.js, MySQL, and Azure deployment</strong>. Experienced with CI/CD pipelines, AI integration, front-end optimization, and animation libraries such as Framer Motion, GSAP, and Lottie. Collaborative team player delivering secure, optimized solutions with a focus on UX/UI.
    </p>
</section>

<!-- Skills -->
<section id="skills" class="py-16 px-6 bg-gray-100">
    <h2 class="text-3xl font-bold mb-8 text-center">Core Skills</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl mx-auto">
        <div class="bg-white p-6 rounded-lg shadow">
            <h3 class="font-semibold text-xl mb-4">Front-End</h3>
            <ul class="list-disc list-inside text-gray-700">
                <li>React.js, Next.js, Redux</li>
                <li>HTML5, CSS3 (SCSS/SASS), Tailwind CSS, Bootstrap</li>
                <li>JavaScript (ES6+), TypeScript, jQuery, Angular</li>
                <li>Animation/Motion: Framer Motion, GSAP, Lottie</li>
            </ul>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
            <h3 class="font-semibold text-xl mb-4">Back-End</h3>
            <ul class="list-disc list-inside text-gray-700">
                <li>Node.js, Python, Django</li>
                <li>RESTful APIs, GraphQL</li>
                <li>Databases: MySQL</li>
            </ul>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
            <h3 class="font-semibold text-xl mb-4">Cloud & DevOps</h3>
            <ul class="list-disc list-inside text-gray-700">
                <li>Azure deployment, CI/CD pipelines</li>
                <li>Git, GitHub Actions, Azure DevOps</li>
                <li>Testing & Debugging, OpenAI API</li>
            </ul>
        </div>
    </div>
</section>

<!-- Experience -->
<section id="experience" class="py-16 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-8 text-center">Experience</h2>
    <div class="bg-white p-8 rounded-lg shadow mb-6">
        <h3 class="text-2xl font-semibold mb-2">Front-End Developer | Infosys Pvt Ltd</h3>
        <p class="text-gray-600 mb-2">Aug 2022 – Jul 2025</p>
        <p class="text-gray-700 mb-2"><strong>Client:</strong> Los Angeles Unified School District (LAUSD)</p>
        <p class="text-gray-700 mb-4"><strong>Project:</strong> My Integrated Student Information System – Master Scheduling</p>
        <ul class="list-disc list-inside text-gray-700">
            <li>Developed responsive and interactive web interfaces using ReactJS, HTML, CSS, JavaScript.</li>
            <li>Implemented dynamic dashboards, data tables, and forms to display real-time student data.</li>
            <li>Ensured cross-browser compatibility, accessibility, and mobile-friendly design.</li>
            <li>Integrated front-end with APIs to fetch and visualize live student data efficiently.</li>
            <li>Applied UX/UI best practices to improve user experience.</li>
            <li>Collaborated with backend developers for smooth data flow and feature integration.</li>
            <li>Participated in Full Stack Python Django with Angular training.</li>
        </ul>
    </div>
</section>

<!-- Projects -->
<section id="projects" class="py-16 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-8 text-center">Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="card bg-white p-6 rounded-lg shadow relative overflow-hidden">
            <h3 class="text-xl font-semibold mb-2">LAUSD Student Dashboard</h3>
            <p class="text-gray-700 mb-2">Dynamic front-end dashboard displaying student attendance, grades, and test scores with API integration.</p>
            <p class="text-gray-600 mb-2"><strong>Technologies:</strong> React.js, HTML5, CSS3, JavaScript, REST API</p>
            <a href="#" class="text-purple-600 font-semibold hover:underline">View Project</a>
        </div>
        <div class="card bg-white p-6 rounded-lg shadow relative overflow-hidden">
            <h3 class="text-xl font-semibold mb-2">Full-Stack Demo Project</h3>
            <p class="text-gray-700 mb-2">End-to-end project demonstrating front-end and back-end integration with a database and REST API.</p>
            <p class="text-gray-600 mb-2"><strong>Technologies:</strong> Node.js, React.js, MySQL</p>
            <a href="#" class="text-purple-600 font-semibold hover:underline">View Project</a>
        </div>
    </div>
</section>

<!-- Contact -->
<section id="contact" class="py-16 px-6 max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
    <p class="text-gray-700 mb-6">Email: <a href="c:\Users\dilsh\OneDrive\Documents\Resume_UAE\DILSHA_P_REACT.pdf" class="text-purple-600 hover:underline">dilshanasar11@gmail.com</a></p>
    <p class="text-gray-700 mb-6">LinkedIn: <a href="https://www.linkedin.com/in/dilsha-p-266456265?lip" class="text-purple-600 hover:underline">linkedin.com/in/dilsha-p-266456265</a></p>
    <p class="text-gray-700 mb-6">GitHub: <a href="https://github.com/dilsha-tech" class="text-purple-600 hover:underline">github.com/dilsha-tech</a></p>
    <a href="mailto:dilshanasar11@gmail.com" class="bg-purple-600 text-white px-6 py-3 rounded-full font-semibold hover:bg-purple-700 transition">Send Email</a>
</section>

<script>
    // Dark Mode Toggle
    const toggleBtn = document.getElementById('darkToggle');
    toggleBtn.addEventListener('click', () => {
        document.body.classList.toggle('dark-mode');
    });
</script>

</body>
</html>
