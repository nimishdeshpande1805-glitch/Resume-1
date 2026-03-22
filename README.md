<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Professional Resume</title>
    <style>
        /* This is CSS - It makes the website look pretty */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f7f6;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 40px;
            text-align: center;
            border-radius: 8px 8px 0 0;
        }
        .container {
            background: white;
            padding: 40px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-radius: 0 0 8px 8px;
        }
        h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        .skill-badge {
            display: inline-block;
            background: #3498db;
            color: white;
            padding: 5px 15px;
            margin: 5px;
            border-radius: 20px;
            font-size: 14px;
        }
        form {
            background: #ecf0f1;
            padding: 20px;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background: #27ae60;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
        }
        button:hover {
            background: #219150;
        }
    </style>
</head>
<body>

    <header>
        <h1> NIMISH DESHPANDE </h1>
        <p> Student | Tech Enthusiast</p>
    </header>

    <div class="container">
        <section>
            <h2>About Me</h2>
            <p>I am a passionate web developer with creating clean, user-friendly interfaces. I love solving complex problems and learning new technologies every day.</p>
        </section>

        <section>
            <h2>Top Skills</h2>
            <span class="skill-badge">HTML5</span>
            <span class="skill-badge">CSS3</span>
            <span class="skill-badge">JavaScript</span>
            <span class="skill-badge">Accounting</span>
            <span class="skill-badge">Python</span>
        </section>

        <section>
            <h2>Work Experience</h2>
            <div style="margin-bottom: 20px;">
                <strong> Student - IIMB</strong> (2025)
                <p> Currently pursuing BBA in Business and Entrepreneurship in online college</p>
            </div>
            <div>
                <strong>Student - Ambedkar College</strong> (2020 - 2022)
                <p>Currently pursuing BBA in offline college</p>
            </div>
        </section>

        <section>
            <h2>Contact Me</h2>
            <form action="#">
                <label>Your Name</label>
                <input type="text" placeholder="Nimish Deshpande">
                
                <label>Your Email</label>
                <input type="email" placeholder="nimish@example.com">
                
                <label>Message</label>
                <textarea rows="4" placeholder="How can I help you?"></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer style="text-align: center; margin-top: 20px; color: #7f8c8d;">
        <p>&copy; 2026 Your Name - Built with HTML/CSS</p>
    </footer>

</body>
</html>
