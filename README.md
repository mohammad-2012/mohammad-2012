<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohammad Akbari · GitHub Profile</title>
  <!-- Google Fonts for cleaner typography -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(135deg, #0a0f1f 0%, #0c1222 100%);
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 2rem;
    }

    /* main card - GitHub readme style with subtle glow */
    .readme-card {
      max-width: 960px;
      width: 100%;
      background: rgba(13, 20, 35, 0.85);
      backdrop-filter: blur(2px);
      border-radius: 2rem;
      padding: 2.2rem 2rem 2.5rem;
      box-shadow: 0 25px 45px -12px rgba(0,0,0,0.6), 0 0 0 1px rgba(71, 125, 255, 0.2);
      transition: all 0.2s;
      border: 1px solid rgba(255,255,255,0.08);
    }

    /* typewriter section */
    .typewriter-area {
      text-align: center;
      margin-bottom: 2rem;
      background: rgba(255,255,255,0.02);
      border-radius: 2rem;
      padding: 1.5rem 1rem;
      border: 1px solid rgba(255,255,255,0.05);
    }

    #typewriter-text {
      font-size: 1.9rem;
      font-weight: 700;
      background: linear-gradient(120deg, #e0e7ff, #b3ccff, #8bb5ff);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      letter-spacing: -0.3px;
      display: inline-block;
      font-family: 'Inter', monospace;
      min-height: 5rem;
    }

    .typewriter-cursor {
      display: inline-block;
      width: 3px;
      height: 2rem;
      background-color: #70a5ff;
      margin-left: 6px;
      vertical-align: middle;
      animation: blink 0.9s step-end infinite;
      border-radius: 2px;
    }

    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }

    /* original style headers */
    h1 {
      font-size: 2.4rem;
      font-weight: 800;
      background: linear-gradient(135deg, #FFFFFF, #b9d0ff);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      margin-top: 0.5rem;
      margin-bottom: 0.75rem;
      letter-spacing: -0.5px;
    }

    .subhead {
      font-size: 1.15rem;
      color: #b9c7e6;
      margin-bottom: 1.6rem;
      font-weight: 400;
    }

    h2 {
      font-size: 1.5rem;
      font-weight: 600;
      margin: 1.6rem 0 1rem 0;
      color: #d6e3ff;
      border-left: 4px solid #3b82f6;
      padding-left: 0.9rem;
    }

    /* expertise badges grid */
    .badge-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 0.6rem;
      margin: 1rem 0 0.5rem 0;
    }

    .badge-grid img {
      transition: transform 0.1s ease;
    }

    .badge-grid img:hover {
      transform: translateY(-2px);
    }

    /* about me content */
    .about-box {
      background: rgba(255,255,255,0.03);
      border-radius: 1.5rem;
      padding: 1.4rem 1.6rem;
      margin: 1rem 0 1.2rem 0;
      border-left: 4px solid #3b82f6;
      transition: 0.2s;
    }

    .about-text {
      color: #cfdef5;
      line-height: 1.65;
      font-size: 1rem;
      font-weight: 400;
    }

    .about-text strong {
      color: #90cdf4;
      font-weight: 600;
    }

    .quote {
      margin-top: 1.3rem;
      font-style: italic;
      color: #9bb4e0;
      border-top: 1px dashed rgba(255,255,255,0.2);
      padding-top: 1rem;
      text-align: center;
    }

    .contact-row {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin: 1.5rem 0 1rem;
    }

    hr {
      border: none;
      height: 1px;
      background: linear-gradient(90deg, transparent, #2d467e, transparent);
      margin: 1rem 0;
    }

    footer {
      text-align: center;
      margin-top: 1.8rem;
      font-size: 0.85rem;
      color: #6f85aa;
    }

    @media (max-width: 600px) {
      .readme-card {
        padding: 1.5rem;
      }
      #typewriter-text {
        font-size: 1.3rem;
      }
      h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>
<div class="readme-card">
  
  <!-- TYPEWRITER SECTION (dynamic greeting in English) -->
  <div class="typewriter-area">
    <div id="typewriter-text"></div>
    <div class="typewriter-cursor"></div>
  </div>

  <!-- MAIN HEADER -->
  <div align="center">
    <h1>👋 Hi there!</h1>
    <p class="subhead">Hi, I'm Mohammad Akbari – a passionate Frontend Developer. And I love coding.</p>
  </div>

  <!-- EXPERTISE SECTION -->
  <h2 align="left">🚀 My Expertise:</h2>
  <div class="badge-grid" align="left">
    <img src="https://img.shields.io/badge/HTML5-e34c26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572b6?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
    <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
    <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white" />
    <img src="https://img.shields.io/badge/TailwindCSS-38b2ac?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
    <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" />
    <img src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white" />
    <img src="https://img.shields.io/badge/Bootstrap-7952b3?style=for-the-badge&logo=bootstrap&logoColor=white" />
    <img src="https://img.shields.io/badge/Figma-f24e1e?style=for-the-badge&logo=figma&logoColor=white" />
    <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobe-photoshop&logoColor=white" />
  </div>

  <!-- ABOUT ME SECTION (English, with journey & full-stack ambition) -->
  <h2 align="left">📖 About Me</h2>
  <div class="about-box">
    <div class="about-text">
      🧑‍💻 <strong>My coding journey started about 1.5 years ago</strong> — since then, I've dived deep into the world of web development. 
      In this relatively short period, I've evolved into a <strong>fully professional Frontend Developer</strong>, mastering modern tools like React, Next.js, Redux, Tailwind, and more. 
      <br><br>
      🚀 I'm not stopping here! Right now, I'm actively <strong>moving toward becoming a Full-Stack Developer</strong>, expanding my backend knowledge and building scalable applications. 
      I believe that great developers never stop learning — and I'm hungry for challenges that make an impact.
      <br><br>
      💡 I enjoy turning complex ideas into clean, responsive, and user-friendly interfaces. Collaboration, clean code, and continuous improvement drive me every day.
    </div>
    <div class="quote">
      🌟 “The best way to learn is to build.” — and that's exactly what I do every single day.
    </div>
  </div>

  <!-- CONTACT SECTION -->
  <h2 align="left">📬 Contact me:</h2>
  <div class="contact-row" align="center">
    <a href="https://t.me/mohammad_dev_2012" target="_blank">
      <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
    </a>
    <!-- you could add more socials if needed, but we keep original -->
  </div>

  <!-- FOOTER QUOTES -->
  <hr />
  <div align="center">
    <p>🧑‍💻 "The best way to learn is to build."</p>
    <p>👩🏻‍💻💖</p>
  </div>
  <footer>
    ✨ Mohammad Akbari · constantly evolving · full-stack horizon ✨
  </footer>
</div>

<script>
  // Typewriter effect — English dynamic message
  // Message includes: "Hello, I'm Mohammad Akbari" and a welcoming intro
  const fullMessage = "✨ Hello, I'm Mohammad Akbari ✨ — Frontend crafter, coding enthusiast, and future full-stack dev. Welcome to my dev universe!";
  
  let i = 0;
  const typewriterElement = document.getElementById('typewriter-text');
  
  function typeNextChar() {
    if (i < fullMessage.length) {
      // add next character
      typewriterElement.innerHTML = fullMessage.substring(0, i + 1);
      i++;
      setTimeout(typeNextChar, 45);  // smooth typing speed
    } else {
      // optional: keep final message, maybe add a subtle restart? but better to keep the full greeting.
      // we can add a blinking effect without removing message.
      // just let it stay — but we add a tiny restart logic after 6 seconds? Not necessary, but could be nice.
      // However, to mimic a "typewriter" that does not erase, we leave the final text. 
      // But if you want it to loop and retype? I'll add a smooth restart after 12 seconds, showing the same message again? 
      // but might be too aggressive. Instead, just keep message and no restart (so it remains readable).
      // But for fun effect: we reset after 10 seconds? No, better keep static. But many typewriters loop? 
      // I'll add an optional re-run with a delay to show the dynamic vibe? maybe not, because it's a profile section and shouldn't flicker constantly.
      // We'll add a soft "restart after 15 seconds" but elegant? Considering GitHub profile, permanent message is fine. 
      // I'll add a small fade then restart? Actually user expects a one-time smooth typewriter. I'll keep it.
      // However to make it more interactive I'll add a mouseover reset? not needed. But we can make cursor blink only.
      // final: keep message fully typed, cursor will keep blinking (CSS animation). Done.
    }
  }
  
  // start typewriter effect after page loads with a tiny delay to look nice
  window.addEventListener('DOMContentLoaded', () => {
    typewriterElement.innerHTML = '';   // start empty
    i = 0;
    setTimeout(typeNextChar, 180);
  });
</script>

<!-- Additional note: all content is in English, and the typewriter says the greeting with name and passion -->
</body>
</html>
