<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>我想你了</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      font-family: "Helvetica Neue", sans-serif;
    }
    .message {
      font-size: 48px;
      color: white;
      animation: heartbeat 1.5s ease-in-out infinite;
    }
    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
  </style>
</head>
<body>
  <div class="message">我想你了 ❤️</div>
</body>
</html>
