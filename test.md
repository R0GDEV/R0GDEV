<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Om Sharma - Resume</title>
      <link rel="icon" href="https://raw.githubusercontent.com/R0GDEV/Real-Estate-Agency/refs/heads/main/main/src/assets/favicon.ico" />
    <link rel="apple-touch-icon" href="https://raw.githubusercontent.com/R0GDEV/Real-Estate-Agency/refs/heads/main/main/src/assets/favicon.ico" />
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Global Styles */
        body {
          
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f4f4f9;
            background-image: url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"%3E%3Cpath fill="none" stroke="gold" stroke-width="1" d="M0 50 L100 50 M50 0 L50 100 M25 0 L75 100 M75 0 L25 100" /%3E%3Ccircle cx="50" cy="50" r="3" fill="gold" /%3E%3C/svg%3E');
            background-size: 50px 50px;
            background-attachment: fixed;
            background-repeat: repeat;
            

        }


        /* Hover and Transform Animations for Project Cards */
        .card:hover {
            transform: scale(1.05) rotate(-1deg);
            box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.1);
        }

        .card img {
            transition: transform 0.5s ease;
        }

        .card:hover img {
            transform: scale(1.1);
        }
    </style>
</head>

<body class="bg-stone-50/50 ">


    <div class="max-w-5xl mx-auto p-6">

        <div class="base max-w-5xl mx-auto p-6">

            <!-- Header Section -->
            <header class="bg-gradient-to-r from-indigo-600 to-blue-500 text-white py-10 rounded-lg shadow-lg mb-8">
                <h1 class="text-4xl font-bold text-center">Om Sharma</h1>
                <p class="text-lg text-center mt-2">Software Developer | Full-Stack Developer | Cloud Enthusiast</p>
                <div class="flex bg-white flex-wrap justify-center items-center rounded-lg text-blue-500 space-x-2 py-1 mx-2 mt-4">
  <a href="mailto:mr.omsharma.c@gmail.com" class="hover:underline text-center">mr.omsharma.c@gmail.com</a>
  <a href="https://linkedin.com/in/om-nb" class="hover:underline text-center">LinkedIn</a>
  <a href="https://github.com/R0GDEV" class="hover:underline text-center">GitHub</a>
