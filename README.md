<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>Flickxzi Header</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #000;
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
      box-sizing: border-box;
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
    <div class="logo">
      <!-- โลโก้ของคุณ -->
      <img src="https://i.postimg.cc/2SSHL0Px/Untitled-design.png" alt="Flickxzi Logo">
    </div>

    <div class="buttons">
      <!-- ลิงก์ไลน์ของคุณ (สมัครสมาชิก) -->
      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me"
         class="btn green" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111728.png" alt="LINE">
        สมัครสมาชิก
      </a>

      <!-- ลิงก์ไลน์ของคุณ (เข้าสู่ระบบ) -->
      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me"
         class="btn orange" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1828/1828490.png" alt="Login">
        เข้าสู่ระบบ
      </a>
    </div>
  </div>

</body>
</html>
