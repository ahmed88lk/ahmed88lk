<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Quantum AI Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1a1a1a, #0a0a0a);
            color: #e0e0e0;
            min-height: 100vh;
        }
        .header {
            text-align: center;
            padding: 50px 20px;
            animation: fadeIn 2s ease-in-out;
        }
        .quantum-banner {
            width: 100%;
            height: 300px;
            background: url('https://media.giphy.com/media/26ufdipQqU2lhNA4g/giphy.gif') center/cover no-repeat;
            border-bottom: 2px solid #4CAF50;
        }
        .content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            margin: 40px 0;
        }
        .typing-effect {
            font-size: 1.5em;
            white-space: nowrap;
            overflow: hidden;
            border-right: 2px solid #4CAF50;
            animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #4CAF50 }
        }
        .tech-stack {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .tech-card {
            background: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .tech-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 15px rgba(76, 175, 80, 0.5);
        }
        .project {
            background: #2a2a2a;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            transition: transform 0.3s ease;
        }
        .project:hover {
            transform: scale(1.02);
        }
        .github-stats {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .contact-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }
        .contact-icon {
            font-size: 2em;
            color: #4CAF50;
            transition: transform 0.3s ease;
        }
        .contact-icon:hover {
            transform: scale(1.2);
        }
        .equation {
            font-size: 1.2em;
            color: #4CAF50;
        }
        .particle {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            pointer-events: none;
        }
        @media (max-width: 768px) {
            .tech-stack {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="particle" id="particles"></div>
    
    <div class="header">
        <div class="typing-effect">Quantum AI Engineer | Researcher | Innovator</div>
        <div class="typing-effect" style="animation-delay: 3s">Exploring Intelligence & Trust in AI</div>
        <div class="typing-effect" style="animation-delay: 6s">Nature and Math through Quantum Lens</div>
    </div>

    <div class="quantum-banner"></div>

    <div class="content">
        <div class="section">
            <h2>🌱 Welcome to My Quantum AI World</h2>
            <p>Hi, I'm <strong>Ahmed Ben Elswaey</strong>, a Quantum AI Researcher and AI Engineer building intelligent systems at the intersection of quantum physics and machine learning.</p>
            
            <div class="currently">
                <h3>🔭 Currently:</h3>
                <ul>
                    <li>Teaching neural networks quantum mechanics (they're better at math than I am)</li>
                    <li>Developing self-explaining AI agents using quantum-inspired architectures</li>
                    <li>Researching NISQ-era algorithms for practical AI applications</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>🛠️ Technical Arsenal</h2>
            <div class="tech-stack">
                <div class="tech-card">
                    <h3>Languages</h3>
                    <ul>
                        <li>Python</li>
                        <li>Rust</li>
                        <li>Julia</li>
                    </ul>
                </div>
                <div class="tech-card">
                    <h3>Quantum Tools</h3>
                    <ul>
                        <li>Qiskit</li>
                        <li>PennyLane</li>
                        <li>Cirq</li>
                    </ul>
                </div>
                <div class="tech-card">
                    <h3>AI/ML Frameworks</h3>
                    <ul>
                        <li>PyTorch</li>
                        <li>TensorFlow Quantum</li>
                        <li>Scikit-learn</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>📜 Research Spotlight</h2>
            <div class="project">
                <h3>"Quantum AI in the NISQ Era: A Relevance Taxonomy"</h3>
                <p>Accepted at IEEE QCNC 2025 (Nara, Japan)</p>
                <p>Developing hybrid quantum-classical algorithms for practical machine learning applications in noisy quantum systems.</p>
            </div>
        </div>

        <div class="section">
            <h2>🔮 Quantum Equations I Love</h2>
            <div class="equation">
                <p>$$\hat{H}|\psi\rangle = i\hbar\frac{\partial}{\partial t}|\psi\rangle \quad \text{(Schrödinger Equation)}$$</p>
                <p>$$\rho_{AB} \neq \rho_A \otimes \rho_B \quad \text{(Quantum Entanglement)}$$</p>
            </div>
        </div>

        <div class="section">
            <h2>🚀 Recent Projects</h2>
            <div class="project">
                <h3>QAgent Framework</h3>
                <p>Quantum-inspired multi-agent system</p>
            </div>
            <div class="project">
                <h3>Entangled Neural Networks</h3>
                <p>Using quantum correlations in deep learning</p>
            </div>
            <div class="project">
                <h3>Quantum NLP</h3>
                <p>Because words should be in superposition too</p>
            </div>
        </div>

        <div class="section">
            <h2>📊 GitHub Stats</h2>
            <div class="github-stats">
                <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=radical" alt="GitHub Stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=radical" alt="Top Languages">
            </div>
        </div>

        <div class="section">
            <h2>🌌 Let's Collide Ideas</h2>
            <div class="contact-icons">
                <a href="https://www.linkedin.com/in/ahmed-ben-elswayeh-322844231/" target="_blank" class="contact-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="48" height="48">
                </a>
                <a href="https://leetcode.com/u/walker404/" target="_blank" class="contact-icon">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/leetcode/leetcode-original.svg" width="48" height="48">
                </a>
                <a href="https://topmate.io/ahmed33" target="_blank" class="contact-icon">
                    <img src="https://topmate.io/favicon.ico" width="48" height="48">
                </a>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
    <script>
        particlesJS('particles', {
            particles: {
                number: { value: 80, density: { enable: true, value_area: 800 } },
                color: { value: "#4CAF50" },
                shape: { type: "circle" },
                opacity: { random: true, anim: { enable: true, speed: 1, opacity_min: 0.1 } },
                size: { random: true, value: 3 },
                line_linked: { enable: false },
                move: { enable: true, speed: 2, direction: "none", random: true }
            },
            interactivity: {
                detect_on: "canvas",
                events: { onhover: { enable: true, mode: "repulse" } }
            },
            retina_detect: true
        });
    </script>
    <script async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
</body>
</html>
