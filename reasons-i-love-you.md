<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>100 Reasons I Love You 💖</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(circle at center, #1b2735 0%, #090a0f 100%);
      color: #ffffff;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow-x: hidden;
    }

    #galaxyCanvas {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 1;
      pointer-events: none;
    }

    .container {
      position: relative;
      z-index: 2;
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(15px);
      -webkit-backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 24px;
      padding: 30px 20px;
      max-width: 440px;
      width: 88%;
      margin: 40px auto;
      text-align: left;
      box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
      animation: fadeIn 1.5s ease-in-out;
    }

    h1 {
      text-align: center;
      color: #ff9a9e;
      font-size: 1.8rem;
      text-shadow: 0 0 10px rgba(255, 154, 158, 0.5);
      margin-bottom: 25px;
    }

    ol {
      padding-left: 20px;
      margin: 0;
    }

    li {
      padding: 10px 0;
      font-size: 0.95rem;
      line-height: 1.4;
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      color: #e0e6ed;
    }

    li::marker {
      color: #ff9a9e;
      font-weight: bold;
    }

    .next-btn {
      display: block;
      margin-top: 30px;
      text-align: center;
      padding: 14px 20px;
      background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%);
      color: #1b2735;
      font-weight: bold;
      text-decoration: none;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(161, 196, 253, 0.5);
      font-size: 1rem;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <canvas id="galaxyCanvas"></canvas>

  <div class="container">
    <h1>100 Reasons I Love You 🤍</h1>

    <ol>
      <li>You make distance feel smaller than it is.</li>
      <li>You make ordinary days worth looking forward to.</li>
      <li>You make my phone feel like my favorite place.</li>
      <li>You're the first person I want to tell everything to.</li>
      <li>You taught me that someone can feel like home without living nearby.</li>
      <li>I love how your laugh lives in my head even when you're offline.</li>
      <li>I love that I never have to pretend around you.</li>
      <li>You make silence feel comfortable.</li>
      <li>You're my favorite notification.</li>
      <li>You somehow make "good morning" feel special.</li>
      <li>I love how your heart stays soft even after hard days.</li>
      <li>I love the little things you probably don't even notice about yourself.</li>
      <li>You make waiting worth it.</li>
      <li>I love that every conversation with you feels different.</li>
      <li>You turned my screen into somewhere I actually want to be.</li>
      <li>You made time zones my biggest enemy. 😭</li>
      <li>I love that you let me be part of your world.</li>
      <li>I love hearing about your random thoughts.</li>
      <li>I love that you trust me with your feelings.</li>
      <li>You make "I miss you" mean something beautiful.</li>
      <li>I love how you care so deeply.</li>
      <li>You remind me that kindness still exists.</li>
      <li>I love how your happiness becomes mine.</li>
      <li>I love how your excitement is contagious.</li>
      <li>You make every "I love you" feel brand new.</li>
      <li>You make me want to become a better person.</li>
      <li>I love the way you make my heart slow down.</li>
      <li>You never feel like just another person.</li>
      <li>I love that you're my safe place.</li>
      <li>I love imagining our future together.</li>
      <li>I love your sleepy texts.</li>
      <li>I love your random messages.</li>
      <li>I love your voice.</li>
      <li>I love your honesty.</li>
      <li>I love how real you are.</li>
      <li>I love how much you mean to me without even trying.</li>
      <li>You make ordinary conversations unforgettable.</li>
      <li>I love how you always cross my mind.</li>
      <li>I love how you became my favorite habit.</li>
      <li>I love every memory we've made.</li>
      <li>You make me smile at my phone like an idiot.</li>
      <li>I love that I never get tired of talking to you.</li>
      <li>I love that your name makes me smile.</li>
      <li>You make waiting for replies exciting.</li>
      <li>I love that every call feels too short.</li>
      <li>You make forever sound possible.</li>
      <li>I love that you understand me.</li>
      <li>I love your heart.</li>
      <li>I love your mind.</li>
      <li>I love your soul.</li>
      <li>I love the way you care about people.</li>
      <li>I love that you're stronger than you think.</li>
      <li>I love how you keep going.</li>
      <li>I love every dream you tell me.</li>
      <li>I love hearing about your day.</li>
      <li>I love sharing mine with you.</li>
      <li>I love our little inside jokes.</li>
      <li>I love that you can cheer me up without trying.</li>
      <li>I love that you're my peace.</li>
      <li>I love that you exist.</li>
      <li>I love every version of you.</li>
      <li>I love the happy you.</li>
      <li>I love the tired you.</li>
      <li>I love the overthinking you.</li>
      <li>I love the quiet you.</li>
      <li>I love the goofy you.</li>
      <li>I love the sleepy you.</li>
      <li>I love the emotional you.</li>
      <li>I love the confident you.</li>
      <li>I love all the parts you think aren't lovable.</li>
      <li>You make forever feel too short.</li>
      <li>I love that you're worth every mile.</li>
      <li>I love dreaming about meeting you.</li>
      <li>I love thinking about hugging you.</li>
      <li>I love imagining our first real date.</li>
      <li>I love imagining our last goodbye becoming our last goodbye ever.</li>
      <li>I love the future because you're in it.</li>
      <li>I love choosing you every day.</li>
      <li>I love how easy it is to love you.</li>
      <li>I love how impossible it would be to replace you.</li>
      <li>I love the way you changed my life.</li>
      <li>I love that I found you.</li>
      <li>I love that you found me.</li>
      <li>I love every late-night conversation.</li>
      <li>I love every good morning.</li>
      <li>I love every good night.</li>
      <li>I love every memory still waiting to happen.</li>
      <li>I love every version of "us."</li>
      <li>I love our story.</li>
      <li>I love our beginning.</li>
      <li>If I could relive one chapter, I'd choose the day we met.</li>
      <li>You're my favorite coincidence.</li>
      <li>You're my favorite chapter.</li>
      <li>You're my favorite future.</li>
      <li>You're my favorite person.</li>
      <li>If my heart had a homepage, it'd have your name on it.</li>
      <li>Every version of tomorrow is better if you're there.</li>
      <li>No algorithm could calculate how much you mean to me.</li>
      <li>If love were open source, you'd still be my favorite commit.</li>
      <li>Out of the billions of people on Earth, my heart somehow found the exact person it wanted... you. 🤍</li>
    </ol>

    <a href="README.md" class="next-btn">Next Surprise ✨</a>
  </div>

  <script>
    // Starfield Background
    const canvas = document.getElementById('galaxyCanvas');
    const ctx = canvas.getContext('2d');
    let stars = [];
    const numStars = 150;
    let mouse = { x: null, y: null, radius: 100 };

    function resizeCanvas() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    }
    resizeCanvas();
    window.addEventListener('resize', resizeCanvas);

    function updateCoords(e) {
      if (e.touches) {
        mouse.x = e.touches[0].clientX;
        mouse.y = e.touches[0].clientY;
      } else {
        mouse.x = e.clientX;
        mouse.y = e.clientY;
      }
    }

    window.addEventListener('mousemove', updateCoords);
    window.addEventListener('touchstart', updateCoords);
    window.addEventListener('touchmove', updateCoords);

    class Star {
      constructor() {
        this.x = Math.random() * canvas.width;
        this.y = Math.random() * canvas.height;
        this.baseX = this.x;
        this.baseY = this.y;
        this.size = Math.random() * 2 + 0.5;
        this.density = (Math.random() * 20) + 1;
      }

      draw() {
        ctx.fillStyle = '#ffffff';
        ctx.beginPath();
        ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
        ctx.fill();
      }

      update() {
        if (mouse.x !== null && mouse.y !== null) {
          let dx = mouse.x - this.x;
          let dy = mouse.y - this.y;
          let distance = Math.sqrt(dx * dx + dy * dy);
          if (distance < mouse.radius) {
            let force = (mouse.radius - distance) / mouse.radius;
            this.x -= (dx / distance) * force * this.density;
            this.y -= (dy / distance) * force * this.density;
          } else {
            if (this.x !== this.baseX) this.x -= (this.x - this.baseX) / 10;
            if (this.y !== this.baseY) this.y -= (this.y - this.baseY) / 10;
          }
        }
      }
    }

    function init() {
      stars = [];
      for (let i = 0; i < numStars; i++) stars.push(new Star());
    }

    function animate() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      for (let i = 0; i < stars.length; i++) {
        stars[i].draw();
        stars[i].update();
      }
      requestAnimationFrame(animate);
    }

    init();
    animate();

    // Tap Hearts
    window.addEventListener('click', (e) => {
      const heart = document.createElement('div');
      heart.innerHTML = '💖';
      heart.style.position = 'fixed';
      heart.style.left = `${e.clientX}px`;
      heart.style.top = `${e.clientY}px`;
      heart.style.fontSize = '24px';
      heart.style.pointerEvents = 'none';
      heart.style.transform = 'translate(-50%, -50%)';
      heart.style.transition = 'all 1s ease-out';
      heart.style.zIndex = '9999';
      document.body.appendChild(heart);
      setTimeout(() => { heart.style.top = `${e.clientY - 60}px`; heart.style.opacity = '0'; }, 50);
      setTimeout(() => heart.remove(), 1000);
    });
  </script>
</body>
</html>
