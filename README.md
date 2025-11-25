<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flickxzi</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #000;
      background-image: url('your-background-image.jpg');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      font-family: sans-serif;
    }

    .header {
      width: 100%;
      height: 70px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
      background-color: rgba(0, 0, 0, 0.4);
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
    }

    .logo img {
      width: 100px;
      height: auto;
      transform: scale(1.6);
      transform-origin: left center;
    }

    .buttons {
      display: flex;
      gap: 10px;
    }

    .btn {
      padding: 8px 16px;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      display: flex;
      align-items: center;
      gap: 6px;
      text-decoration: none;
      color: white;
    }

    .btn img {
      height: 18px;
      width: 18px;
    }

    .btn.green {
      background-color: #00c300;
    }

    .btn.orange {
      background-color: #f5511e;
    }

    @media (max-width: 768px) {
      .header {
        padding: 12px 20px;
      }

      .logo img {
        transform: scale(1.4);
      }

      .btn {
        padding: 6px 12px;
        font-size: 14px;
      }

      .btn img {
        height: 16px;
        width: 16px;
      }
    }
  </style>
</head>
<body>

  <div class="header">
    <!-- โลโก้ใหม่ -->
    <div class="logo">
      <img src="https://i.postimg.cc/2SSHL0Px/Untitled-design.png" alt="Flickxzi Logo">
    </div>

    <div class="buttons">
      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me" class="btn green" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111728.png" alt="LINE">
        สมัครสมาชิก
      </a>

      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me" class="btn orange" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1828/1828490.png" alt="Login">
        เข้าสู่ระบบ
      </a>
    </div>
  </div>

</body>
</html>
