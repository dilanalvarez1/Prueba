<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Love Message</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: #fff0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Arial', sans-serif;
    }

    .Heart__Love {
      width: 128px;
      height: 128px;
      background: red;
      position: absolute;
      left: 50%;
      top: 280px;
      transform: translate(-50%);
      overflow: visible;
      clip-path: polygon(
        50% 0%,
        100% 35%,
        80% 100%,
        50% 80%,
        20% 100%,
        0% 35%
      );
    }

    .message-box {
      background: #fff0f0;
      padding: 20px 30px;
      border-radius: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      text-align: center;
      position: relative;
    }

    .message-box::after {
      content: '';
      position: absolute;
      bottom: -20px;
      left: 50%;
      transform: translateX(-50%);
      width: 0;
      height: 0;
      border: 10px solid transparent;
      border-top-color: #fff0f0;
    }

    .message-box h2 {
      margin: 0;
      font-size: 1.5em;
    }
    .highlight {
      color: crimson;
    }
  </style>
</head>
<body>

  <div class="message-box">
    <div class="Heart__Love"></div>
    <h2>You are a Queen <span class="highlight">my love!</span></h2>
  </div>

</body>
</html>
