<!doctype html>
<html> 
 <head>
  <title>JAHID HASSAN RINKQ</title> 
  <meta name="language" content="English"> 
  <meta name="theme-color" content="#000"> 
  <meta name="viewport" content="width=device-width"> 
  <meta name="title" content="BANGLADESH CYBER 2.0 BEST HACKING TEAM"> 
  <meta name="description" content="we are BANGLADESH CYBER 2.0. WE ARE NOT VILLAINE BRO.."> 
  <meta property="og:image" content="https://i.postimg.cc/3wPjVf2M/bdc2-0.png"> 
  <link rel="icon" type="image" href="https://i.postimg.cc/3wPjVf2M/bdc2-0.png"> 
  <style>
    @import url("https://fonts.googleapis.com/css?family=Raleway");

    :root {
      --glow-color: hsl(186 100% 69%);
      --neon-color: hsl(50 100% 50%);
    }

    *,
    *::before,
    *::after {
      box-sizing: border-box;
    }

    html,
    body {
      height: 100%;
      width: 100%;
      overflow: hidden;
      margin: 0;
      padding: 0;
      background: black;
    }

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: black;
      flex-direction: column;
      position: relative;
      z-index: 1;
    }

    canvas {
      position: absolute;
      top: 0;
      left: 0;
      z-index: 0;
    }

    .icon {
      width: 150px;
      height: 150px;
      margin-top: 20px;
      border-radius: 50%;
      object-fit: cover;
      z-index: 1;
    }

    .button-container {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      z-index: 1;
    }

    .glowing-btn {
      position: relative;
      color: var(--glow-color);
      cursor: pointer;
      padding: 0.25em 0.75em;
      margin: 10px 0;
      border: 0.1em solid var(--glow-color);
      border-radius: 0.35em;
      background: none;
      perspective: 2em;
      font-family: "Raleway", sans-serif;
      font-size: 1.5em;
      font-weight: 900;
      letter-spacing: 0.75em;
      z-index: 1;

      -webkit-box-shadow: inset 0px 0px 0.4em 0px var(--glow-color),
        0px 0px 0.4em 0px var(--glow-color);
      -moz-box-shadow: inset 0px 0px 0.4em 0px var(--glow-color),
        0px 0px 0.4em 0px var(--glow-color);
      box-shadow: inset 0px 0px 0.4em 0px var(--glow-color),
        0px 0px 0.4em 0px var(--glow-color);
      animation: border-flicker 2s linear infinite;
    }

    .glowing-txt {
      float: left;
      margin-right: -0.6em;
      -webkit-text-shadow: 0 0 0.1em hsl(0 0% 100% / 0.3),
        0 0 0.35em var(--glow-color);
      -moz-text-shadow: 0 0 0.1em hsl(0 0% 100% / 0.3),
        0 0 0.35em var(--glow-color);
      text-shadow: 0 0 0.1em hsl(0 0% 100% / 0.3), 0 0 0.35em var(--glow-color);
      animation: text-flicker 3s linear infinite;
    }

    .faulty-letter {
      opacity: 0.5;
      animation: faulty-flicker 2s linear infinite;
    }

    .glowing-btn::before {
      content: "";
      position: absolute;
      top: 0;
      bottom: 0;
      left: 0;
      right: 0;
      opacity: 0.7;
      filter: blur(0.8em);
      transform: translateY(120%) rotateX(95deg) scale(1, 0.35);
      background: var(--glow-color);
      pointer-events: none;
    }

    .glowing-btn::after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      opacity: 0;
      z-index: -1;
      background-color: var(--glow-color);
      box-shadow: 0 0 1.5em 0.15em var(--glow-color);
      transition: opacity 100ms linear;
    }

    .glowing-btn:hover {
      color: rgba(0, 0, 0, 0.8);
      text-shadow: none;
      animation: none;
    }

    .glowing-btn:hover .glowing-txt {
      animation: none;
    }

    .glowing-btn:hover .faulty-letter {
      animation: none;
      text-shadow: none;
      opacity: 1;
    }

    .glowing-btn:hover:before {
      filter: blur(1em);
      opacity: 1;
    }

    .glowing-btn:hover:after {
      opacity: 1;
    }

    @keyframes faulty-flicker {
      0% {
        opacity: 0.1;
      }
      2% {
        opacity: 0.1;
      }
      4% {
        opacity: 0.5;
      }
      19% {
        opacity: 0.5;
      }
      21% {
        opacity: 0.1;
      }
      23% {
        opacity: 1;
      }
      80% {
        opacity: 0.5;
      }
      83% {
        opacity: 0.4;
      }

      87% {
        opacity: 1;
      }
    }

    @keyframes text-flicker {
      0% {
        opacity: 0.1;
      }

      2% {
        opacity: 1;
      }

      8% {
        opacity: 0.1;
      }

      9% {
        opacity: 1;
      }

      12% {
        opacity: 0.1;
      }
      20% {
        opacity: 1;
      }
      25% {
        opacity: 0.3;
      }
      30% {
        opacity: 1;
      }

      70% {
        opacity: 0.7;
      }
      72% {
        opacity: 0.2;
      }

      77% {
        opacity: 0.9;
      }
      100% {
        opacity: 0.9;
      }
    }

    @keyframes border-flicker {
      0% {
        opacity: 0.1;
      }
      2% {
        opacity: 1;
      }
      4% {
        opacity: 0.1;
      }

      8% {
        opacity: 1;
      }
      70% {
        opacity: 0.7;
      }
      100% {
        opacity: 1;
      }
    }

    .neon-text {
      color: var(--neon-color);
      text-shadow: 0 0 5px var(--neon-color), 0 0 10px var(--neon-color), 0 0 20px var(--neon-color);
      font-size: 2em;
      margin: 20px 0;
      animation: neon-blink 1s infinite;
      z-index: 1;
    }

    @keyframes neon-blink {
      0%, 100% {
        opacity: 1;
      }
      50% {
        opacity: 0.1;
      }
    }

    @media only screen and (max-width: 600px) {
      .glowing-btn {
        font-size: 1em;
      }
      .neon-text {
        font-size: 1.2em;
      }
    }
  </style> 
 </head> 
 <body> 
  <canvas id="matrix"></canvas>

  <img src="https://i.postimg.cc/VLryqmpy/ic-licensed.gif" class="icon" alt="Icon Image"> 

  <div class="neon-text">YOU HAVE BEEN HACKED BY @rinkq2</div>

  <div class="button-container"> 
    <a href="https://www.facebook.com/rinkq2"> 
      <button class="glowing-btn"><span class="glowing-txt">GITHUB</span></button> 
    </a> 
    <a href="https://www.facebook.com/rinkq2?mibextid=ZbWKwL"> 
      <button class="glowing-btn"><span class="glowing-txt">FB<span class="faulty-letter">PA</span>GE</span></button> 
    </a> 
    <a href="https://www.facebook.com/rinkq2?mibextid=ZbWKwL"><span class="glowing-txt">FB GROUP</span></button> 
    </a> 
    <a href="https://t.me/rinkq1"> 
      <button class="glowing-btn"><span class="glowing-txt">TELEGRAM</span></button> 
    </a> 
    <a href="https://t.me/rinkq1"> 
      <button class="glowing-btn"><span class="glowing-txt">TOOL STORE</span></button> 
    </a> 
    <a href="https://t.me/rink1"> 
      <button class="glowing-btn"><span class="glowing-txt">ABOUT US</span></button> 
    </a> 
  </div> 

  <script>
    const canvas = document.getElementById('matrix');
    const ctx = canvas.getContext('2d');

    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;

    const letters = 'アァカサタナハマヤャラワン1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ';
    const fontSize = 16;
    const columns = canvas.width / fontSize;

    const drops = Array.from({ length: columns }, () => 1);

    function draw() {
      ctx.fillStyle = 'rgba(0, 0, 0, 0.05)';
      ctx.fillRect(0, 0, canvas.width, canvas.height);

      ctx.fillStyle = '#0F0';
      ctx.font = `${fontSize}px monospace`;

      drops.forEach((y, x) => {
        const text = letters[Math.floor(Math.random() * letters.length)];
        ctx.fillText(text, x * fontSize, y * fontSize);

        if (y * fontSize > canvas.height && Math.random() > 0.975) {
          drops[x] = 0;
        }
        drops[x]++;
      });
    }

    setInterval(draw, 30);

    window.addEventListener('resize', () => {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    });
  </script>  
 </body>
</html>