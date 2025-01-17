<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I Promise to Work Hard</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(45deg, #ff7f50, #87cefa, #dda0dd, #ff6347);
      background-size: 400% 400%;
      animation: gradient 8s ease infinite;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: #333;
      overflow: hidden;
      position: relative;
      flex-direction: column;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .marquee {
      width: 100%;
      background-color: #f39c12;
      color: white;
      padding: 10px;
      font-size: 1.5em;
      text-align: center;
      font-weight: bold;
      margin: 20px 0;
      white-space: nowrap;
      overflow: hidden;
    }

    .marquee span {
      display: inline-block;
      padding-left: 100%;
      animation: marquee 15s linear infinite;
    }

    @keyframes marquee {
      0% {
        transform: translateX(100%);
      }
      100% {
        transform: translateX(-100%);
      }
    }

    .letter-container {
      background-color: #fff;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0px 6px 20px rgba(0, 0, 0, 0.15);
      width: 75%;
      max-width: 800px;
      text-align: center;
      position: relative;
      z-index: 2;
      animation: fadeIn 2s ease-out;
      border: 4px solid #f39c12;
      box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.1);
    }

    h1 {
      color: #27ae60;
      font-size: 3em;
      margin-bottom: 20px;
      font-family: 'Georgia', serif;
      text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.2);
      animation: breathe 3s infinite ease-in-out;
    }

    @keyframes breathe {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.1); }
    }

    p {
      font-size: 1.3em;
      line-height: 1.8;
      margin-bottom: 20px;
      color: #333;
    }

    .highlight {
      color: #f39c12;
      font-weight: bold;
    }

    .signature {
      margin-top: 40px;
      font-size: 1.8em;
      font-weight: bold;
      color: #2c3e50;
    }

    .button {
      margin-top: 30px;
      padding: 15px 30px;
      font-size: 1.4em;
      background: linear-gradient(135deg, #e74c3c, #f39c12);
      color: white;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: background 0.3s ease;
      box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
    }

    .button:hover {
      background: linear-gradient(135deg, #c0392b, #e67e22);
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .stickers {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
      z-index: 1;
    }

    .sticker {
      position: absolute;
      width: 60px;
      height: 60px;
      animation: float 10s ease-in-out infinite;
      opacity: 0.8;
    }

    .sticker img {
      width: 100%;
      height: 100%;
    }

    @keyframes float {
      0% { transform: translateY(0px) translateX(0px) rotate(0deg); }
      50% { transform: translateY(-20px) translateX(10px) rotate(20deg); }
      100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
    }

    .sticker1 { top: 10%; left: 15%; animation-duration: 8s; animation-delay: 0s; }
    .sticker2 { top: 30%; left: 70%; animation-duration: 12s; animation-delay: 1s; }
    .sticker3 { top: 50%; left: 40%; animation-duration: 10s; animation-delay: 2s; }
    .sticker4 { top: 70%; left: 10%; animation-duration: 9s; animation-delay: 3s; }
    .sticker5 { top: 20%; left: 80%; animation-duration: 11s; animation-delay: 4s; }
    .sticker6 { top: 60%; left: 60%; animation-duration: 8s; animation-delay: 5s; }
    .sticker7 { top: 80%; left: 30%; animation-duration: 13s; animation-delay: 6s; }
  </style>
</head>
<body>
  <div class="marquee">
    <span>Your Unstoppable Love and Support Means Everything to Me, Mum ❤️</span>
  </div>

  <div class="stickers">
    <div class="sticker sticker1"><img src="https://img.icons8.com/emoji/96/heart-emoji.png" alt="Heart"></div>
    <div class="sticker sticker2"><img src="https://img.icons8.com/emoji/96/star-emoji.png" alt="Star"></div>
    <div class="sticker sticker3"><img src="https://img.icons8.com/emoji/96/rose.png" alt="Rose"></div>
    <div class="sticker sticker4"><img src="https://img.icons8.com/emoji/96/sun-with-face.png" alt="Sun"></div>
    <div class="sticker sticker5"><img src="https://img.icons8.com/emoji/96/gift.png" alt="Gift"></div>
    <div class="sticker sticker6"><img src="https://img.icons8.com/emoji/96/sparkles.png" alt="Sparkles"></div>
    <div class="sticker sticker7"><img src="https://img.icons8.com/emoji/96/balloon.png" alt="Balloon"></div>
  </div>

  <div class="letter-container">
    <h1>I Promise to Work Hard and Repay You</h1>
    <p>Dear Mum,</p>
    <p>I want you to know how grateful I am for your love, support, and sacrifices. Everything you’ve done for me has shaped the person I am today. I promise to work hard, excel in my journey, and make you proud every step of the way.</p>
    <p>I know I can never repay you fully for all you’ve done, but I will do my best to succeed and show you that your efforts were never in vain. Thank you for believing in me and for giving me the chance to achieve my dreams.</p>
    <p class="signature">With all my love, <br> Monteli Blessen</p>
    <button class="button" onclick="alert('I love you, Mum!')">Send My Promise</button>
  </div>

  <div class="marquee">
    <span>Your Beloved Ever Loving Son Monteli Blessen Lihalo</span>
  </div>
</body>
</html>
