
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: linear-gradient(to top, #ffe6f0, #e6f7ff);
      font-family: 'Comic Sans MS', cursive;
      overflow: hidden;
    }

    h1 {
      font-size: 3rem;
      color: #ff3399;
      text-shadow: 0 0 10px #ff99cc, 0 0 20px #ff66b2;
      animation: fadeOut 3s ease forwards;
      animation-delay: 3s;
    }

    @keyframes fadeOut {
      to { opacity: 0; }
    }

    .cake {
      display: none;
      font-size: 5rem;
      animation: fadeIn 2s ease forwards;
      margin-bottom: 20px;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Birthday Note (like a card opening) */
    .note {
      display: none;
      background: #fff0f5;
      color: #ff4da6;
      padding: 20px;
      border: 2px solid #ff99cc;
      border-radius: 15px;
      font-size: 1.3rem;
      text-align: center;
      width: 0;
      overflow: hidden;
      white-space: nowrap;
      animation: openCard 2s ease forwards;
    }

    @keyframes openCard {
      from { width: 0; opacity: 0; }
      to { width: 350px; opacity: 1; }
    }
  </style>
</head>
<body>
  <h1 id="title">🎉 Happiest Birthday Baee!🌷 🎉</h1>
  <div class="cake" id="cake">🎂</div>
  <div class="note" id="note">
    Hey my love 🐶💖<br>
    You make my life brighter than any candle 🕯<br>
    (hahaha chessy right?)<br>
    You make me feel Happyy nd Loved❤🎀<br>
    and On your special day😋...<br>
    I just want u to know-✨💕<br>
    I'm so happy to be with u,U r the BESTT❤<br>
    Don't ever stop being cheesy🎀<br>
    U r hardworking,Loving,caring🙃❤<br>
    Proud of u 🖤 nd also-<br>
    💌THANK U SOO MUCH (eeeh)💌<br>
    I trust u..Love youu🤍🖤<br>
    
  </div>

  <script>
    setTimeout(() => {
      document.getElementById('cake').style.display = 'block';
    }, 4000); // Cake shows after 4 sec

    setTimeout(() => {
      document.getElementById('note').style.display = 'block';
    }, 6000); // Card opens after 6 sec
  </script>
</body>
</html>
