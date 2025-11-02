# Ivans-s-Website
website for personal portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ivan's Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem 0;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }

        h1 {
            color: #2c3e50;
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }

        .subtitle {
            color: #7f8c8d;
            font-size: 1.2rem;
        }

        .main-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .card {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .card h2 {
            color: #2c3e50;
            margin-bottom: 1rem;
        }

        .card p {
            color: #555;
            line-height: 1.8;
            margin-bottom: 1rem;
        }

        .skills-list {
            list-style: none;
            padding: 0;
        }

        .skills-list li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #eee;
        }

        footer {
            background: rgba(255, 255, 255, 0.95);
            padding: 1.5rem 0;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
            flex-wrap: wrap;
        }

        .contact-links a {
            color: #667eea;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border: 2px solid #667eea;
            border-radius: 5px;
            transition: all 0.3s ease;
        }

        .contact-links a:hover {
            background: #667eea;
            color: white;
        }

        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Welcome to Ivan's Website</h1>
            <p class="subtitle">Personal Portfolio & Creative Space</p>
        </header>

        <section class="main-content">
            <div class="card">
                <h2>About Ivan</h2>
                <p>I'm an aspiring Data Analyst driven by a passion for turning complex data into clear, actionable insights. With a strong foundation in Python, SQL, and Excel, I specialize in analyzing trends, automating reports, and visualizing data that tells a story. Every dataset has a hidden pattern — and I love uncovering it!</p>

                <p>My journey in AI and Data Science has sharpened my ability to think analytically and creatively. From data cleaning to predictive modeling, I enjoy every step that transforms raw numbers into real-world solutions. Using tools like Pandas, NumPy, and Matplotlib, I've built projects that highlight both accuracy and innovation.</p>

                <p>Proficient in Excel dashboards and SQL queries, I can efficiently manipulate, filter, and interpret data from multiple sources. Python allows me to automate repetitive workflows and bring intelligence into everyday analytics.</p>

                <p>I believe data is more than numbers — it's a language that drives business growth and smarter decisions. My goal is to bridge the gap between data and decision-making through clarity, precision, and curiosity.</p>

                <p>Currently exploring machine learning, AI-powered analytics, and data-driven storytelling, I aim to build a career where insight meets impact.</p>

                <p>Always learning. Always analyzing. Always evolving. Let's decode data — and shape the future, one dataset at a time.</p>
            </div>

            <div class="card">
                <h2>My Skills</h2>
                <ul class="skills-list">
                    <li>• Python</li>
                    <li>• SQL</li>
                    <li>• Excel</li>
                    <li>• Power BI</li>
                </ul>
            </div>
        </section>

        <footer>
            <p>&copy; 2024 Ivan's Website. All rights reserved.</p>
            <div class="contact-links">
                <a href="https://www.linkedin.com/in/ivan-lucas-merugumalla-aab50a2a6/" target="_blank">LinkedIn</a>
                <a href="mailto:leepikamoses17@gmail.com">Email</a>
                <a href="https://wa.me/7872788468" target="_blank">WhatsApp</a>
                <a href="tel:+7872788468">Phone</a>
            </div>
        </footer>
    </div>
</body>
</html>
