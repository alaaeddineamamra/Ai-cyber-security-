# Informatique-
Informatique 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>مصادر تعلم الذكاء الاصطناعي والأمن السيبراني</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Cairo&display=swap');
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }
  body {
    font-family: 'Cairo', sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: #eee;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem;
    overflow-x: hidden;
  }
  header {
    font-size: 2.8rem;
    margin-bottom: 1rem;
    letter-spacing: 0.1em;
    text-shadow: 0 0 8px #00f0ff, 0 0 20px #00f0ff;
    animation: glow 2.5s infinite alternate;
  }
  @keyframes glow {
    0% { text-shadow: 0 0 8px #00f0ff, 0 0 20px #00f0ff; }
    100% { text-shadow: 0 0 20px #00fff0, 0 0 40px #00fff0; }
  }
  .container {
    background: rgba(255 255 255 / 0.1);
    border-radius: 15px;
    box-shadow: 0 8px 30px rgba(0, 255, 255, 0.3);
    max-width: 800px;
    width: 100%;
    padding: 2rem;
    backdrop-filter: blur(12px);
    animation: fadeInUp 1s ease forwards;
  }
  @keyframes fadeInUp {
    0% {opacity: 0; transform: translateY(30px);}
    100% {opacity: 1; transform: translateY(0);}
  }
  h2 {
    color: #00fff0;
    margin-bottom: 1rem;
    border-bottom: 2px solid #00fff0;
    padding-bottom: 0.5rem;
  }
  ul {
    list-style: none;
  }
  ul li {
    background: rgba(0, 255, 255, 0.1);
    margin-bottom: 0.8rem;
    padding: 0.75rem 1rem;
    border-radius: 10px;
    font-size: 1.15rem;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease;
    box-shadow: 0 0 10px rgba(0, 255, 255, 0.15);
  }
  ul li:hover {
    background: #00fff0;
    color: #003333;
    transform: scale(1.05);
    box-shadow: 0 0 20px #00fff0;
  }
  footer {
    margin-top: 3rem;
    font-size: 0.9rem;
    color: #00fff0aa;
  }
  a.source-link {
    color: #00fff0;
    text-decoration: none;
    font-weight: 600;
  }
  a.source-link:hover {
    text-decoration: underline;
  }
</style>
</head>
<body>
<header>مصادر تعلم الذكاء الاصطناعي والأمن السيبراني</header>
<div class="container" role="main">
  <section aria-label="مصادر الذكاء الاصطناعي">
    <h2>مصادر الذكاء الاصطناعي</h2>
    <ul>
      <li onclick="window.open('https://www.coursera.org/specializations/deep-learning','_blank')">Coursera - Deep Learning Specialization</li>
      <li onclick="window.open('https://www.fast.ai/','_blank')">Fast.ai - Practical Deep Learning for Coders</li>
      <li onclick="window.open('https://www.edx.org/professional-certificate/harvardx-data-science','_blank')">edX - Harvard Data Science Professional Certificate</li>
      <li onclick="window.open('https://machinelearningmastery.com/start-here/','_blank')">Machine Learning Mastery - Start Here</li>
      <li onclick="window.open('https://ai.google/education/','_blank')">Google AI Education</li>
    </ul>
  </section>
  <section aria-label="مصادر الأمن السيبراني" style="margin-top:2rem;">
    <h2>مصادر الأمن السيبراني</h2>
    <ul>
      <li onclick="window.open('https://www.cybrary.it/','_blank')">Cybrary - Free Cybersecurity Training</li>
      <li onclick="window.open('https://www.coursera.org/specializations/cyber-security','_blank')">Coursera - Cybersecurity Specialization</li>
      <li onclick="window.open('https://www.edx.org/course/introduction-to-cyber-security','_blank')">edX - Introduction to Cybersecurity</li>
      <li onclick="window.open('https://www.offensive-security.com/','_blank')">Offensive Security - Penetration Testing Training</li>
      <li onclick="window.open('https://www.sans.org/','_blank')">SANS Institute - Security Training & Certifications</li>
    </ul>
  </section>
</div>
<footer>© 2025 جميع الحقوق محفوظة</footer>
<script>
  // Animate header text color pulse
  const header = document.querySelector('header');
  let hue = 180;
  setInterval(() => {
    hue += 1;
    if(hue > 360) hue = 180;
    header.style.textShadow = `0 0 20px hsl(${hue}, 100%, 50%), 0 0 40px hsl(${hue}, 100%, 60%)`;
  }, 100);

  // Accessibility: make list items keyboard accessible
  document.querySelectorAll('ul li').forEach(li => {
    li.setAttribute('tabindex', '0');
    li.addEventListener('keydown', e => {
      if(e.key === 'Enter' || e.key === ' ') {
        li.click();
      }
    });
  });
</script>
</body>
</html>

