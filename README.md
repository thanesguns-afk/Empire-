<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>Empire Header</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background: transparent;
      font-family: sans-serif;
    }

    .wrap {
      width: 100%;
      padding: 8px 0;
      background: transparent;
      box-sizing: border-box;
      display: flex;
      justify-content: center;
    }

    .card {
      background: #ffffff;
      border-radius: 8px;
      padding: 6px 10px;
      display: flex;
      align-items: center;
      gap: 10px;
      box-sizing: border-box;
      max-width: 420px;
      width: 100%;
    }

    .card img.logo {
      height: 42px;
      display: block;
    }

    .btn {
      padding: 6px 10px;
      border-radius: 6px;
      font-size: 13px;
      font-weight: bold;
      text-decoration: none;
      color: #fff;
      display: inline-flex;
      align-items: center;
      gap: 6px;
      white-space: nowrap;
    }

    .btn img {
      width: 16px;
      height: 16px;
    }

    .btn.green {
      background-color: #00c300;
    }

    .btn.orange {
      background-color: #f5511e;
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <!-- โลโก้ (ภาพนี้มีพื้นหลังขาวอยู่แล้ว) -->
      <img class="logo" src="https://i.postimg.cc/2SSHL0Px/Untitled-design.png" alt="EMPIRE WAY">

      <!-- ปุ่มสมัคร -->
      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me"
         class="btn green" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111728.png" alt="LINE">
        สมัครสมาชิก
      </a>

      <!-- ปุ่มเข้าสู่ระบบ -->
      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me"
         class="btn orange" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1828/1828490.png" alt="Login">
        เข้าสู่ระบบ
      </a>
    </div>
  </div>
</body>
</html>
