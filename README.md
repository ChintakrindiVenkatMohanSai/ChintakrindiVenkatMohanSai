<!-- 🌌 Ultimate Animated Developer Portfolio by Chintakrindi Venkat Mohan Sai -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chintakrindi Venkat Mohan Sai | Developer Portfolio</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
  /* === GLOBAL STYLE === */
  * { box-sizing: border-box; }
  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(270deg, #050816, #11002C, #190028, #2B0040);
    background-size: 800% 800%;
    animation: gradientBG 14s ease infinite;
    color: #fff;
    text-align: center;
    overflow-x: hidden;
  }

  @keyframes gradientBG {
    0% {background-position: 0% 50%;}
    50% {background-position: 100% 50%;}
    100% {background-position: 0% 50%;}
  }

  /* === HEADER === */
  h1 {
    font-size: 3rem;
    margin-top: 70px;
    font-weight: 700;
    background: linear-gradient(90deg, #00DBDE, #FC00FF);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    text-shadow: 0px 0px 25px rgba(252, 0, 255, 0.3);
  }

  h3 {
    font-weight: 400;
    color: #cfcfcf;
    margin-bottom: 20px;
  }

  .typing {
    color: #00FFFF;
    font-size: 1.3rem;
    font-weight: 500;
    height: 30px;
  }

  /* === ANIMATION (Typing effect) === */
  .typing::after {
    content: '|';
    animation: blink 1s infinite;
  }

  @keyframes blink {
    0%, 50% { opacity: 1; }
    51%, 100% { opacity: 0; }
  }

  /* === SECTION CARDS === */
  .section {
    margin: 50px auto;
    width: 85%;
    max-width: 900px;
    background: rgba(255, 255, 255, 0.07);
    border-radius: 20px;
    padding: 30px;
    backdrop-filter: blur(10px);
    box-shadow: 0 0 25px rgba(0, 0, 0, 0.3);
    transition: transform 0.4s ease, box-shadow 0.4s ease;
  }

  .section:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 35px rgba(255, 0, 255, 0.2);
  }

  /* === IMAGE === */
  img.coding {
    width: 350px;
    border-radius: 10px;
    box-shadow: 0 0 25px rgba(255, 255, 255, 0.15);
    margin-top: 20px;
  }

  /* === BUTTON === */
  .btn {
    display: inline-block;
    padding: 12px 25px;
    margin: 20px;
    background: linear-gradient(90deg, #00DBDE, #FC00FF);
    border-radius: 30px;
    color: white;
    text-decoration: none;
    font-weight: 600;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .btn:hover {
    transform: scale(1.05);
    box-shadow: 0px 0px 20px rgba(252, 0, 255, 0.6);
  }

  /* === ICONS === */
  .badges img, .icons img {
    margin: 10px;
    height: 45px;
    transition: transform 0.3s ease, filter 0.3s ease;
  }

  .badges img:hover, .icons img:hover {
    transform: scale(1.15);
    filter: drop-shadow(0 0 10px #00FFFF);
  }

  /* === FOOTER === */
  footer {
    margin-top: 60px;
    color: #bbb;
    font-size: 0.95rem;
  }

  /* === FLOATING EFFECT === */
  @keyframes float {
    0% {transform: translateY(0);}
    50% {transform: translateY(-10px);}
    100% {transform: translateY(0);}
  }

  .floating { animation: float 4s ease-in-out infinite; }

</style>
</head>
<body>

  <!-- HEADER -->
  <h1>👋 Hi, I'm Chintakrindi Venkat Mohan Sai</h1>
  <h3>💻 Frontend Developer | ML Enthusiast | Full Stack Explorer</h3>
  <p class="typing floating">Building creative experiences with code...</p>

  <img src="https://tse2.mm.bing.net/th/id/OIP.uuPvXNnlckEFe14kiG9CygHaFj?pid=Api&P=0&h=180" alt="coding" class="coding floating" />

  <!-- ABOUT -->
  <div class="section">
    <h2>🚀 About Me</h2>
    <p>🔭 Currently working on <b>Machine Learning–Based Ensemble Model for Quality Estimation of Diabetic Retinopathy Images</b></p>
    <p>🌱 Exploring <b>Deep Learning · Computer Vision · Full Stack Development</b></p>
    <p>💬 Ask me about <b>React · Python · OpenCV · Django · TensorFlow</b></p>
    <p>📫 Reach me: <b>mohansaichintakrindi@gmail.com</b></p>
    <a href="#" class="btn">📄 Download Resume</a>
  </div>

  <!-- CONNECT -->
  <div class="section">
    <h2>🌐 Connect With Me</h2>
    <div class="badges">
      <a href="https://www.linkedin.com/in/chintakrindi-venkata-moahan-sai-b2a70b252/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
      </a>
      <a href="mailto:mohansaichintakrindi@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
      </a>
      <a href="https://github.com/chintakrindivenkatmohansai" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white">
      </a>
    </div>
  </div>

  <!-- SKILLS -->
  <div class="section">
    <h2>🛠️ Languages & Tools</h2>
    <div class="icons">
      <img src="https://skillicons.dev/icons?i=html,css,js,react,angular,nodejs,python,django,tensorflow,sklearn,opencv,matlab,mysql,mongodb,php,bootstrap,figma,photoshop,c&theme=dark" alt="skills">
    </div>
  </div>

  <!-- GITHUB STATS -->
  <div class="section">
    <h2>📊 GitHub Analytics</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=chintakrindivenkatmohansai&show_icons=true&theme=radical&hide_border=true" height="180">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=chintakrindivenkatmohansai&theme=radical&hide_border=true" height="180">
  </div>

  <!-- FOOTER -->
  <footer>
    ✨ “Code is not just logic — it’s creativity in motion.” ✨ <br>
    © 2025 Chintakrindi Venkat Mohan Sai. All Rights Reserved.
  </footer>

</body>
</html>
