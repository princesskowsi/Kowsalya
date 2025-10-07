<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project: ORIGIN — The Living Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            box-sizing: border-box;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Rajdhani', sans-serif;
            background: #000;
            color: #00ffff;
            overflow-x: hidden;
            cursor: none;
        }

        /* Custom Cursor */
        .cursor {
            position: fixed;
            width: 20px;
            height: 20px;
            background: radial-gradient(circle, #00ffff 0%, transparent 70%);
            border-radius: 50%;
            pointer-events: none;
            z-index: 9999;
            mix-blend-mode: screen;
            transition: transform 0.1s ease;
        }

        .cursor-trail {
            position: fixed;
            width: 4px;
            height: 4px;
            background: #ff00ff;
            border-radius: 50%;
            pointer-events: none;
            z-index: 9998;
            opacity: 0.7;
        }

        /* Animated Background */
        .bg-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        /* Main Container */
        .container {
            position: relative;
            z-index: 1;
        }

        /* Login Interface */
        .login-section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, rgba(0,255,255,0.1) 0%, rgba(255,0,255,0.1) 100%);
            position: relative;
        }

        .login-terminal {
            background: rgba(0,0,0,0.8);
            border: 2px solid #00ffff;
            border-radius: 10px;
            padding: 40px;
            max-width: 600px;
            width: 90%;
            box-shadow: 0 0 50px rgba(0,255,255,0.3);
            animation: pulse-glow 2s infinite alternate;
        }

        @keyframes pulse-glow {
            0% { box-shadow: 0 0 50px rgba(0,255,255,0.3); }
            100% { box-shadow: 0 0 80px rgba(0,255,255,0.6); }
        }

        .terminal-text {
            font-family: 'Orbitron', monospace;
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        .typing-text {
            border-right: 2px solid #00ffff;
            animation: typing 3s steps(40) 1s forwards, blink 1s infinite;
            white-space: nowrap;
            overflow: hidden;
            width: 0;
        }

        @keyframes typing {
            to { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }

        .access-btn {
            background: linear-gradient(45deg, #00ffff, #ff00ff);
            border: none;
            padding: 15px 30px;
            border-radius: 25px;
            color: #000;
            font-family: 'Orbitron', monospace;
            font-weight: 700;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            margin-top: 20px;
        }

        .access-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 0 30px rgba(0,255,255,0.8);
        }

        /* Main Portfolio Sections */
        .section {
            min-height: 100vh;
            padding: 80px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
            opacity: 0;
            transform: translateY(50px);
            transition: all 1s ease;
        }

        .section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .section-title {
            font-family: 'Orbitron', monospace;
            font-size: 3rem;
            font-weight: 900;
            text-align: center;
            margin-bottom: 40px;
            background: linear-gradient(45deg, #00ffff, #ff00ff, #00ff00);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: gradient-shift 3s ease-in-out infinite;
        }

        @keyframes gradient-shift {
            0%, 100% { filter: hue-rotate(0deg); }
            50% { filter: hue-rotate(180deg); }
        }

        /* Profile and DNA Layout */
        .profile-dna-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 1000px;
            margin: 40px auto;
            gap: 60px;
        }

        .profile-section {
            flex: 1;
            max-width: 400px;
        }

        .profile-avatar {
            width: 150px;
            height: 150px;
            position: relative;
            margin: 0 auto 30px;
        }

        .avatar-ring {
            position: absolute;
            width: 100%;
            height: 100%;
            border: 3px solid #00ffff;
            border-radius: 50%;
            animation: avatar-rotate 10s linear infinite;
        }

        .avatar-ring::before {
            content: '';
            position: absolute;
            top: -3px;
            left: -3px;
            right: -3px;
            bottom: -3px;
            border: 1px solid #ff00ff;
            border-radius: 50%;
            animation: avatar-rotate 8s linear infinite reverse;
        }

        .avatar-core {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80px;
            height: 80px;
            background: linear-gradient(45deg, #00ffff, #ff00ff);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Orbitron', monospace;
            font-size: 2rem;
            font-weight: 900;
            color: #000;
            box-shadow: 0 0 30px rgba(0,255,255,0.5);
        }

        @keyframes avatar-rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .profile-info {
            text-align: center;
        }

        .profile-name {
            font-family: 'Orbitron', monospace;
            font-size: 2rem;
            font-weight: 900;
            color: #00ffff;
            margin-bottom: 10px;
            text-shadow: 0 0 20px rgba(0,255,255,0.5);
        }

        .profile-title {
            font-size: 1.2rem;
            color: #ff00ff;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .profile-subtitle {
            font-size: 1rem;
            color: #00ff00;
            margin-bottom: 30px;
        }

        .profile-stats {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .stat-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 15px;
            background: rgba(0,255,255,0.1);
            border: 1px solid #00ffff;
            border-radius: 5px;
            font-family: 'Orbitron', monospace;
            font-size: 0.9rem;
        }

        .stat-label {
            color: #00ffff;
        }

        .stat-value {
            color: #00ff00;
            font-weight: 700;
        }

        /* DNA Strand Animation */
        .dna-container {
            width: 300px;
            height: 400px;
            position: relative;
            flex-shrink: 0;
        }

        /* About Content */
        .about-content {
            max-width: 800px;
            margin: 60px auto 0;
            text-align: center;
        }

        .bio-text {
            margin-top: 20px;
        }

        .bio-tagline {
            font-size: 1.4rem;
            color: #00ffff;
            font-weight: 600;
            margin-bottom: 25px;
            font-family: 'Orbitron', monospace;
        }

        .bio-description {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #ffffff;
            margin-bottom: 25px;
        }

        .bio-mission {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #ff00ff;
            font-style: italic;
        }

        .dna-strand {
            position: absolute;
            width: 4px;
            height: 100%;
            background: linear-gradient(to bottom, #00ffff, #ff00ff);
            left: 50%;
            transform: translateX(-50%);
            animation: dna-pulse 2s infinite;
        }

        .dna-base {
            position: absolute;
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, #00ffff, #ff00ff);
            left: 50%;
            transform: translateX(-50%);
            animation: dna-rotate 4s linear infinite;
        }

        @keyframes dna-pulse {
            0%, 100% { opacity: 0.7; }
            50% { opacity: 1; }
        }

        @keyframes dna-rotate {
            0% { transform: translateX(-50%) rotateY(0deg); }
            100% { transform: translateX(-50%) rotateY(360deg); }
        }

        /* Neural Network */
        .neural-network {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 30px;
            max-width: 800px;
            margin: 40px auto;
        }

        .neural-node {
            width: 120px;
            height: 120px;
            border: 2px solid #00ffff;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgba(0,255,255,0.1);
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .neural-node:hover {
            transform: scale(1.1);
            box-shadow: 0 0 40px rgba(0,255,255,0.8);
            border-color: #ff00ff;
        }

        .neural-node::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(0,255,255,0.3), transparent);
            animation: neural-scan 3s linear infinite;
        }

        @keyframes neural-scan {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Project Holograms */
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            max-width: 1200px;
            margin: 40px auto;
        }

        .project-card {
            background: rgba(0,0,0,0.7);
            border: 1px solid #00ffff;
            border-radius: 15px;
            padding: 30px;
            position: relative;
            cursor: pointer;
            transition: all 0.3s ease;
            overflow: hidden;
        }

        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,255,255,0.3);
        }

        .project-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,0,255,0.2), transparent);
            transition: left 0.5s ease;
        }

        .project-card:hover::before {
            left: 100%;
        }

        /* Contact Orb */
        .contact-orb {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(0,255,255,0.3), rgba(255,0,255,0.3));
            border: 2px solid #00ffff;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            animation: orb-float 3s ease-in-out infinite;
            margin: 40px auto;
        }

        @keyframes orb-float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }

        .contact-orb:hover {
            animation-play-state: paused;
            transform: scale(1.1);
            box-shadow: 0 0 60px rgba(0,255,255,0.8);
        }

        /* System Messages */
        .system-msg {
            font-family: 'Orbitron', monospace;
            color: #00ff00;
            font-size: 0.9rem;
            margin: 10px 0;
            opacity: 0;
            animation: fade-in 0.5s ease forwards;
        }

        @keyframes fade-in {
            to { opacity: 1; }
        }

        /* Contact Form Styles */
        .contact-container {
            max-width: 800px;
            margin: 40px auto;
            text-align: center;
        }

        .contact-intro {
            margin-bottom: 40px;
            font-size: 1.1rem;
            color: #ffffff;
        }

        .contact-form {
            background: rgba(0,0,0,0.7);
            border: 2px solid #00ffff;
            border-radius: 15px;
            padding: 40px;
            margin-bottom: 40px;
            box-shadow: 0 0 30px rgba(0,255,255,0.2);
        }

        .form-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
            margin-bottom: 30px;
        }

        .form-group {
            text-align: left;
        }

        .form-group.full-width {
            grid-column: 1 / -1;
        }

        .form-group label {
            display: block;
            font-family: 'Orbitron', monospace;
            font-size: 0.9rem;
            color: #00ffff;
            margin-bottom: 8px;
            font-weight: 600;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            background: rgba(0,255,255,0.1);
            border: 1px solid #00ffff;
            border-radius: 5px;
            padding: 12px 15px;
            color: #ffffff;
            font-family: 'Rajdhani', sans-serif;
            font-size: 1rem;
            transition: all 0.3s ease;
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #ff00ff;
            box-shadow: 0 0 15px rgba(255,0,255,0.3);
            background: rgba(255,0,255,0.1);
        }

        .form-group input::placeholder,
        .form-group textarea::placeholder {
            color: rgba(255,255,255,0.5);
        }

        .submit-btn {
            position: relative;
            background: linear-gradient(45deg, #00ffff, #ff00ff);
            border: none;
            padding: 15px 40px;
            border-radius: 25px;
            color: #000;
            font-family: 'Orbitron', monospace;
            font-weight: 700;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            overflow: hidden;
        }

        .submit-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 0 40px rgba(0,255,255,0.8);
        }

        .btn-glow {
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: left 0.5s ease;
        }

        .submit-btn:hover .btn-glow {
            left: 100%;
        }

        .contact-info {
            background: rgba(0,0,0,0.5);
            border: 1px solid #00ffff;
            border-radius: 10px;
            padding: 30px;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .info-item {
            text-align: center;
            padding: 15px;
            background: rgba(0,255,255,0.1);
            border-radius: 8px;
            border: 1px solid rgba(0,255,255,0.3);
        }

        .info-label {
            font-family: 'Orbitron', monospace;
            font-size: 0.8rem;
            color: #00ffff;
            margin-bottom: 5px;
            font-weight: 600;
        }

        .info-value {
            color: #ffffff;
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .section-title {
                font-size: 2rem;
            }
            
            .neural-network {
                grid-template-columns: repeat(2, 1fr);
                gap: 20px;
            }
            
            .neural-node {
                width: 100px;
                height: 100px;
            }
            
            .login-terminal {
                padding: 20px;
            }
            
            .terminal-text {
                font-size: 1rem;
            }
            
            .profile-dna-container {
                flex-direction: column;
                gap: 40px;
                text-align: center;
            }
            
            .profile-avatar {
                width: 120px;
                height: 120px;
            }
            
            .avatar-core {
                width: 60px;
                height: 60px;
                font-size: 1.5rem;
            }
            
            .profile-name {
                font-size: 1.5rem;
            }
            
            .dna-container {
                width: 250px;
                height: 300px;
                margin: 0 auto;
            }
            
            .bio-tagline {
                font-size: 1.2rem;
            }
            
            .bio-description, .bio-mission {
                font-size: 1rem;
            }
            
            .form-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }
            
            .info-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }
            
            .contact-form {
                padding: 25px;
            }
            
            .submit-btn {
                padding: 12px 30px;
                font-size: 1rem;
            }
        }

        /* Hidden initially */
        .main-content {
            display: none;
        }

        .main-content.active {
            display: block;
        }
    </style>
