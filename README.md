<!-- 🌊 LIQUID MORPHISM PROFILE README -->
<!-- With 3D effects, interactive elements, and dynamic animations -->

<div align="center">

<!-- 3D ANIMATED TITLE WITH LIQUID EFFECT -->
<div style="
  position: relative;
  padding: 30px;
  margin: 20px 0;
  background: linear-gradient(135deg, 
    rgba(48, 164, 108, 0.15), 
    rgba(37, 99, 235, 0.15), 
    rgba(124, 58, 237, 0.15));
  border-radius: 30px;
  border: 2px solid transparent;
  background-clip: padding-box;
  overflow: hidden;
">
  
  <!-- Liquid background blobs -->
  <div style="
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle at 30% 30%, 
      rgba(48, 164, 108, 0.3) 0%, 
      transparent 50%),
      radial-gradient(circle at 70% 70%, 
      rgba(37, 99, 235, 0.3) 0%, 
      transparent 50%);
    animation: liquidFloat 20s infinite linear;
    z-index: 0;
  "></div>
  
  <h1 style="
    position: relative;
    z-index: 1;
    font-size: 3.5rem;
    background: linear-gradient(90deg, 
      #30A46C, #2563eb, #7c3aed, #30A46C);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-size: 300% 300%;
    animation: gradientShift 8s ease infinite;
    text-shadow: 0 5px 15px rgba(48, 164, 108, 0.3);
    margin: 0;
  ">
    <span style="display: inline-block; animation: bounce 2s infinite;">
      👋
    </span>
    Hi, I'm <span style="
      font-weight: 900;
      text-decoration: underline;
      text-decoration-color: #30A46C;
      text-decoration-thickness: 3px;
    ">Sarang Gole</span>
  </h1>
  
  <div style="
    position: relative;
    z-index: 1;
    margin-top: 10px;
    font-size: 1.5rem;
    color: #94a3b8;
  ">
    <div id="typing-text"></div>
  </div>
</div>

<!-- INTERACTIVE 3D CUBE -->
<div style="
  width: 150px;
  height: 150px;
  margin: 40px auto;
  position: relative;
  transform-style: preserve-3d;
  animation: rotateCube 20s infinite linear;
  cursor: pointer;
  transition: transform 0.5s;
" 
onmouseover="this.style.animationPlayState='paused'"
onmouseout="this.style.animationPlayState='running'"
onclick="this.style.transform='rotateX(360deg) rotateY(360deg)'">
  
  <!-- Cube faces -->
  <div style="
    position: absolute;
    width: 150px;
    height: 150px;
    background: linear-gradient(45deg, #30A46C, #2563eb);
    opacity: 0.9;
    border: 2px solid rgba(255,255,255,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    color: white;
  " style="transform: rotateY(0deg) translateZ(75px)">C++</div>
  
  <div style="
    position: absolute;
    width: 150px;
    height: 150px;
    background: linear-gradient(45deg, #2563eb, #7c3aed);
    opacity: 0.9;
    border: 2px solid rgba(255,255,255,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    color: white;
  " style="transform: rotateY(90deg) translateZ(75px)">AI</div>
  
  <div style="
    position: absolute;
    width: 150px;
    height: 150px;
    background: linear-gradient(45deg, #7c3aed, #30A46C);
    opacity: 0.9;
    border: 2px solid rgba(255,255,255,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    color: white;
  " style="transform: rotateY(180deg) translateZ(75px)">WEB</div>
  
  <div style="
    position: absolute;
    width: 150px;
    height: 150px;
    background: linear-gradient(45deg, #30A46C, #7c3aed);
    opacity: 0.9;
    border: 2px solid rgba(255,255,255,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    color: white;
  " style="transform: rotateY(-90deg) translateZ(75px)">DEV</div>
  
  <div style="
    position: absolute;
    width: 150px;
    height: 150px;
    background: linear-gradient(45deg, #2563eb, #30A46C);
    opacity: 0.9;
    border: 2px solid rgba(255,255,255,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    color: white;
  " style="transform: rotateX(90deg) translateZ(75px)">CODE</div>
  
  <div style="
    position: absolute;
    width: 150px;
    height: 150px;
    background: linear-gradient(45deg, #7c3aed, #2563eb);
    opacity: 0.9;
    border: 2px solid rgba(255,255,255,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    font-weight: bold;
    color: white;
  " style="transform: rotateX(-90deg) translateZ(75px)">FUN</div>
</div>

</div>

<!-- CSS ANIMATIONS AND EFFECTS -->
<style>
  @keyframes liquidFloat {
    0% { transform: translate(0, 0) rotate(0deg); }
    25% { transform: translate(5%, 5%) rotate(90deg); }
    50% { transform: translate(0, 10%) rotate(180deg); }
    75% { transform: translate(-5%, 5%) rotate(270deg); }
    100% { transform: translate(0, 0) rotate(360deg); }
  }
  
  @keyframes gradientShift {
    0%, 100% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
  }
  
  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-20px); }
  }
  
  @keyframes rotateCube {
    0% { transform: rotateX(0) rotateY(0); }
    100% { transform: rotateX(360deg) rotateY(360deg); }
  }
  
  @keyframes morphBlob {
    0%, 100% { 
      border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
      transform: scale(1);
    }
    50% { 
      border-radius: 30% 60% 70% 40% / 50% 60% 30% 60%;
      transform: scale(1.1);
    }
  }
  
  @keyframes pulseGlow {
    0%, 100% { 
      box-shadow: 0 0 20px rgba(48, 164, 108, 0.5),
                  0 0 40px rgba(37, 99, 235, 0.3);
    }
    50% { 
      box-shadow: 0 0 30px rgba(48, 164, 108, 0.8),
                  0 0 60px rgba(37, 99, 235, 0.5);
    }
  }
  
  @keyframes floatUp {
    0%, 100% { transform: translateY(0) rotate(0deg); }
    50% { transform: translateY(-20px) rotate(180deg); }
  }
  
  @keyframes shimmer {
    0% { background-position: -1000px 0; }
    100% { background-position: 1000px 0; }
  }
  
  @keyframes slideIn {
    from { transform: translateX(-100%); opacity: 0; }
    to { transform: translateX(0); opacity: 1; }
  }
  
  /* 3D Card Flip Animation */
  .flip-card {
    perspective: 1000px;
    width: 100%;
    height: 200px;
  }
  
  .flip-card-inner {
    position: relative;
    width: 100%;
    height: 100%;
    text-align: center;
    transition: transform 0.8s;
    transform-style: preserve-3d;
  }
  
  .flip-card:hover .flip-card-inner {
    transform: rotateY(180deg);
  }
  
  .flip-card-front, .flip-card-back {
    position: absolute;
    width: 100%;
    height: 100%;
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
    border-radius: 15px;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  
  .flip-card-front {
    background: linear-gradient(135deg, 
      rgba(48, 164, 108, 0.1), 
      rgba(37, 99, 235, 0.1));
    border: 2px solid rgba(48, 164, 108, 0.3);
  }
  
  .flip-card-back {
    background: linear-gradient(135deg, 
      rgba(37, 99, 235, 0.1), 
      rgba(124, 58, 237, 0.1));
    border: 2px solid rgba(37, 99, 235, 0.3);
    transform: rotateY(180deg);
  }
  
  /* Particle effect container */
  .particles {
    position: relative;
    width: 100%;
    height: 100px;
    overflow: hidden;
  }
  
  .particle {
    position: absolute;
    width: 5px;
    height: 5px;
    background: rgba(48, 164, 108, 0.6);
    border-radius: 50%;
    animation: floatUp 5s infinite linear;
  }
</style>

<!-- JavaScript for Interactive Elements -->
<script>
  // Typing effect
  const texts = [
    "B.Tech CSE Student 🎓",
    "AI & ML Enthusiast 🤖", 
    "Full-Stack Developer 💻",
    "Problem Solver 🔧",
    "Hackathon Lover ⚡",
    "Tech Explorer 🚀"
  ];
  
  let textIndex = 0;
  let charIndex = 0;
  let isDeleting = false;
  let typingSpeed = 100;
  
  function typeEffect() {
    const currentText = texts[textIndex];
    const displayText = isDeleting 
      ? currentText.substring(0, charIndex--)
      : currentText.substring(0, charIndex++);
    
    document.getElementById('typing-text').textContent = displayText;
    
    if (!isDeleting && charIndex === currentText.length) {
      isDeleting = true;
      typingSpeed = 1000; // Pause at end
    } else if (isDeleting && charIndex === 0) {
      isDeleting = false;
      textIndex = (textIndex + 1) % texts.length;
      typingSpeed = 200;
    }
    
    setTimeout(typeEffect, typingSpeed);
  }
  
  // Initialize typing effect
  window.onload = function() {
    typeEffect();
    
    // Create particles
    const particlesContainer = document.querySelector('.particles');
    for (let i = 0; i < 50; i++) {
      const particle = document.createElement('div');
      particle.className = 'particle';
      particle.style.left = `${Math.random() * 100}%`;
      particle.style.animationDelay = `${Math.random() * 5}s`;
      particle.style.animationDuration = `${3 + Math.random() * 7}s`;
      particle.style.background = `rgba(${Math.random() > 0.5 ? '48, 164, 108' : '37, 99, 235'}, ${0.3 + Math.random() * 0.4})`;
      particle.style.width = particle.style.height = `${2 + Math.random() * 6}px`;
      particlesContainer.appendChild(particle);
    }
  };
  
  // Interactive glow effect
  function addGlow(element) {
    element.style.animation = 'pulseGlow 1.5s infinite';
  }
  
  function removeGlow(element) {
    element.style.animation = '';
  }
</script>

---

## 🌟 **ABOUT ME** - The Liquid Developer

<div style="
  position: relative;
  padding: 40px;
  margin: 40px 0;
  background: linear-gradient(135deg,
    rgba(48, 164, 108, 0.05),
    rgba(37, 99, 235, 0.05),
    rgba(124, 58, 237, 0.05));
  border-radius: 25px;
  border: 2px solid transparent;
  border-image: linear-gradient(45deg, #30A46C, #2563eb, #7c3aed) 1;
  animation: slideIn 1s ease-out;
">

<!-- Liquid Blob Avatar -->
<div style="
  width: 180px;
  height: 180px;
  margin: 0 auto 30px;
  background: linear-gradient(135deg, #30A46C, #2563eb);
  border-radius: 50%;
  animation: morphBlob 8s infinite ease-in-out;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 3rem;
  box-shadow: 0 10px 30px rgba(48, 164, 108, 0.3),
              0 0 50px rgba(37, 99, 235, 0.2);
  position: relative;
  overflow: hidden;
  cursor: pointer;
  transition: transform 0.3s;
"
onmouseover="this.style.transform='scale(1.1)'; addGlow(this)"
onmouseout="this.style.transform='scale(1)'; removeGlow(this)"
onclick="this.style.animationPlayState='paused'; setTimeout(() => {this.style.animationPlayState='running'}, 1000)">
  <div style="
    position: absolute;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at 30% 30%, 
      rgba(255,255,255,0.3) 0%, 
      transparent 70%);
  "></div>
  SG
</div>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
  margin-top: 30px;
">

<!-- Animated Info Card -->
<div style="
  background: linear-gradient(135deg, 
    rgba(48, 164, 108, 0.1), 
    rgba(37, 99, 235, 0.1));
  padding: 25px;
  border-radius: 20px;
  border: 1px solid rgba(48, 164, 108, 0.2);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
"
onmouseover="this.style.transform='translateY(-10px)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.2)'"
onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'">

  <div style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(90deg, #30A46C, #2563eb);
    animation: shimmer 2s infinite linear;
  "></div>

  <h3 style="
    color: #30A46C;
    margin-top: 0;
    display: flex;
    align-items: center;
    gap: 10px;
  ">
    <span style="animation: bounce 2s infinite;">🎓</span>
    Education
  </h3>
  
  <p><strong>B.Tech in CSE</strong></p>
  <p>ITM Skills University, Navi Mumbai</p>
  <p style="color: #94a3b8; font-size: 0.9rem;">
    Specializing in AI & Full-Stack Development
  </p>
</div>

<!-- Current Focus Card -->
<div style="
  background: linear-gradient(135deg, 
    rgba(37, 99, 235, 0.1), 
    rgba(124, 58, 237, 0.1));
  padding: 25px;
  border-radius: 20px;
  border: 1px solid rgba(37, 99, 235, 0.2);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
"
onmouseover="this.style.transform='translateY(-10px)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.2)'"
onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'">

  <div style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(90deg, #2563eb, #7c3aed);
    animation: shimmer 2s infinite linear;
  "></div>

  <h3 style="
    color: #2563eb;
    margin-top: 0;
    display: flex;
    align-items: center;
    gap: 10px;
  ">
    <span style="animation: bounce 2s infinite 0.5s;">🚀</span>
    Current Focus
  </h3>
  
  <ul style="list-style: none; padding: 0;">
    <li style="margin: 10px 0; display: flex; align-items: center; gap: 10px;">
      <span style="
        width: 10px;
        height: 10px;
        background: #30A46C;
        border-radius: 50%;
        animation: pulseGlow 2s infinite;
      "></span>
      <strong>Generative AI:</strong> GPT Models, Diffusion Networks
    </li>
    <li style="margin: 10px 0; display: flex; align-items: center; gap: 10px;">
      <span style="
        width: 10px;
        height: 10px;
        background: #2563eb;
        border-radius: 50%;
        animation: pulseGlow 2s infinite 0.3s;
      "></span>
      <strong>C++ Algorithms:</strong> Advanced DSA & System Design
    </li>
    <li style="margin: 10px 0; display: flex; align-items: center; gap: 10px;">
      <span style="
        width: 10px;
        height: 10px;
        background: #7c3aed;
        border-radius: 50%;
        animation: pulseGlow 2s infinite 0.6s;
      "></span>
      <strong>AppSheet:</strong> No-Code Business Solutions
    </li>
  </ul>
</div>

</div>

<!-- Interactive Progress Bars -->
<div style="margin-top: 40px;">
  <h3 style="color: #7c3aed; text-align: center;">
    <span style="animation: bounce 2s infinite 1s;">📈</span>
    Skill Progression
  </h3>
  
  <div style="
    background: rgba(30, 41, 59, 0.5);
    border-radius: 20px;
    padding: 25px;
    margin-top: 20px;
  ">
    
    <!-- Animated Progress Bars -->
    <div style="margin: 15px 0;">
      <div style="display: flex; justify-content: space-between; margin-bottom: 8px;">
        <span>C++ & Algorithms</span>
        <span id="cpp-progress">0%</span>
      </div>
      <div style="
        width: 100%;
        height: 12px;
        background: rgba(48, 164, 108, 0.2);
        border-radius: 6px;
        overflow: hidden;
      ">
        <div id="cpp-bar" style="
          width: 0%;
          height: 100%;
          background: linear-gradient(90deg, #30A46C, #22c55e);
          border-radius: 6px;
          transition: width 2s ease;
        "></div>
      </div>
    </div>
    
    <div style="margin: 15px 0;">
      <div style="display: flex; justify-content: space-between; margin-bottom: 8px;">
        <span>Web Development</span>
        <span id="web-progress">0%</span>
      </div>
      <div style="
        width: 100%;
        height: 12px;
        background: rgba(37, 99, 235, 0.2);
        border-radius: 6px;
        overflow: hidden;
      ">
        <div id="web-bar" style="
          width: 0%;
          height: 100%;
          background: linear-gradient(90deg, #2563eb, #3b82f6);
          border-radius: 6px;
          transition: width 2s ease 0.2s;
        "></div>
      </div>
    </div>
    
    <div style="margin: 15px 0;">
      <div style="display: flex; justify-content: space-between; margin-bottom: 8px;">
        <span>AI & Machine Learning</span>
        <span id="ai-progress">0%</span>
      </div>
      <div style="
        width: 100%;
        height: 12px;
        background: rgba(124, 58, 237, 0.2);
        border-radius: 6px;
        overflow: hidden;
      ">
        <div id="ai-bar" style="
          width: 0%;
          height: 100%;
          background: linear-gradient(90deg, #7c3aed, #8b5cf6);
          border-radius: 6px;
          transition: width 2s ease 0.4s;
        "></div>
      </div>
    </div>
    
  </div>
</div>

</div>

<script>
  // Animate progress bars on load
  window.addEventListener('load', function() {
    setTimeout(() => {
      document.getElementById('cpp-bar').style.width = '85%';
      document.getElementById('cpp-progress').textContent = '85%';
      
      document.getElementById('web-bar').style.width = '78%';
      document.getElementById('web-progress').textContent = '78%';
      
      document.getElementById('ai-bar').style.width = '70%';
      document.getElementById('ai-progress').textContent = '70%';
    }, 1000);
  });
</script>

---

## 🏆 **GITHUB TROPHIES & STATS**

<div align="center">

<!-- Interactive Stats Grid -->
<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
  margin: 40px 0;
">

<!-- Flip Card for Stats -->
<div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <h3 style="color: #30A46C; margin: 0;">📊 Live Stats</h3>
      <p style="color: #94a3b8; margin: 10px 0;">Hover to see real-time stats</p>
      <div style="
        width: 60px;
        height: 60px;
        border: 3px solid #30A46C;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        animation: rotateCube 4s infinite linear;
        margin: 15px auto;
      ">
        🔄
      </div>
    </div>
    <div class="flip-card-back">
      <img src="https://github-readme-stats.vercel.app/api?username=Saranggole9106&show_icons=true&theme=radical&hide_border=true&count_private=true&bg_color=0d1117&title_color=30A46C&icon_color=30A46C" 
           alt="GitHub Stats" 
           style="width: 100%; border-radius: 10px;" />
    </div>
  </div>
</div>

<!-- Streak Card -->
<div style="
  background: linear-gradient(135deg, 
    rgba(48, 164, 108, 0.1), 
    rgba(37, 99, 235, 0.1));
  padding: 25px;
  border-radius: 20px;
  border: 2px solid transparent;
  border-image: linear-gradient(45deg, #30A46C, #2563eb) 1;
  animation: pulseGlow 4s infinite;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
">
  <h3 style="color: #30A46C; margin: 0 0 15px 0;">
    <span style="animation: bounce 2s infinite;">🔥</span>
    Contribution Streak
  </h3>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Saranggole9106&theme=radical&hide_border=true&background=0d1117&ring=30A46C&fire=30A46C&currStreakLabel=30A46C" 
       alt="GitHub Streak" 
       style="width: 100%; border-radius: 10px;" />
</div>

</div>

<!-- Trophies with Liquid Effect -->
<div style="
  position: relative;
  padding: 30px;
  background: linear-gradient(135deg, 
    rgba(30, 41, 59, 0.8), 
    rgba(15, 23, 42, 0.9));
  border-radius: 25px;
  margin: 30px 0;
  overflow: hidden;
">

<!-- Liquid background for trophies -->
<div style="
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: 
    radial-gradient(circle at 20% 30%, rgba(48, 164, 108, 0.1) 0%, transparent 50%),
    radial-gradient(circle at 80% 70%, rgba(37, 99, 235, 0.1) 0%, transparent 50%);
  animation: liquidFloat 30s infinite linear;
  z-index: 0;
"></div>

<div style="position: relative; z-index: 1;">
  <h3 align="center" style="color: #30A46C; margin-bottom: 20px;">
    <span style="animation: bounce 2s infinite 0.2s;">🏆</span>
    GitHub Trophies
  </h3>
  
  <img src="https://github-profile-trophy.vercel.app/?username=Saranggole9106&theme=radical&margin-w=15&margin-h=15&no-frame=true&no-bg=true" 
       alt="GitHub Trophies" 
       style="width: 100%; border-radius: 15px;"
       onerror="this.src='https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=radical&margin-w=15&margin-h=15&no-frame=true&no-bg=true'" />
</div>

</div>

<!-- Languages Graph -->
<div style="
  background: linear-gradient(135deg, 
    rgba(124, 58, 237, 0.05), 
    rgba(48, 164, 108, 0.05));
  padding: 30px;
  border-radius: 25px;
  border: 2px solid rgba(124, 58, 237, 0.2);
  margin: 30px 0;
">
  
  <h3 align="center" style="color: #7c3aed; margin-bottom: 20px;">
    <span style="animation: bounce 2s infinite 0.4s;">💬</span>
    Top Languages
  </h3>
  
  <div style="
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
  ">
    <!-- Language circles with animations -->
    <div style="
      width: 120px;
      height: 120px;
      background: conic-gradient(#30A46C 0% 40%, #2563eb 40% 70%, #7c3aed 70% 85%, #94a3b8 85% 100%);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      animation: rotateCube 10s infinite linear;
    ">
      <div style="
        width: 80px;
        height: 80px;
        background: #0f172a;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        font-weight: bold;
        color: white;
      ">
        Code
      </div>
    </div>
    
    <div style="
      background: linear-gradient(135deg, 
        rgba(48, 164, 108, 0.1), 
        rgba(37, 99, 235, 0.1));
      padding: 20px;
      border-radius: 20px;
      flex: 1;
      min-width: 250px;
    ">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Saranggole9106&layout=compact&theme=radical&hide_border=true&langs_count=8&bg_color=0d1117&title_color=30A46C" 
           alt="Top Languages" 
           style="width: 100%; border-radius: 10px;" />
    </div>
  </div>
  
  <!-- Language Tags -->
  <div style="
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    margin-top: 25px;
  ">
    <span style="
      background: linear-gradient(135deg, #30A46C, #22c55e);
      color: white;
      padding: 8px 20px;
      border-radius: 25px;
      font-size: 0.9rem;
      animation: floatUp 3s infinite ease-in-out;
      animation-delay: 0s;
    ">C++</span>
    
    <span style="
      background: linear-gradient(135deg, #2563eb, #3b82f6);
      color: white;
      padding: 8px 20px;
      border-radius: 25px;
      font-size: 0.9rem;
      animation: floatUp 3s infinite ease-in-out;
      animation-delay: 0.2s;
    ">Python</span>
    
    <span style="
      background: linear-gradient(135deg, #7c3aed, #8b5cf6);
      color: white;
      padding: 8px 20px;
      border-radius: 25px;
      font-size: 0.9rem;
      animation: floatUp 3s infinite ease-in-out;
      animation-delay: 0.4s;
    ">JavaScript</span>
    
    <span style="
      background: linear-gradient(135deg, #dc2626, #ef4444);
      color: white;
      padding: 8px 20px;
      border-radius: 25px;
      font-size: 0.9rem;
      animation: floatUp 3s infinite ease-in-out;
      animation-delay: 0.6s;
    ">HTML/CSS</span>
  </div>
</div>

</div>

<!-- Particle Effect Container -->
<div class="particles"></div>

---

## 🛠️ **TECH STACK** - Interactive 3D Showcase

<div align="center">

<!-- Tech Stack Grid with Hover Effects -->
<div style="
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
  gap: 25px;
  margin: 40px 0;
">

<!-- Each tech item with 3D effect -->
<div style="
  background: linear-gradient(135deg, 
    rgba(48, 164, 108, 0.1), 
    rgba(48, 164, 108, 0.2));
  padding: 25px 15px;
  border-radius: 20px;
  border: 2px solid rgba(48, 164, 108, 0.3);
  text-align: center;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  cursor: pointer;
"
onmouseover="
  this.style.transform='translateY(-15px) scale(1.05)';
  this.style.boxShadow='0 20px 40px rgba(48, 164, 108, 0.3)';
  this.style.borderColor='#30A46C';
"
onmouseout="
  this.style.transform='translateY(0) scale(1)';
  this.style.boxShadow='none';
  this.style.borderColor='rgba(48, 164, 108, 0.3)';
"
onclick="this.style.animation='bounce 0.5s'">
  
  <div style="
    width: 60px;
    height: 60px;
    margin: 0 auto 15px;
    background: linear-gradient(135deg, #30A46C, #22c55e);
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    color: white;
    animation: morphBlob 6s infinite ease-in-out;
  ">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" 
         width="40" 
         height="40" 
         alt="C++"
         onerror="this.style.display='none'; this.parentElement.innerHTML='C++'" />
  </div>
  
  <strong style="color: #30A46C; display: block; margin-bottom: 5px;">C++</strong>
  <small style="color: #94a3b8; font-size: 0.8rem;">Expert</small>
</div>

<div style="
  background: linear-gradient(135deg, 
    rgba(37, 99, 235, 0.1), 
    rgba(37, 99, 235, 0.2));
  padding: 25px 15px;
  border-radius: 20px;
  border: 2px solid rgba(37, 99, 235, 0.3);
  text-align: center;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  cursor: pointer;
"
onmouseover="
  this.style.transform='translateY(-15px) scale(1.05)';
  this.style.boxShadow='0 20px 40px rgba(37, 99, 235, 0.3)';
  this.style.borderColor='#2563eb';
"
onmouseout="
  this.style.transform='translateY(0) scale(1)';
  this.style.boxShadow='none';
  this.style.borderColor='rgba(37, 99, 235, 0.3)';
"
onclick="this.style.animation='bounce 0.5s'">
  
  <div style="
    width: 60px;
    height: 60px;
    margin: 0 auto 15px;
    background: linear-gradient(135deg, #2563eb, #3b82f6);
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    color: white;
    animation: morphBlob 6s infinite ease-in-out 0.2s;
  ">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" 
         width="40" 
         height="40" 
         alt="Python"
         onerror="this.style.display='none'; this.parentElement.innerHTML='Py'" />
  </div>
  
  <strong style="color: #2563eb; display: block; margin-bottom: 5px;">Python</strong>
  <small style="color: #94a3b8; font-size: 0.8rem;">Advanced</small>
</div>

<!-- Add more tech items similarly for: -->
<!-- HTML, CSS, JavaScript, Git, Figma, VS Code, etc. -->

</div>

<!-- Tech Stack Progress Visualization -->
<div style="
  background: linear-gradient(135deg, 
    rgba(30, 41, 59, 0.8), 
    rgba(15, 23, 42, 0.9));
  padding: 40px;
  border-radius: 25px;
  margin: 40px 0;
  position: relative;
  overflow: hidden;
">

<!-- Animated tech waves -->
<div style="
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 100px;
  background: linear-gradient(transparent, rgba(48, 164, 108, 0.1));
  animation: liquidFloat 15s infinite linear;
  z-index: 0;
"></div>

<div style="position: relative; z-index: 1;">
  <h3 align="center" style="color: #30A46C; margin-bottom: 30px;">
    <span style="animation: bounce 2s infinite 0.6s;">📈</span>
    Tech Stack Visualization
  </h3>
  
  <div style="
    display: flex;
    justify-content: center;
    align-items: flex-end;
    height: 200px;
    gap: 20px;
    margin-top: 30px;
  ">
    
    <!-- Animated bars for each tech -->
    <div style="
      width: 50px;
      background: linear-gradient(to top, #30A46C, #22c55e);
      border-radius: 10px 10px 0 0;
      animation: growBar 2s ease-out;
      height: 0;
      transition: height 2s ease;
      position: relative;
    "
    onmouseover="this.style.height='180px'"
    onmouseout="this.style.height='150px'">
      <div style="
        position: absolute;
        bottom: -25px;
        left: 0;
        width: 100%;
        text-align: center;
        color: #30A46C;
        font-weight: bold;
      ">C++</div>
    </div>
    
    <!-- Add more bars for other technologies -->
    
  </div>
</div>

</div>

</div>

---

## 📂 **FEATURED PROJECTS** - Interactive Showcase

<div align="center">

<!-- Project Cards Grid -->
<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 30px;
  margin: 40px 0;
">

<!-- Project 1 with 3D Flip -->
<div class="flip-card" style="height: 300px;">
  <div class="flip-card-inner">
    <div class="flip-card-front" style="
      background: linear-gradient(135deg, 
        rgba(48, 164, 108, 0.1), 
        rgba(37, 99, 235, 0.1));
    ">
      <h3 style="color: #30A46C; margin: 0 0 15px 0;">
        <span style="animation: bounce 2s infinite;">🏦</span>
        ATM Simulator
      </h3>
      <p style="color: #94a3b8; margin: 10px 0;">
        Python-based banking system with OOP
      </p>
      <div style="
        width: 80px;
        height: 80px;
        background: linear-gradient(135deg, #30A46C, #2563eb);
        border-radius: 20px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 15px auto;
        animation: morphBlob 8s infinite ease-in-out;
      ">
        🐍
      </div>
      <p style="
        color: #30A46C;
        font-size: 0.9rem;
        margin: 10px 0 0 0;
      ">
        Hover to see details →
      </p>
    </div>
    <div class="flip-card-back" style="
      background: linear-gradient(135deg, 
        rgba(37, 99, 235, 0.1), 
        rgba(124, 58, 237, 0.1));
    ">
      <h4 style="color: #2563eb; margin: 0 0 10px 0;">Features</h4>
      <ul style="
        text-align: left;
        padding-left: 20px;
        color: #94a3b8;
        font-size: 0.9rem;
        margin: 0;
      ">
        <li>PIN Verification System</li>
        <li>Balance Management</li>
        <li>Transaction History</li>
        <li>OOP Architecture</li>
      </ul>
      <div style="
        display: flex;
        gap: 10px;
        margin-top: 20px;
        justify-content: center;
      ">
        <span style="
          background: #30A46C;
          color: white;
          padding: 5px 15px;
          border-radius: 15px;
          font-size: 0.8rem;
        ">Python</span>
        <span style="
          background: #2563eb;
          color: white;
          padding: 5px 15px;
          border-radius: 15px;
          font-size: 0.8rem;
        ">OOP</span>
      </div>
      <a href="https://github.com/Saranggole9106/ATM-Simulator"
         style="
           display: inline-block;
           margin-top: 15px;
           color: #7c3aed;
           text-decoration: none;
           font-weight: bold;
           border: 2px solid #7c3aed;
           padding: 8px 20px;
           border-radius: 25px;
           transition: all 0.3s;
         "
         onmouseover="this.style.background='#7c3aed'; this.style.color='white'"
         onmouseout="this.style.background='transparent'; this.style.color='#7c3aed'">
        View Project →
      </a>
    </div>
  </div>
</div>

<!-- Add more project cards similarly -->

</div>

<!-- View All Projects Button -->
<a href="https://github.com/Saranggole9106?tab=repositories"
   style="
     display: inline-block;
     margin: 30px auto;
     padding: 15px 40px;
     background: linear-gradient(135deg, #30A46C, #2563eb, #7c3aed);
     color: white;
     text-decoration: none;
     border-radius: 30px;
     font-weight: bold;
     font-size: 1.1rem;
     animation: pulseGlow 3s infinite;
     transition: all 0.3s;
   "
   onmouseover="
     this.style.transform='scale(1.1)';
     this.style.boxShadow='0 20px 40px rgba(48, 164, 108, 0.4)';
   "
   onmouseout="
     this.style.transform='scale(1)';
     this.style.boxShadow='none';
   ">
  <span style="animation: bounce 2s infinite;">✨</span>
  Explore All Projects
  <span style="animation: bounce 2s infinite 0.5s;">🚀</span>
</a>

</div>

---

## 🌐 **CONNECT WITH ME** - Interactive Network

<div align="center">

<!-- Social Links with 3D Effect -->
<div style="
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin: 40px 0;
">

<!-- LinkedIn with advanced hover -->
<a href="https://linkedin.com/in/sarang-gole-43042831b" 
   target="_blank"
   style="
     position: relative;
     display: inline-flex;
     align-items: center;
     gap: 15px;
     padding: 20px 30px;
     background: linear-gradient(135deg, 
       rgba(10, 102, 194, 0.1), 
       rgba(10, 102, 194, 0.2));
     color: #0A66C2;
     text-decoration: none;
     border-radius: 20px;
     border: 2px solid rgba(10, 102, 194, 0.3);
     transition: all 0.3s ease;
     min-width: 200px;
     overflow: hidden;
   "
   onmouseover="
     this.style.transform='translateY(-10px)';
     this.style.boxShadow='0 20px 40px rgba(10, 102, 194, 0.3)';
     this.style.borderColor='#0A66C2';
     this.querySelector('.social-icon').style.transform='rotate(360deg) scale(1.2)';
   "
   onmouseout="
     this.style.transform='translateY(0)';
     this.style.boxShadow='none';
     this.style.borderColor='rgba(10, 102, 194, 0.3)';
     this.querySelector('.social-icon').style.transform='rotate(0) scale(1)';
   ">
   
  <div style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(45deg, 
      transparent 30%, 
      rgba(255,255,255,0.1) 50%, 
      transparent 70%);
    animation: shimmer 3s infinite linear;
    z-index: 0;
  "></div>
  
  <div class="social-icon" style="
    position: relative;
    z-index: 1;
    width: 50px;
    height: 50px;
    background: #0A66C2;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    color: white;
    transition: transform 0.5s ease;
  ">
    <i class="fab fa-linkedin-in"></i>
  </div>
  
  <div style="position: relative; z-index: 1;">
    <strong style="display: block; font-size: 1.1rem;">LinkedIn</strong>
    <small style="color: #94a3b8; font-size: 0.9rem;">Professional Network</small>
  </div>
</a>

<!-- Add similar blocks for Twitter, Instagram, YouTube, Email, etc. -->

</div>

<!-- Contact Form Simulation -->
<div style="
  background: linear-gradient(135deg, 
    rgba(48, 164, 108, 0.05), 
    rgba(37, 99, 235, 0.05));
  padding: 40px;
  border-radius: 25px;
  border: 2px solid rgba(48, 164, 108, 0.2);
  margin: 40px 0;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
">

  <h3 style="color: #30A46C; text-align: center; margin-bottom: 30px;">
    <span style="animation: bounce 2s infinite;">📧</span>
    Get In Touch
  </h3>
  
  <div style="
    display: grid;
    gap: 20px;
    margin-bottom: 30px;
  ">
    
    <div style="position: relative;">
      <input type="text" 
             placeholder="Your Name"
             style="
               width: 100%;
               padding: 15px 20px;
               background: rgba(15, 23, 42, 0.5);
               border: 2px solid rgba(48, 164, 108, 0.3);
               border-radius: 15px;
               color: white;
               font-size: 1rem;
               outline: none;
               transition: all 0.3s;
             "
             onfocus="
               this.style.borderColor='#30A46C';
               this.style.boxShadow='0 0 20px rgba(48, 164, 108, 0.3)';
             "
             onblur="
               this.style.borderColor='rgba(48, 164, 108, 0.3)';
               this.style.boxShadow='none';
             " />
    </div>
    
    <div style="position: relative;">
      <input type="email" 
             placeholder="Your Email"
             style="
               width: 100%;
               padding: 15px 20px;
               background: rgba(15, 23, 42, 0.5);
               border: 2px solid rgba(37, 99, 235, 0.3);
               border-radius: 15px;
               color: white;
               font-size: 1rem;
               outline: none;
               transition: all 0.3s;
             "
             onfocus="
               this.style.borderColor='#2563eb';
               this.style.boxShadow='0 0 20px rgba(37, 99, 235, 0.3)';
             "
             onblur="
               this.style.borderColor='rgba(37, 99, 235, 0.3)';
               this.style.boxShadow='none';
             " />
    </div>
    
    <div style="position: relative;">
      <textarea placeholder="Your Message"
                rows="4"
                style="
                  width: 100%;
                  padding: 15px 20px;
                  background: rgba(15, 23, 42, 0.5);
                  border: 2px solid rgba(124, 58, 237, 0.3);
                  border-radius: 15px;
                  color: white;
                  font-size: 1rem;
                  outline: none;
                  resize: vertical;
                  transition: all 0.3s;
                "
                onfocus="
                  this.style.borderColor='#7c3aed';
                  this.style.boxShadow='0 0 20px rgba(124, 58, 237, 0.3)';
                "
                onblur="
                  this.style.borderColor='rgba(124, 58, 237, 0.3)';
                  this.style.boxShadow='none';
                "></textarea>
    </div>
    
  </div>
  
  <button style="
    width: 100%;
    padding: 15px;
    background: linear-gradient(135deg, #30A46C, #2563eb);
    color: white;
    border: none;
    border-radius: 15px;
    font-size: 1.1rem;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s;
    position: relative;
    overflow: hidden;
  "
  onmouseover="
    this.style.transform='translateY(-3px)';
    this.style.boxShadow='0 10px 30px rgba(48, 164, 108, 0.4)';
  "
  onmouseout="
    this.style.transform='translateY(0)';
    this.style.boxShadow='none';
  "
  onclick="
    this.innerHTML='📧 Message Sent!';
    this.style.background='linear-gradient(135deg, #22c55e, #10b981)';
    setTimeout(() => {
      this.innerHTML='Send Message';
      this.style.background='linear-gradient(135deg, #30A46C, #2563eb)';
    }, 2000);
  ">
    <span style="animation: bounce 2s infinite;">🚀</span>
    Send Message
    <span style="animation: bounce 2s infinite 0.5s;">✨</span>
  </button>
  
</div>

</div>

---

## 🎮 **INTERACTIVE ELEMENTS** - Playground

<div align="center">

<!-- Interactive Code Editor Simulation -->
<div style="
  background: #0f172a;
  border-radius: 20px;
  padding: 30px;
  margin: 40px 0;
  border: 2px solid #30A46C;
  text-align: left;
  font-family: 'Courier New', monospace;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
">

  <div style="
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 1px solid #334155;
  ">
    <div style="
      width: 12px;
      height: 12px;
      background: #ef4444;
      border-radius: 50%;
    "></div>
    <div style="
      width: 12px;
      height: 12px;
      background: #f59e0b;
      border-radius: 50%;
    "></div>
    <div style="
      width: 12px;
      height: 12px;
      background: #10b981;
      border-radius: 50%;
    "></div>
    <span style="color: #94a3b8; margin-left: 20px;">profile.js</span>
  </div>
  
  <pre style="
    color: #e2e8f0;
    margin: 0;
    font-size: 0.9rem;
    line-height: 1.6;
    overflow-x: auto;
  ">
<span style="color: #c792ea;">class</span> <span style="color: #82aaff;">SarangGole</span> <span style="color: #e2e8f0;">{</span>
  <span style="color: #c792ea;">constructor</span><span style="color: #e2e8f0;">()</span> <span style="color: #e2e8f0;">{</span>
    <span style="color: #f78c6c;">this</span><span style="color: #e2e8f0;">.</span><span style="color: #82aaff;">name</span> <span style="color: #e2e8f0;">=</span> <span style="color: #c3e88d;">"Sarang Gole"</span><span style="color: #e2e8f0;">;</span>
    <span style="color: #f78c6c;">this</span><span style="color: #e2e8f0;">.</span><span style="color: #82aaff;">role</span> <span style="color: #e2e8f0;">=</span> <span style="color: #c3e88d;">"B.Tech CSE Student"</span><span style="color: #e2e8f0;">;</span>
    <span style="color: #f78c6c;">this</span><span style="color: #e2e8f0;">.</span><span style="color: #82aaff;">skills</span> <span style="color: #e2e8f0;">=</span> <span style="color: #e2e8f0;">[</span>
      <span style="color: #c3e88d;">"C++"</span><span style="color: #e2e8f0;">,</span> <span style="color: #c3e88d;">"Python"</span><span style="color: #e2e8f0;">,</span> 
      <span style="color: #c3e88d;">"Web Dev"</span><span style="color: #e2e8f0;">,</span> <span style="color: #c3e88d;">"AI/ML"</span>
    <span style="color: #e2e8f0;">];</span>
  <span style="color: #e2e8f0;">}</span>
  
  <span style="color: #82aaff;">code</span><span style="color: #e2e8f0;">()</span> <span style="color: #e2e8f0;">{</span>
    <span style="color: #c792ea;">return</span> <span style="color: #c3e88d;">"🚀 Building amazing projects!"</span><span style="color: #e2e8f0;">;</span>
  <span style="color: #e2e8f0;">}</span>
  
  <span style="color: #82aaff;">connect</span><span style="color: #e2e8f0;">()</span> <span style="color: #e2e8f0;">{</span>
    <span style="color: #c792ea;">return</span> <span style="color: #f78c6c;">this</span><span style="color: #e2e8f0;">.</span><span style="color: #82aaff;">github</span> <span style="color: #e2e8f0;">||</span> <span style="color: #c3e88d;">"Saranggole9106"</span><span style="color: #e2e8f0;">;</span>
  <span style="color: #e2e8f0;">}</span>
<span style="color: #e2e8f0;">}</span>

<span style="color: #c792ea;">const</span> <span style="color: #e2e8f0;">me</span> <span style="color: #e2e8f0;">=</span> <span style="color: #c792ea;">new</span> <span style="color: #82aaff;">SarangGole</span><span style="color: #e2e8f0;">();</span>
<span style="color: #89ddff;">console</span><span style="color: #e2e8f0;">.</span><span style="color: #82aaff;">log</span><span style="color: #e2e8f0;">(</span><span style="color: #e2e8f0;">me</span><span style="color: #e2e8f0;">.</span><span style="color: #82aaff;">code</span><span style="color: #e2e8f0;">());</span> <span style="color: #697098;">// 🚀 Building amazing projects!</span>
  </pre>
  
  <div style="
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 20px;
    padding-top: 20px;
    border-top: 1px solid #334155;
  ">
    <button style="
      background: #30A46C;
      color: white;
      border: none;
      padding: 8px 20px;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s;
    "
    onmouseover="this.style.background='#22c55e'; this.style.transform='translateY(-2px)'"
    onmouseout="this.style.background='#30A46C'; this.style.transform='translateY(0)'"
    onclick="
      const output = document.getElementById('code-output');
      output.style.display = 'block';
      output.innerHTML = '🚀 Output: Building amazing projects!<br>👤 GitHub: Saranggole9106';
      setTimeout(() => { output.style.opacity = '1'; }, 10);
    ">
      Run Code
    </button>
    
    <div id="code-output" style="
      color: #10b981;
      font-family: 'Courier New', monospace;
      opacity: 0;
      transition: opacity 0.3s;
      display: none;
    ">
    </div>
  </div>
</div>

</div>

<!-- Final Particle Effect -->
<div class="particles"></div>

---

<div align="center" style="
  padding: 50px 20px;
  margin: 40px 0;
  position: relative;
  overflow: hidden;
">

<!-- Final Liquid Background -->
<div style="
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: 
    radial-gradient(circle at 20% 80%, rgba(48, 164, 108, 0.1) 0%, transparent 50%),
    radial-gradient(circle at 80% 20%, rgba(37, 99, 235, 0.1) 0%, transparent 50%),
    radial-gradient(circle at 50% 50%, rgba(124, 58, 237, 0.1) 0%, transparent 60%);
  animation: liquidFloat 25s infinite linear;
  z-index: 0;
"></div>

<div style="position: relative; z-index: 1;">
  <h2 style="
    font-size: 2.5rem;
    background: linear-gradient(90deg, #30A46C, #2563eb, #7c3aed);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin: 0 0 20px 0;
    animation: gradientShift 6s ease infinite;
  ">
    <span style="animation: bounce 2s infinite;">🚀</span>
    Let's Build The Future Together!
    <span style="animation: bounce 2s infinite 0.5s;">✨</span>
  </h2>
  
  <p style="
    font-size: 1.2rem;
    color: #94a3b8;
    max-width: 600px;
    margin: 0 auto 30px;
    line-height: 1.6;
  ">
    Every great innovation starts with a conversation. 
    Whether it's collaborating on projects, discussing ideas, 
    or just talking tech - I'm always excited to connect!
  </p>
  
  <!-- Final CTA Buttons -->
  <div style="
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin: 30px 0;
  ">
    
    <a href="mailto:saranggole9106@gmail.com"
       style="
         display: inline-flex;
         align-items: center;
         gap: 10px;
         padding: 15px 30px;
         background: linear-gradient(135deg, #30A46C, #22c55e);
         color: white;
         text-decoration: none;
         border-radius: 30px;
         font-weight: bold;
         font-size: 1.1rem;
         transition: all 0.3s;
       "
       onmouseover="
         this.style.transform='translateY(-5px)';
         this.style.boxShadow='0 15px 30px rgba(48, 164, 108, 0.4)';
       "
       onmouseout="
         this.style.transform='translateY(0)';
         this.style.boxShadow='none';
       ">
      <span style="animation: bounce 2s infinite;">📧</span>
      Send Email
    </a>
    
    <a href="https://github.com/Saranggole9106"
       style="
         display: inline-flex;
         align-items: center;
         gap: 10px;
         padding: 15px 30px;
         background: linear-gradient(135deg, #2563eb, #3b82f6);
         color: white;
         text-decoration: none;
         border-radius: 30px;
         font-weight: bold;
         font-size: 1.1rem;
         transition: all 0.3s;
       "
       onmouseover="
         this.style.transform='translateY(-5px)';
         this.style.boxShadow='0 15px 30px rgba(37, 99, 235, 0.4)';
       "
       onmouseout="
         this.style.transform='translateY(0)';
         this.style.boxShadow='none';
       ">
      <span style="animation: bounce 2s infinite 0.2s;">⭐</span>
      Star My Profile
    </a>
    
    <a href="https://github.com/Saranggole9106?tab=repositories"
       style="
         display: inline-flex;
         align-items: center;
         gap: 10px;
         padding: 15px 30px;
         background: linear-gradient(135deg, #7c3aed, #8b5cf6);
         color: white;
         text-decoration: none;
         border-radius: 30px;
         font-weight: bold;
         font-size: 1.1rem;
         transition: all 0.3s;
       "
       onmouseover="
         this.style.transform='translateY(-5px)';
         this.style.boxShadow='0 15px 30px rgba(124, 58, 237, 0.4)';
       "
       onmouseout="
         this.style.transform='translateY(0)';
         this.style.boxShadow='none';
       ">
      <span style="animation: bounce 2s infinite 0.4s;">👨‍💻</span>
      View Projects
    </a>
    
  </div>
  
  <!-- Live Stats Footer -->
  <div style="
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
    margin-top: 40px;
    padding-top: 30px;
    border-top: 1px solid rgba(255,255,255,0.1);
  ">
    
    <div style="
      background: rgba(48, 164, 108, 0.1);
      padding: 15px 25px;
      border-radius: 15px;
      border: 1px solid rgba(48, 164, 108, 0.3);
      text-align: center;
      min-width: 150px;
    ">
      <div style="
        font-size: 2rem;
        font-weight: bold;
        color: #30A46C;
        animation: pulseGlow 3s infinite;
      " id="visitor-count">1000+</div>
      <div style="color: #94a3b8; font-size: 0.9rem;">Profile Views</div>
    </div>
    
    <div style="
      background: rgba(37, 99, 235, 0.1);
      padding: 15px 25px;
      border-radius: 15px;
      border: 1px solid rgba(37, 99, 235, 0.3);
      text-align: center;
      min-width: 150px;
    ">
      <div style="
        font-size: 2rem;
        font-weight: bold;
        color: #2563eb;
        animation: pulseGlow 3s infinite 0.5s;
      ">24/7</div>
      <div style="color: #94a3b8; font-size: 0.9rem;">Coding Spirit</div>
    </div>
    
    <div style="
      background: rgba(124, 58, 237, 0.1);
      padding: 15px 25px;
      border-radius: 15px;
      border: 1px solid rgba(124, 58, 237, 0.3);
      text-align: center;
      min-width: 150px;
    ">
      <div style="
        font-size: 2rem;
        font-weight: bold;
        color: #7c3aed;
        animation: pulseGlow 3s infinite 1s;
      ">∞</div>
      <div style="color: #94a3b8; font-size: 0.9rem;">Possibilities</div>
    </div>
    
  </div>
  
</div>

</div>

<!-- Final Message -->
<div align="center" style="
  padding: 30px;
  background: linear-gradient(135deg, 
    rgba(15, 23, 42, 0.9), 
    rgba(30, 41, 59, 0.9));
  border-radius: 20px;
  margin: 40px 0;
  border: 2px solid transparent;
  border-image: linear-gradient(45deg, #30A46C, #2563eb, #7c3aed) 1;
">

  <p style="
    font-size: 1.1rem;
    color: #e2e8f0;
    margin: 0;
    line-height: 1.8;
  ">
    <span style="
      font-size: 1.5rem;
      animation: bounce 2s infinite;
      display: inline-block;
      margin: 0 10px;
    ">✨</span>
    
    <strong>Thank you for visiting my profile!</strong> 
    
    <span style="
      font-size: 1.5rem;
      animation: bounce 2s infinite 0.5s;
      display: inline-block;
      margin: 0 10px;
    ">🚀</span>
    
    <br><br>
    
    Remember: <span style="color: #30A46C;">"The best way to predict the future is to create it."</span>
    
    <br><br>
    
    Let's connect and build something amazing together! 
    
    <span style="
      font-size: 1.5rem;
      animation: bounce 2s infinite 1s;
      display: inline-block;
      margin: 0 10px;
    ">💻</span>
  </p>
  
  <!-- Final Signature -->
  <div style="
    margin-top: 30px;
    padding-top: 20px;
    border-top: 1px solid rgba(255,255,255,0.1);
  ">
    <p style="
      font-family: 'Brush Script MT', cursive;
      font-size: 1.8rem;
      color: #30A46C;
      margin: 0;
    ">
      With code and passion,
    </p>
    <p style="
      font-size: 2rem;
      font-weight: bold;
      background: linear-gradient(90deg, #30A46C, #2563eb);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin: 5px 0 0 0;
    ">
      Sarang Gole
    </p>
  </div>
  
</div>

<!-- Final Animation -->
<div style="
  width: 100%;
  height: 4px;
  background: linear-gradient(90deg, 
    #30A46C, #2563eb, #7c3aed, #30A46C);
  background-size: 300% 100%;
  animation: gradientShift 3s infinite linear;
  border-radius: 2px;
  margin-top: 20px;
"></div>

<!-- Hidden Easter Egg -->
<div style="
  opacity: 0.01;
  position: absolute;
  pointer-events: none;
">
  <!-- Easter Egg: Try clicking the 3D cube multiple times! -->
  <!-- You found the secret message! 🎉 -->
  <!-- Contact me: saranggole9106@gmail.com -->
  <!-- Made with ❤️ and JavaScript -->
</div>

<!-- Add Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<script>
  // Initialize animations
  document.addEventListener('DOMContentLoaded', function() {
    // Start typing effect
    const texts = [
      "B.Tech CSE Student 🎓",
      "AI & ML Enthusiast 🤖", 
      "Full-Stack Developer 💻",
      "Problem Solver 🔧",
      "Hackathon Lover ⚡",
      "Tech Explorer 🚀"
    ];
    
    let textIndex = 0;
    let charIndex = 0;
    let isDeleting = false;
    let typingSpeed = 100;
    
    function typeEffect() {
      const currentText = texts[textIndex];
      const displayText = isDeleting 
        ? currentText.substring(0, charIndex--)
        : currentText.substring(0, charIndex++);
      
      document.getElementById('typing-text').textContent = displayText;
      
      if (!isDeleting && charIndex === currentText.length) {
        isDeleting = true;
        typingSpeed = 1000;
      } else if (isDeleting && charIndex === 0) {
        isDeleting = false;
        textIndex = (textIndex + 1) % texts.length;
        typingSpeed = 200;
      }
      
      setTimeout(typeEffect, typingSpeed);
    }
    
    typeEffect();
    
    // Animate progress bars
    setTimeout(() => {
      document.getElementById('cpp-bar').style.width = '85%';
      document.getElementById('cpp-progress').textContent = '85%';
      
      document.getElementById('web-bar').style.width = '78%';
      document.getElementById('web-progress').textContent = '78%';
      
      document.getElementById('ai-bar').style.width = '70%';
      document.getElementById('ai-progress').textContent = '70%';
    }, 1000);
    
    // Create particles
    const particlesContainers = document.querySelectorAll('.particles');
    particlesContainers.forEach(container => {
      for (let i = 0; i < 30; i++) {
        const particle = document.createElement('div');
        particle.className = 'particle';
        particle.style.left = `${Math.random() * 100}%`;
        particle.style.animationDelay = `${Math.random() * 5}s`;
        particle.style.animationDuration = `${3 + Math.random() * 7}s`;
        particle.style.background = `rgba(${Math.random() > 0.5 ? '48, 164, 108' : '37, 99, 235'}, ${0.3 + Math.random() * 0.4})`;
        particle.style.width = particle.style.height = `${2 + Math.random() * 6}px`;
        container.appendChild(particle);
      }
    });
    
    // Update visitor count (simulated)
    setInterval(() => {
      const countElement = document.getElementById('visitor-count');
      const currentCount = parseInt(countElement.textContent);
      if (currentCount < 1500) {
        countElement.textContent = (currentCount + Math.floor(Math.random() * 5)) + '+';
      }
    }, 5000);
  });
  
  // Easter egg: Cube rotation on click
  document.addEventListener('click', function(e) {
    if (e.target.closest('[style*="rotateCube"]')) {
      const cube = e.target.closest('[style*="rotateCube"]');
      let rotations = parseInt(cube.getAttribute('data-rotations') || '0');
      rotations++;
      cube.setAttribute('data-rotations', rotations);
      
      if (rotations === 5) {
        alert('🎉 Secret Unlocked! You found the Easter Egg!\n\n"Great developers are not born, they\'re coded!"\n\n- Sarang Gole');
        cube.setAttribute('data-rotations', '0');
      }
    }
  });
</script>
