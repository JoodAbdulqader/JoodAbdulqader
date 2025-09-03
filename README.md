# Create the updated README.html file with the user's LinkedIn and email, and without Twitter.
html_content = """<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Jood Abdulqader - GitHub Profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
      margin: 0;
      padding: 20px;
    }
    h1, h2 {
      color: #2c3e50;
    }
    .section {
      margin-bottom: 30px;
    }
    .highlight {
      color: #007acc;
      font-weight: bold;
    }
    ul {
      list-style-type: square;
      padding-left: 20px;
    }
    a {
      color: #007acc;
      text-decoration: none;
      word-break: break-word;
    }
    a:hover {
      text-decoration: underline;
    }
    .tagline {
      font-style: italic;
      color: #555;
    }
  </style>
</head>
<body>
  <h1>👋 Hi, I’m <span class="highlight">Jood Abdulqader</span></h1>
  <p>🎓 <strong>Computer Science Student @ University of Jordan (KASIT)</strong> | 📈 <strong>Top of my class (GPA 4.0/4.0)</strong> | 🤖 <strong>AI & Full-Stack Enthusiast</strong></p>

  <div class="section">
    <h2>🚀 About Me</h2>
    <ul>
      <li>💡 Passionate about <strong>Artificial Intelligence, Software Engineering, and Problem Solving</strong>.</li>
      <li>🏆 Always ranked <strong>#1 in my cohort</strong>, with strong academic and practical experience.</li>
      <li>👩‍💻 Skilled in <strong>front-end & back-end development</strong>: building scalable apps with a focus on clean architecture.</li>
      <li>🔬 Currently leading/working on projects like:
        <ul>
          <li><strong>Sukoun</strong> 🧘 – An AI-powered mental well-being app.</li>
          <li><strong>Wasla</strong> 🌍 – A platform connecting Arab startups with investors.</li>
        </ul>
      </li>
      <li>🌐 Active in <strong>IEEE CIS</strong> and university volunteering teams (KASIT).</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠️ Tech Stack</h2>
    <ul>
      <li><strong>Languages:</strong> Java, C++, Python, C, SQL, JavaScript, TypeScript</li>
      <li><strong>Frameworks &amp; Tools:</strong> ASP.NET Core, EF Core, React, Node.js, Express, MySQL, PostgreSQL</li>
      <li><strong>AI/ML:</strong> Scikit-Learn, Pandas, NumPy, ML basics (agents, pipelines)</li>
      <li><strong>Other:</strong> Git/GitHub, Swagger, Postman, Docker (basics)</li>
    </ul>
  </div>

  <div class="section">
    <h2>📚 Learning &amp; Growth</h2>
    <ul>
      <li>⚡ Solving algorithmic challenges on <strong>LeetCode</strong> and <strong>Codewars</strong>.</li>
      <li>📘 Writing and sharing <strong>study booklets</strong> for Java, Data Structures, Web Development, Databases, and Linear Algebra.</li>
      <li>🤖 Exploring <strong>AI agents</strong> and practical applications of <strong>machine learning</strong>.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🌟 Achievements</h2>
    <ul>
      <li>🏅 Recognized by <strong>IEEE</strong> (Member of the Month, leadership roles).</li>
      <li>📘 Authored <strong>multiple study booklets</strong> to help peers master CS fundamentals.</li>
      <li>🤝 Led technical &amp; organizational efforts in <strong>AI Industry Week</strong> and hackathons.</li>
    </ul>
  </div>

  <div class="section">
    <h2>📫 Connect with Me</h2>
    <ul>
      <li>💼 <a href="https://www.linkedin.com/in/jood-abdelqader-46b70337a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank" rel="noopener noreferrer">LinkedIn</a></li>
      <li>📧 <a href="mailto:joodabdulqader@gmail.com">joodabdulqader@gmail.com</a></li>
    </ul>
  </div>

  <p class="tagline">✨ “Passionate about building tech that makes a difference – from AI to entrepreneurship.”</p>
</body>
</html>
"""
with open("/mnt/data/README.html", "w", encoding="utf-8") as f:
    f.write(html_content)
"/mnt/data/README.html"
