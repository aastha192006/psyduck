<!DOCTYPE html>
<html>
<head>
  <title>Happy Birthday </title>
  <style>
    body {
      background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
      text-align: center;
      min-height: 100vh;
      overflow: hidden;
      margin: 0;
    }
    .wish {
      font-size: 1.8em;
      margin-top: 100px;
      color: #ff4081;
      letter-spacing: 2px;
      animation: pop 1.5s ease-in-out;
    }
    @keyframes pop {
      0% { transform: scale(0.2); opacity: 0; }
      80% { transform: scale(1.2); opacity: 1;}
      100% { transform: scale(1); }
    }
    .balloon {
      position: absolute;
      bottom: -150px;
      width: 70px;
      height: 90px;
      background: radial-gradient(circle at 65% 20%, #ffadad, #ff6392 70%);
      border-radius: 60% 60% 60% 60% / 80% 80% 70% 70%;
      animation: float 6s infinite linear;
      z-index: 1;
    }
    .balloon:nth-child(2) {
      left: 20vw;
      background: radial-gradient(circle at 60% 20%, #ffd6a5, #fdffb6 70%);
      animation-duration: 8s;
      animation-delay: 2s;
    }
    .balloon:nth-child(3) {
      left: 60vw;
      background: radial-gradient(circle at 70% 20%, #caffbf, #9bf6ff 70%);
      animation-duration: 7s;
      animation-delay: 1s;
    }
    .balloon:nth-child(4) {
      left: 80vw;
      background: radial-gradient(circle at 65% 20%, #bdb2ff, #a0c4ff 70%);
      animation-duration: 9s;
      animation-delay: 3s;
    }
    .balloon::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: -30px;
      width: 2px;
      height: 40px;
      background: #888;
      transform: translateX(-50%);
    }
    @keyframes float {
      0% { bottom: -150px; opacity: 0.8; }
      10% { opacity: 1;}
      90% { opacity: 1;}
      100% { bottom: 100vh; opacity: 0;}
    }
    .msg {
      font-size: 1em;
      color: black;
      margin-top: 40px;
      animation: fadeIn 2s 1.5s both;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="balloon" style="left:10vw;"></div>
  <div class="balloon"></div>
  <div class="balloon"></div>
  <div class="balloon"></div>
  <div class="wish">🎉 Happy Birthday! 🎉</div>
  <div class="msg">
    ANSHU-MANN 🦸‍♂️🥳🥳🥳🥳<br>
    Wishing you a day filled with laughter, joy, and sweet surprises.<br>
    
    
    
    
    🌸Even though we may not always be  in the same place , I want you to know that <br>
    our friendship means a lot to me.🌸<br>
    I want to see u achieve everything you've ever told me , even if I'm not there. <br>
    Distance may separate us, but it can never diminish the bond we share.<br>
    I cherish the moments we've spent together and look forward to creating <br>
    many more memories in the future , no matter where life takes us.<br>
    
    
    
    <br>
    <strong>Happy Birthday once again!🐣</strong><br>
    <br>
    <strong>With love  ,</strong><br>
    <strong>Aastha 🐼 </strong><br>
    <br>
    
    
    <strong>PS:</strong> <br>
    <strong>-[chotu sa project h prr boht mehnat lagi h 😅]-</strong><br>
    <br>
    <strong>✨ Hope you like it!✨</strong>
  </div>

</body>
</html>
