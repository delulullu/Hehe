# Hehe 
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>For You - May 4th</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #f8f0ff, #ffe6e6);
      color: #333;
      text-align: center;
      overflow-x: hidden;
    }
    .section {
      padding: 60px 20px;
    }
    h1, h2 {
      margin: 0 0 20px;
    }
    .blossoms {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: -1;
    }
    .quote {
      font-style: italic;
      margin-top: 40px;
      color: #666;
    }
    footer {
      margin-top: 60px;
      font-size: 0.9em;
      color: #888;
    }
  </style>
</head>
<body>
  <canvas class="blossoms"></canvas>  <div class="section">
    <h1>Hey, beautiful.</h1>
    <p>Just a little something for you...</p>
  </div>  <div class="section">
    <h2>May 4th is coming.</h2>
    <p>I believe in you — more than anything. You're smart, you're capable, and you've got this.</p>
    <p>But even if it doesn’t go the way you hope... it's okay. There's always another chance.</p>
    <p>What matters most is *you*. And I love you, no matter what.</p>
  </div>  <div class="section quote">
    <p>“Stars can’t shine without darkness.”</p>
  </div>  <footer>
    With all my love, always.
  </footer>  <script>
    // Simple falling blossoms animation
    const canvas = document.querySelector('.blossoms');
    const ctx = canvas.getContext('2d');
    let petals = [];

    function resize() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    }

    function createPetals() {
      petals = Array.from({ length: 30 }, () => ({
        x: Math.random() * canvas.width,
        y: Math.random() * canvas.height,
        r: Math.random() * 3 + 2,
        d: Math.random() * 2 + 1
      }));
    }

    function drawPetals() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      ctx.fillStyle = 'rgba(255, 182, 193, 0.8)';
      ctx.beginPath();
      petals.forEach(p => {
        ctx.moveTo(p.x, p.y);
        ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2, true);
      });
      ctx.fill();
      updatePetals();
    }

    function updatePetals() {
      petals.forEach(p => {
        p.y += p.d;
        if (p.y > canvas.height) {
          p.y = 0;
          p.x = Math.random() * canvas.width;
        }
      });
    }

    window.addEventListener('resize', resize);
    resize();
    createPetals();
    setInterval(drawPetals, 33);
  </script></body>
</html><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>For You - May 4th</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #f8f0ff, #ffe6e6);
      color: #333;
      text-align: center;
      overflow-x: hidden;
    }
    .section {
      padding: 60px 20px;
    }
    h1, h2 {
      margin: 0 0 20px;
    }
    .blossoms {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: -1;
    }
    .quote {
      font-style: italic;
      margin-top: 40px;
      color: #666;
    }
    footer {
      margin-top: 60px;
      font-size: 0.9em;
      color: #888;
    }
  </style>
</head>
<body>
  <canvas class="blossoms"></canvas>  <div class="section">
    <h1>Hey, beautiful.</h1>
    <p>Just a little something for you...</p>
  </div>  <div class="section">
    <h2>May 4th is coming.</h2>
    <p>I believe in you — more than anything. You're smart, you're capable, and you've got this.</p>
    <p>But even if it doesn’t go the way you hope... it's okay. There's always another chance.</p>
    <p>What matters most is *you*. And I love you, no matter what.</p>
  </div>  <div class="section quote">
    <p>“Stars can’t shine without darkness.”</p>
  </div>  <footer>
    With all my love, always.
  </footer>  <script>
    // Simple falling blossoms animation
    const canvas = document.querySelector('.blossoms');
    const ctx = canvas.getContext('2d');
    let petals = [];

    function resize() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    }

    function createPetals() {
      petals = Array.from({ length: 30 }, () => ({
        x: Math.random() * canvas.width,
        y: Math.random() * canvas.height,
        r: Math.random() * 3 + 2,
        d: Math.random() * 2 + 1
      }));
    }

    function drawPetals() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      ctx.fillStyle = 'rgba(255, 182, 193, 0.8)';
      ctx.beginPath();
      petals.forEach(p => {
        ctx.moveTo(p.x, p.y);
        ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2, true);
      });
      ctx.fill();
      updatePetals();
    }

    function updatePetals() {
      petals.forEach(p => {
        p.y += p.d;
        if (p.y > canvas.height) {
          p.y = 0;
          p.x = Math.random() * canvas.width;
        }
      });
    }

    window.addEventListener('resize', resize);
    resize();
    createPetals();
    setInterval(drawPetals, 33);
  </script></body>
</html>
