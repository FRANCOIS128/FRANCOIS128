<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Francois’ GitHub Page</title>
  <style>
    /* 整体布局 */
    body {
      margin: 0;
      padding: 0;
      font-family: sans-serif;
      display: flex;
    }

    /* 左侧栏 */
    .sidebar {
      width: 250px;
      padding: 20px;
      box-sizing: border-box;
      float: left;
      margin-right: 40px;
      text-align: left; /* 全部左对齐 */
      background: #f9f9f9;
    }
    .sidebar h1 {
      margin-top: 0;
      font-size: 1.8em;
    }
    .sidebar em {
      color: #555;
    }

    /* Socials */
    .socials {
      margin-top: 1.5em;
    }
    .socials h3 {
      margin: 0 0 0.5em 0;
      font-size: 1.1em;
    }
    .socials .icons {
      display: flex;
      gap: 0.5em;
      flex-wrap: wrap;
    }
    .socials .icons a img {
      display: block;
    }

    /* About Me */
    .about {
      margin-top: 2em;
    }
    .about h3 {
      margin-bottom: 0.5em;
      font-size: 1.1em;
    }
    .about p {
      margin: 0.3em 0;
      line-height: 1.4;
    }

    /* Skills */
    .skills {
      margin-top: 2em;
    }
    .skills h3 {
      margin-bottom: 0.5em;
      font-size: 1.1em;
    }
    .skills .icons {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5em;
    }
    .skills .icons img {
      height: 24px;
    }

    /* Highlights */
    .highlights {
      margin-top: 2em;
    }
    .highlights h3 {
      margin-bottom: 0.5em;
      font-size: 1.1em;
    }
    .highlights ul {
      padding-left: 1.2em;
      margin: 0.3em 0;
    }

    /* Featured Projects */
    .projects {
      margin-top: 2em;
    }
    .projects h3 {
      margin-bottom: 0.5em;
      font-size: 1.1em;
    }
    .projects table {
      width: 100%;
      border-collapse: collapse;
    }
    .projects td {
      padding: 0.5em;
      vertical-align: top;
    }
    .projects img {
      width: 100%;
      height: auto;
      border-radius: 4px;
    }
    .projects h4 {
      margin: 0.5em 0 0.3em;
      font-size: 1em;
    }
    .projects p {
      margin: 0.2em 0;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <!-- 左侧栏 -->
  <div class="sidebar">
    <!-- 名字 & 职业 -->
    <h1>👋 Hi I'm Francois</h1>
    <p><em>Data Scientist & FullStack Developer</em></p>
    <p>Computer Science @ University of Melbourne</p>
    <p>Building useful products and sharing knowledge to help the community.</p>

    <!-- Socials -->
    <div class="socials">
      <h3>Socials</h3>
      <div class="icons">
        <a href="https://github.com/FRANCOIS128">
          <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" alt="GitHub"/>
        </a>
        <a href="https://www.linkedin.com/in/francoisli08">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn"/>
        </a>
        <a href="mailto:franlijd08@gmail.com">
          <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/>
        </a>
      </div>
    </div>

    <!-- About Me -->
    <div class="about">
      <h3>About Me</h3>
      <p>I’m a Computer Science student at the University of Melbourne with a passion for electronics and mathematical exploration.</p>
      <p>I focus on building high-performance web applications using React, Node.js, and complement my work by exploring cloud and hardware innovations.</p>
      <p>Feel free to explore my projects to see how I blend innovative technology with rigorous problem-solving.</p>
    </div>

    <!-- Skills -->
    <div class="skills">
      <h3>Skills</h3>
      <div class="icons">
        <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5"/>
        <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3"/>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"/>
        <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white" alt="Next.js"/>
        <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white" alt="Node.js"/>
        <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker"/>
        <img src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white" alt="Prisma"/>
        <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" alt="AWS"/>
        <img src="https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white" alt="Three.js"/>
        <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git"/>
      </div>
    </div>

    <!-- Highlights -->
    <div class="highlights">
      <h3>Highlights</h3>
      <ul>
        <li>🎯 Built a real-time data visualization dashboard with <strong>Three.js</strong> and <strong>WebSockets</strong>.</li>
        <li>☁️ Deployed containerized apps on <strong>AWS ECS</strong> using <strong>Docker</strong> & <strong>GitHub Actions</strong>.</li>
        <li>🤖 Automated workflows with <strong>Python</strong> cloud functions and AI integrations.</li>
      </ul>
    </div>

    <!-- Featured Projects -->
    <div class="projects">
      <h3>📂 Featured Projects</h3>
      <table>
        <tr>
          <td align="center">
            <a href="#">
              <img src="https://via.placeholder.com/200" alt="Project One Screenshot"/>
              <h4>Project One</h4>
            </a>
            <p>⚡️ Brief description…（待填）</p>
            <p><strong>Tech:</strong> …</p>
          </td>
          <td align="center">
            <a href="#">
              <img src="https://via.placeholder.com/200" alt="Project Two Screenshot"/>
              <h4>Project Two</h4>
            </a>
            <p>🔧 Short description…（待填）</p>
            <p><strong>Tech:</strong> …</p>
          </td>
          <!-- 如需更多项目，可复制 <td> … </td> 块 -->
        </tr>
      </table>
    </div>
  </div>

  <!-- 右侧主内容区（示例占位） -->
  <div class="main-content" style="flex:1; padding:20px;">
    <!-- 在这里放你的 README、文章、项目详情等 -->
  </div>

</body>
</html>