</head>
<body>
    <!-- Custom Cursor -->
    <div class="cursor"></div>
    
    <!-- Animated Background Canvas -->
    <canvas class="bg-canvas" id="bgCanvas"></canvas>
    
    <div class="container">
        <!-- Login Interface -->
        <section class="login-section" id="loginSection">
            <div class="login-terminal">
                <div class="terminal-text">
                    <div class="system-msg">SYSTEM: Initializing neural interface...</div>
                    <div class="system-msg" style="animation-delay: 1s;">SYSTEM: Scanning biometric data...</div>
                    <div class="system-msg" style="animation-delay: 2s;">IDENTITY VERIFICATION: KOWSALYA</div>
                    <div class="system-msg" style="animation-delay: 3s;">STATUS: Cybersecurity Engineer & Digital Innovator</div>
                </div>
                <div class="typing-text" style="animation-delay: 4s;">ACCESS LEVEL: AUTHORIZED</div>
                <button class="access-btn" onclick="enterSystem()">ENTER NEURAL NETWORK</button>
            </div>
        </section>

        <!-- Main Portfolio Content -->
        <div class="main-content" id="mainContent">
            <!-- About: Genetic Data -->
            <section class="section" id="about">
                <h2 class="section-title">GENETIC DATA</h2>
                <div class="system-msg">SYSTEM: Decrypting personal matrix...</div>
                
                <!-- Profile and DNA Layout -->
                <div class="profile-dna-container">
                    <!-- Profile Section -->
                    <div class="profile-section">
                        <div class="profile-avatar">
                            <div class="avatar-ring"></div>
                            <div class="avatar-core">T</div>
                        </div>
                        <div class="profile-info">
                            <h3 class="profile-name">KOWSALYA</h3>
                            <div class="profile-title">Cybersecurity Engineer</div>
                            <div class="profile-subtitle">Digital Innovator</div>
                            <div class="profile-stats">
                                <div class="stat-item">
                                    <span class="stat-label">LOCATION</span>
                                    <span class="stat-value">CHENNAI, INDIA</span>
                                </div>
                                <div class="stat-item">
                                    <span class="stat-label">EXPERIENCE</span>
                                    <span class="stat-value">0 YEARS</span>
                                </div>
                                <div class="stat-item">
                                    <span class="stat-label">SPECIALIZATION</span>
                                    <span class="stat-value">CYBERSECURITY</span>
                                </div>
                                <div class="stat-item">
                                    <span class="stat-label">EDUCATION</span>
                                    <span class="stat-value">B.E CYBERSECURITY</span>
                                </div>
                                <div class="stat-item">
                                    <span class="stat-label">CERTIFICATIONS</span>
                                    <span class="stat-value">C++, PYTHON</span>
                                </div>
                                <div class="stat-item">
                                    <span class="stat-label">STATUS</span>
                                    <span class="stat-value">AVAILABLE</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- DNA Structure -->
                    <div class="dna-container">
                        <div class="dna-strand"></div>
                        <div class="dna-base" style="top: 10%; animation-delay: 0s;"></div>
                        <div class="dna-base" style="top: 25%; animation-delay: 0.5s;"></div>
                        <div class="dna-base" style="top: 40%; animation-delay: 1s;"></div>
                        <div class="dna-base" style="top: 55%; animation-delay: 1.5s;"></div>
                        <div class="dna-base" style="top: 70%; animation-delay: 2s;"></div>
                        <div class="dna-base" style="top: 85%; animation-delay: 2.5s;"></div>
                    </div>
                </div>
                
                <!-- About Me Section -->
                <div class="about-content">
                    <div class="system-msg">SYSTEM: Loading biographical data...</div>
                    <div class="bio-text">
                        <p class="bio-tagline">I am not a portfolio. I am a system — learning, adapting, evolving.</p>
                        <p class="bio-description">
                            A cybersecurity engineer who bridges the gap between digital defense and creative innovation. 
                            My neural pathways process threats, design solutions, and architect secure digital experiences. 
                            I specialize in transforming complex security challenges into elegant, user-friendly solutions.
                        </p>
                        <p class="bio-mission">
                            My mission: To create a safer digital world through innovative security frameworks, 
                            AI-powered threat detection, and immersive user experiences that make cybersecurity accessible to all.
                        </p>
                    </div>
                </div>
            </section>

            <!-- Skills Neural Map -->
            <section class="section" id="skills">
                <h2 class="section-title">NEURAL MAP</h2>
                <div class="system-msg">SYSTEM: Mapping cognitive abilities...</div>
                <div class="neural-network">
                    <div class="neural-node" onclick="activateSkill(this, 'Cybersecurity')">
                        <span style="font-weight: 600;">SECURITY</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'Network Defense')">
                        <span style="font-weight: 600;">DEFENSE</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'Penetration Testing')">
                        <span style="font-weight: 600;">PENTEST</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'AI & Machine Learning')">
                        <span style="font-weight: 600;">AI/ML</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'Web Development')">
                        <span style="font-weight: 600;">WEB DEV</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'Cloud Security')">
                        <span style="font-weight: 600;">CLOUD</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'Digital Forensics')">
                        <span style="font-weight: 600;">FORENSICS</span>
                    </div>
                    <div class="neural-node" onclick="activateSkill(this, 'System Architecture')">
                        <span style="font-weight: 600;">SYSTEMS</span>
                    </div>
                </div>
                <div id="skillDisplay" style="text-align: center; margin-top: 30px; font-size: 1.2rem; min-height: 50px;"></div>
            </section>

            <!-- Projects Core -->
            <section class="section" id="projects">
                <h2 class="section-title">PROJECT CORE</h2>
                <div class="system-msg">SYSTEM: Loading holographic archives...</div>
                <div class="project-grid">
                    <div class="project-card" onclick="loadProject('SecureNet AI')">
                        <h3 style="color: #00ffff; font-family: 'Orbitron', monospace; margin-bottom: 15px;">SecureNet AI</h3>
                        <p>Advanced threat detection system using machine learning algorithms to identify and neutralize cyber threats in real-time.</p>
                        <div style="margin-top: 15px; color: #ff00ff; font-size: 0.9rem;">STATUS: ACTIVE</div>
                    </div>
                    <div class="project-card" onclick="loadProject('Neural Defense Grid')">
                        <h3 style="color: #00ffff; font-family: 'Orbitron', monospace; margin-bottom: 15px;">Neural Defense Grid</h3>
                        <p>Distributed security architecture that adapts and learns from attack patterns to strengthen network defenses.</p>
                        <div style="margin-top: 15px; color: #ff00ff; font-size: 0.9rem;">STATUS: EVOLVING</div>
                    </div>
                    <div class="project-card" onclick="loadProject('Quantum Encryption Protocol')">
                        <h3 style="color: #00ffff; font-family: 'Orbitron', monospace; margin-bottom: 15px;">Quantum Encryption</h3>
                        <p>Next-generation encryption protocol leveraging quantum computing principles for unbreakable data protection.</p>
                        <div style="margin-top: 15px; color: #ff00ff; font-size: 0.9rem;">STATUS: CLASSIFIED</div>
                    </div>
                    <div class="project-card" onclick="loadProject('Digital Consciousness Interface')">
                        <h3 style="color: #00ffff; font-family: 'Orbitron', monospace; margin-bottom: 15px;">Consciousness Interface</h3>
                        <p>Revolutionary UI/UX framework that creates living, breathing digital experiences that adapt to user behavior.</p>
                        <div style="margin-top: 15px; color: #ff00ff; font-size: 0.9rem;">STATUS: PROTOTYPE</div>
                    </div>
                </div>
            </section>

            <!-- Achievements Terminal -->
            <section class="section" id="achievements">
                <h2 class="section-title">SYSTEM UNLOCKS</h2>
                <div class="system-msg">SYSTEM: Retrieving achievement data...</div>
                <div style="max-width: 800px; margin: 40px auto;">
                    <div class="achievement" style="margin: 20px 0; padding: 20px; background: rgba(0,255,255,0.1); border-left: 4px solid #00ffff; border-radius: 5px;">
                        <div style="color: #00ff00; font-family: 'Orbitron', monospace;">ACCESS LEVEL ↑ - Network Defense Specialist</div>
                        <div style="margin-top: 10px;">Advanced certification in network security and threat mitigation</div>
                    </div>
                    <div class="achievement" style="margin: 20px 0; padding: 20px; background: rgba(255,0,255,0.1); border-left: 4px solid #ff00ff; border-radius: 5px;">
                        <div style="color: #00ff00; font-family: 'Orbitron', monospace;">SKILL UNLOCKED - Ethical Hacking</div>
                        <div style="margin-top: 10px;">Certified Ethical Hacker with expertise in penetration testing</div>
                    </div>
                    <div class="achievement" style="margin: 20px 0; padding: 20px; background: rgba(0,255,0,0.1); border-left: 4px solid #00ff00; border-radius: 5px;">
                        <div style="color: #00ff00; font-family: 'Orbitron', monospace;">EVOLUTION COMPLETE - AI Integration</div>
                        <div style="margin-top: 10px;">Successfully integrated AI/ML capabilities into security frameworks</div>
                    </div>
                </div>
            </section>

            <!-- Contact Node -->
            <section class="section" id="contact">
                <h2 class="section-title">COMMUNICATION NODE</h2>
                <div class="system-msg">SYSTEM: Establishing secure channel...</div>
                
                <div class="contact-container">
                    <div class="contact-intro">
                        <p>Ready to collaborate on securing the digital frontier? Initiate contact protocol to establish a secure communication channel.</p>
                    </div>
                    
                    <form class="contact-form" onsubmit="sendMessage(event)">
                        <div class="form-grid">
                            <div class="form-group">
                                <label for="name">IDENTITY VERIFICATION</label>
                                <input type="text" id="name" name="name" required placeholder="Enter your designation...">
                            </div>
                            
                            <div class="form-group">
                                <label for="email">SECURE CHANNEL</label>
                                <input type="email" id="email" name="email" required placeholder="your.email@domain.com">
                            </div>
                            
                            <div class="form-group">
                                <label for="subject">MISSION OBJECTIVE</label>
                                <select id="subject" name="subject" required>
                                    <option value="">Select mission type...</option>
                                    <option value="collaboration">Collaboration Request</option>
                                    <option value="consultation">Security Consultation</option>
                                    <option value="project">Project Partnership</option>
                                    <option value="hiring">Recruitment Inquiry</option>
                                    <option value="other">Other Transmission</option>
                                </select>
                            </div>
                            
                            <div class="form-group full-width">
                                <label for="message">ENCRYPTED MESSAGE</label>
                                <textarea id="message" name="message" required placeholder="Transmit your message through the neural network..." rows="6"></textarea>
                            </div>
                        </div>
                        
                        <button type="submit" class="submit-btn">
                            <span>TRANSMIT MESSAGE</span>
                            <div class="btn-glow"></div>
                        </button>
                    </form>
                    
                    <div class="contact-info">
                        <div class="info-grid">
                            <div class="info-item">
                                <div class="info-label">DIRECT CHANNEL</div>
                                <div class="info-value">kaushalyap757@gmail.com</div>
                            </div>
                            <div class="info-item">
                                <div class="info-label">NEURAL LINK</div>
                                <div class="info-value">linkedin.com/in/kowsalya</div>
                            </div>
                            <div class="info-item">
                                <div class="info-label">CODE REPOSITORY</div>
                                <div class="info-value">github.com/kowsalya</div>
                            </div>
                            <div class="info-item">
                                <div class="info-label">RESPONSE TIME</div>
                                <div class="info-value">24-48 HOURS</div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>


        </div>
    </div>

    <script>
        // Cursor Trail Effect
        let cursor = document.querySelector('.cursor');
        let trails = [];
        
        document.addEventListener('mousemove', (e) => {
            cursor.style.left = e.clientX + 'px';
            cursor.style.top = e.clientY + 'px';
            
            // Create trail
            let trail = document.createElement('div');
            trail.className = 'cursor-trail';
            trail.style.left = e.clientX + 'px';
            trail.style.top = e.clientY + 'px';
            document.body.appendChild(trail);
            
            trails.push(trail);
            
            setTimeout(() => {
                trail.style.opacity = '0';
                setTimeout(() => {
                    if (trail.parentNode) {
                        trail.parentNode.removeChild(trail);
                    }
                    trails = trails.filter(t => t !== trail);
                }, 300);
            }, 100);
        });

        // Animated Background
        const canvas = document.getElementById('bgCanvas');
        const ctx = canvas.getContext('2d');
        
        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }
        
        resizeCanvas();
        window.addEventListener('resize', resizeCanvas);
        
        let particles = [];
        
        class Particle {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.vx = (Math.random() - 0.5) * 0.5;
                this.vy = (Math.random() - 0.5) * 0.5;
                this.life = Math.random() * 100;
            }
            
            update() {
                this.x += this.vx;
                this.y += this.vy;
                this.life += 0.5;
                
                if (this.x < 0 || this.x > canvas.width) this.vx *= -1;
                if (this.y < 0 || this.y > canvas.height) this.vy *= -1;
            }
            
            draw() {
                ctx.save();
                ctx.globalAlpha = Math.sin(this.life * 0.02) * 0.5 + 0.5;
                ctx.fillStyle = `hsl(${180 + Math.sin(this.life * 0.01) * 60}, 70%, 50%)`;
                ctx.beginPath();
                ctx.arc(this.x, this.y, 1, 0, Math.PI * 2);
                ctx.fill();
                ctx.restore();
            }
        }
        
        // Initialize particles
        for (let i = 0; i < 100; i++) {
            particles.push(new Particle());
        }
        
        function animate() {
            ctx.fillStyle = 'rgba(0, 0, 0, 0.05)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            particles.forEach(particle => {
                particle.update();
                particle.draw();
            });
            
            // Draw connections
            ctx.strokeStyle = 'rgba(0, 255, 255, 0.1)';
            ctx.lineWidth = 0.5;
            
            for (let i = 0; i < particles.length; i++) {
                for (let j = i + 1; j < particles.length; j++) {
                    let dx = particles[i].x - particles[j].x;
                    let dy = particles[i].y - particles[j].y;
                    let distance = Math.sqrt(dx * dx + dy * dy);
                    
                    if (distance < 100) {
                        ctx.beginPath();
                        ctx.moveTo(particles[i].x, particles[i].y);
                        ctx.lineTo(particles[j].x, particles[j].y);
                        ctx.stroke();
                    }
                }
            }
            
            requestAnimationFrame(animate);
        }
        
        animate();

        // System Functions
        function enterSystem() {
            document.getElementById('loginSection').style.display = 'none';
            document.getElementById('mainContent').classList.add('active');
            
            // Trigger section animations
            setTimeout(() => {
                document.getElementById('about').classList.add('visible');
            }, 500);
        }

        function activateSkill(node, skill) {
            // Reset all nodes
            document.querySelectorAll('.neural-node').forEach(n => {
                n.style.background = 'rgba(0,255,255,0.1)';
                n.style.borderColor = '#00ffff';
            });
            
            // Activate clicked node
            node.style.background = 'rgba(255,0,255,0.3)';
            node.style.borderColor = '#ff00ff';
            
            // Display skill info
            document.getElementById('skillDisplay').innerHTML = `
                <div style="color: #00ff00;">NEURAL PATHWAY ACTIVATED</div>
                <div style="color: #00ffff; font-size: 1.4rem; margin-top: 10px;">${skill}</div>
                <div style="color: #ff00ff; margin-top: 10px;">Processing enhanced cognitive patterns...</div>
            `;
        }

        function loadProject(projectName) {
            alert(`SYSTEM: Loading ${projectName} environment...\n\nProject portal simulation would open here in a full implementation.`);
        }

        function sendMessage(event) {
            event.preventDefault();
            
            const form = event.target;
            const formData = new FormData(form);
            const name = formData.get('name');
            const email = formData.get('email');
            const subject = formData.get('subject');
            const message = formData.get('message');
            
            // Simulate sending message
            const submitBtn = form.querySelector('.submit-btn');
            const originalText = submitBtn.innerHTML;
            
            submitBtn.innerHTML = '<span>TRANSMITTING...</span><div class="btn-glow"></div>';
            submitBtn.disabled = true;
            
            setTimeout(() => {
                submitBtn.innerHTML = '<span>MESSAGE SENT ✓</span><div class="btn-glow"></div>';
                submitBtn.style.background = 'linear-gradient(45deg, #00ff00, #00ffff)';
                
                setTimeout(() => {
                    alert(`SYSTEM: Message transmission successful!\n\nFrom: ${name}\nChannel: ${email}\nObjective: ${subject}\n\nYour message has been encrypted and sent through the neural network. Expect a response within 24-48 hours.`);
                    
                    // Reset form
                    form.reset();
                    submitBtn.innerHTML = originalText;
                    submitBtn.style.background = 'linear-gradient(45deg, #00ffff, #ff00ff)';
                    submitBtn.disabled = false;
                }, 1000);
            }, 2000);
        }

        // Scroll-triggered animations
        window.addEventListener('scroll', () => {
            const sections = document.querySelectorAll('.section');
            sections.forEach(section => {
                const rect = section.getBoundingClientRect();
                if (rect.top < window.innerHeight * 0.8) {
                    section.classList.add('visible');
                }
            });
        });

        // Add some ambient sound simulation (visual feedback)
        setInterval(() => {
            if (Math.random() < 0.1) {
                const pulse = document.createElement('div');
                pulse.style.position = 'fixed';
                pulse.style.top = Math.random() * window.innerHeight + 'px';
                pulse.style.left = Math.random() * window.innerWidth + 'px';
                pulse.style.width = '4px';
                pulse.style.height = '4px';
                pulse.style.background = '#00ff00';
                pulse.style.borderRadius = '50%';
                pulse.style.pointerEvents = 'none';
                pulse.style.zIndex = '1000';
                pulse.style.animation = 'fade-in 0.5s ease forwards, fade-in 0.5s ease 1s reverse forwards';
                document.body.appendChild(pulse);
                
                setTimeout(() => {
                    if (pulse.parentNode) {
                        pulse.parentNode.removeChild(pulse);
                    }
                }, 2000);
            }
        }, 1000);
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98a683fdf1614da5',t:'MTc1OTc2NzkzNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
