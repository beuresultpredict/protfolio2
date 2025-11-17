<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishna Raj | Mechanical Design Portfolio</title>
    <style>
        /* --- 1. General Settings --- */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f7f6;
            color: #333;
        }
        a { text-decoration: none; transition: 0.3s; }

        /* --- 2. Header Section --- */
        .header {
            background: linear-gradient(135deg, #1e3c72, #2a5298); /* Professional Blue Theme */
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }
        .profile-img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            border: 5px solid white;
            object-fit: cover;
            margin-bottom: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }
        .header h1 { margin: 0; font-size: 2.5rem; letter-spacing: 1px; }
        .header p { font-size: 1.1rem; opacity: 0.95; margin-top: 5px; font-weight: 300; }

        /* --- 3. Main Layout --- */
        .container {
            width: 90%;
            max-width: 850px;
            margin: -40px auto 20px; /* Overlap effect */
            position: relative;
        }

        /* --- 4. Cards/Sections --- */
        .section {
            background: white;
            padding: 35px;
            margin-bottom: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            border-top: 4px solid transparent;
            transition: transform 0.2s;
        }
        .section:hover { border-top: 4px solid #1e3c72; transform: translateY(-2px); }
        
        h2 {
            color: #1e3c72;
            border-bottom: 2px solid #e0e0e0;
            padding-bottom: 10px;
            margin-top: 0;
            font-size: 1.5rem;
        }

        /* --- 5. Buttons & Tags --- */
        .btn-linkedin {
            display: inline-block;
            background: white;
            color: #1e3c72;
            padding: 10px 30px;
            border-radius: 30px;
            font-weight: bold;
            margin-top: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .btn-linkedin:hover { background: #f0f0f0; transform: translateY(-2px); }

        .view-cert-btn {
            display: inline-block;
            color: #d35400;
            border: 1px solid #d35400;
            padding: 6px 15px;
            border-radius: 4px;
            font-size: 0.85rem;
            font-weight: 600;
            margin-top: 8px;
        }
        .view-cert-btn:hover { background-color: #d35400; color: white; }

        .skill-tag {
            display: inline-block;
            background: #e8f0fe;
            color: #1967d2;
            padding: 8px 16px;
            margin: 5px;
            border-radius: 6px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        /* --- 6. Content Items --- */
        .item { margin-bottom: 25px; border-bottom: 1px solid #f0f0f0; padding-bottom: 20px; }
        .item:last-child { border-bottom: none; margin-bottom: 0; padding-bottom: 0; }
        .item h3 { margin-bottom: 5px; color: #2c3e50; font-size: 1.15rem; }
        .date { color: #7f8c8d; font-size: 0.9rem; margin-top: 0; font-style: italic; }
        .description { color: #444; text-align: justify; }

        /* --- 7. Footer --- */
        .footer { text-align: center; padding: 30px; color: #777; font-size: 0.9rem; }
        .contact-link { color: #1e3c72; font-weight: bold; }

        @media (max-width: 600px) {
            .header h1 { font-size: 2rem; }
            .container { width: 95%; }
            .section { padding: 20px; }
        }
    </style>
</head>
<body>

    <div class="header">
        <img src="profile.jpg" alt="Krishna Raj" class="profile-img">
        
        <h1>Krishna Raj</h1>
        <p>Mechanical Engineering Student | Aspiring Automotive Design Engineer</p>
        
        <a href="#" target="_blank" class="btn-linkedin">
            Connect on LinkedIn
        </a>
    </div>

    <div class="container">

        <div class="section">
            <h2>About Me</h2>
            <p class="description">
                I am a final-year Mechanical Engineering student passionate about <strong>Product Design, Automobile Engineering, and Manufacturing</strong>. 
                With a strong foundation in CAD tools like SolidWorks and CATIA, I aim to bridge the gap between theoretical concepts and real-world applications. 
                I am a disciplined learner, actively expanding my skills in Industry 4.0 technologies.
            </p>
        </div>

        <div class="section">
            <h2>Education</h2>
            <div class="item">
                <h3>B.Tech in Mechanical Engineering</h3>
                <p class="date">2022 - 2026 (Expected)</p>
                <p><strong>Institute:</strong> [Enter Your College Name Here]</p>
            </div>
            <div class="item">
                <h3>Higher Secondary Education (12th)</h3>
                <p><strong>School:</strong> [Enter Your School Name Here]</p>
            </div>
        </div>

        <div class="section">
            <h2>Technical Skills</h2>
            <div>
                <span class="skill-tag">AutoCAD (2D Drafting)</span>
                <span class="skill-tag">SolidWorks (Modeling)</span>
                <span class="skill-tag">CATIA V5 (Surfacing)</span>
                <span class="skill-tag">GD&T Basics</span>
                <span class="skill-tag">Laser Manufacturing</span>
                <span class="skill-tag">MS Office Suite</span>
            </div>
        </div>

        <div class="section">
            <h2>Projects & Experience</h2>
            
            <div class="item">
                <h3>1. Advanced Manufacturing Specialization</h3>
                <p class="date">Oct 2025 - Present | NPTEL Course</p>
                <p class="description">
                    Actively pursuing an 8-week intensive course on <strong>Laser Based Manufacturing</strong>. 
                    Focusing on laser-material interaction, cutting parameters, and precision engineering applications.
                </p>
            </div>

            <div class="item">
                <h3>2. Digital Content & Leadership</h3>
                <p class="description">
                    Founder of an educational Instagram series decoding the <em>'Shreemad Bhagwad Gita'</em>. 
                    Demonstrated strong communication skills, video editing, and consistency by managing content for a growing audience.
                </p>
            </div>

            <div class="item">
                <h3>3. Academic Stakeholder Management</h3>
                <p class="description">
                    Led a student initiative to address curriculum and administrative concerns. 
                    Drafted professional communications and mobilized 4,000+ students to provide structured feedback to the university administration.
                </p>
            </div>
        </div>

        <div class="section">
            <h2>Certifications</h2>
            
            <div class="item">
                <h3>Laser Based Manufacturing</h3>
                <p class="date">Issued by: NPTEL (IIT)</p>
                <a href="nptel-cert.jpg" target="_blank" class="view-cert-btn">View Certificate 📜</a>
            </div>

            <div class="item">
                <h3>SolidWorks / CAD Workshop</h3>
                <p class="date">Issued by: [Institute Name]</p>
                <a href="workshop-cert.jpg" target="_blank" class="view-cert-btn">View Certificate 📜</a>
            </div>
        </div>

        <div class="section" style="text-align: center;">
            <h2>Contact Me</h2>
            <p>Open for Internship and Job opportunities in Design & Production.</p>
            <p>📧 Email: <a href="mailto:your.email@example.com" class="contact-link">your.email@example.com</a></p>
            <p>📍 Location: Bihar, India</p>
        </div>

    </div>

    <div class="footer">
        <p>© 2025 Krishna Raj. Hosted on GitHub Pages.</p>
    </div>

</body>
</html>