</div>
            </header>

            <!-- Skills Section -->
            <section>
                <h2 class="text-3xl font-semibold text-center mb-4">Skills</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-5">
                    <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                        <h3 class="text-lg font-bold">Programming Languages</h3>
                        <p class="text-sm">JavaScript, TypeScript, Python, Java, C++</p>
                    </div>
                    <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                        <h3 class="text-lg font-bold">Frontend</h3>
                        <p class="text-sm">React, Redux, Next.js, HTML, CSS, Tailwind</p>
                    </div>
                    <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                        <h3 class="text-lg font-bold">Backend</h3>
                        <p class="text-sm">Node.js, Express, MongoDB, REST APIs, GraphQL</p>
                    </div>
                    <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                        <h3 class="text-lg font-bold">Mobile Development</h3>
                        <p class="text-sm">Flutter, React Native</p>
                    </div>
                    <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                        <h3 class="text-lg font-bold">Cloud & DevOps</h3>
                        <p class="text-sm">AWS (EC2, S3, Lambda), Docker, CI/CD</p>
                    </div>
                    <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                        <h3 class="text-lg font-bold">Version Control</h3>
                        <p class="text-sm">Git, GitHub, GitLab</p>
                    </div>
                </div>
            </section>

            <section id="education" class="mt-8 bg-white">
                <h2 class="text-3xl font-semibold text-center mb-4">Education</h2>
                <div class="bg-white p-6 shadow-lg rounded-lg transition-transform duration-300 hover:scale-105">
                    <h3 class="text-xl font-bold text-gray-800">Bachelor's Degree in Computer Science</h3>
                    <p class="text-gray-600 italic">University of Mumbai, 2021 - 2024 <span
                            class="font-bold text-gray-800">| CGPI : 9.03</span></p>
                    <ul class="list-disc list-inside text-gray-600">
                        <li>Graduated with honors.</li>
                        <li>Relevant coursework: Data Structures, Cloud Computing, Web Development.</li>
                    </ul>
                </div>
            </section>
            <!-- Projects Section -->
            <section id="projects" class="mt-8 bg-white">
                <h2 class="text-3xl font-semibold text-center mb-4">Projects</h2>
                <div class="space-y-6">
                    <!-- Project 1 -->
                    <div
                        class="card flex flex-col overflow-hidden border rounded-lg shadow-lg transition-all duration-500 ease-out transform-gpu hover:shadow-2xl">
                        <a href="https://github.com/R0GDEV/Real-Estate-Agency" class="block cursor-pointer">
                            <img src="https://github.com/user-attachments/assets/10d87d9c-9a17-4cd6-9170-65cee5bdc5d8"
                                alt="MERN Real Estate App" class="h-full w-full object-cover object-top" />
                        </a>
                        <div class="p-4">
                            <h3 class="text-lg font-bold">MERN Real Estate App</h3>
                            <time class="text-sm text-gray-600">Apr 2024 - Present</time>
                            <p class="text-sm text-gray-800 mt-2">A full-stack real estate platform for managing
                                listings, client interactions, and advanced property filtering.</p>
                            <div class="mt-2 flex flex-wrap gap-1">
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">React</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Node.js</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">MongoDB</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Express</span>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <a href="https://github.com/R0GDEV/Real-Estate-Agency" target="_blank"
                                class="flex items-center justify-center text-xs bg-blue-600 text-white rounded py-1 hover:bg-blue-500 transition">View
                                on GitHub</a>
                        </div>
                    </div>

                    <!-- Project 2 -->
                    <div
                        class="card flex flex-col overflow-hidden border rounded-lg shadow-lg transition-all duration-500 ease-out transform-gpu hover:shadow-2xl">
                        <a href="https://github.com/R0GDEV/Society-Service-Management-System"
                            class="block cursor-pointer">
                            <img src="https://github.com/R0GDEV/Society-Service-Management-System/assets/153528804/7ceba434-51dc-4ecf-8c3a-a8b8483e7025"
                                alt="Society Service Management System" class="h-full w-full object-cover object-top" />
                        </a>
                        <div class="p-4">
                            <h3 class="text-lg font-bold">Society Service Management System</h3>
                            <time class="text-sm text-gray-600">Dec 2023 - Mar 2024</time>
                            <p class="text-sm text-gray-800 mt-2">Led backend development using Node.js, enhancing
                                database management for improved resident communication and service request tracking.
                            </p>
                            <div class="mt-2 flex flex-wrap gap-1">
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">NodeJS</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Express.Js</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">React</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">MongoDB</span>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <a href="https://github.com/R0GDEV/Society-Service-Management-System" target="_blank"
                                class="flex items-center justify-center text-xs bg-blue-600 text-white rounded py-1 hover:bg-blue-500 transition">View
                                on GitHub</a>
                        </div>
                    </div>

                    <!-- Project 3 -->
                    <div
                        class="card flex flex-col overflow-hidden border rounded-lg shadow-lg transition-all duration-500 ease-out transform-gpu hover:shadow-2xl">
                        <a href="https://github.com/R0GDEV/Cloud-Gaming-based-Drifting-Game"
                            class="block cursor-pointer">
                            <img src="https://github.com/user-attachments/assets/080fe429-5e23-4796-92de-0909db76406e"
                                alt="Cloud Gaming based Drifting Game" class="h-full w-full object-cover object-top" />
                        </a>
                        <div class="p-4">
                            <h3 class="text-lg font-bold">Cloud Gaming based Drifting Game</h3>
                            <time class="text-sm text-gray-600">Jul 2023 - Dec 2023</time>
                            <p class="text-sm text-gray-800 mt-2">Engineered a high-performance drifting game using
                                Unity, Node.js, and WebGL, accessible via cloud gaming platforms.</p>
                            <div class="mt-2 flex flex-wrap gap-1">
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Unity Engine</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">NodeJS</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Express.Js</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">WebGL</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">JavaScript</span>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <a href="https://github.com/R0GDEV/Cloud-Gaming-based-Drifting-Game" target="_blank"
                                class="flex items-center justify-center text-xs bg-blue-600 text-white rounded py-1 hover:bg-blue-500 transition">View
                                on GitHub</a>
                        </div>
                    </div>

                    <!-- Project 4 -->
                    <div
                        class="card flex flex-col overflow-hidden border rounded-lg shadow-lg transition-all duration-500 ease-out transform-gpu hover:shadow-2xl">
                        <a href="https://github.com/R0GDEV/Full-Stack-MERN-Stack---Next.js" class="block cursor-pointer">
                            <img src="https://github.com/user-attachments/assets/c266f5e7-7710-4d16-98ea-d6c9cdbf9f34" alt="E-commerce Website"
                                class="h-full w-full object-cover object-top" />
                        </a>
                        <div class="p-4">
                            <h3 class="text-lg font-bold">E-commerce Website</h3>
                            <time class="text-sm text-gray-600">Sep 2024 - Present</time>
                            <p class="text-sm text-gray-800 mt-2">Created a fully functional e-commerce website with
                                user authentication, product management, and payment integration.</p>
                            <div class="mt-2 flex flex-wrap gap-1">
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">React</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Node.js</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">MongoDB</span>
                                <span class="px-2 py-1 text-xs text-gray-600 bg-gray-200 rounded">Stripe</span>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <a href="https://github.com/R0GDEV/Full-Stack-MERN-Stack---Next.js" target="_blank"
                                class="flex items-center justify-center text-xs bg-blue-600 text-white rounded py-1 hover:bg-blue-500 transition">View
                                on GitHub</a>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Footer Contact -->
            <footer class="mt-16 text-center">
                <p class="text-gray-600">Connect with me:
                    <a href="mailto:mr.omsharma.c@gmail.com"
                        class="text-blue-600 hover:underline">mr.omsharma.c@gmail.com</a>
                </p>
            </footer>
        </div>
</body>

</html>

