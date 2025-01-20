
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Web Của Tôi</title>
  <link href="https://fonts.googleapis.com/css2?family=Lora&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    h1 {
            display: none;
            }
    body {
      font-family: 'Lora', serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #f8d7d7, #ffe6e6);
      overflow-x: hidden;
    }

    .header {
      background: linear-gradient(90deg, #ff4e50, #f9d423);
      color: white;
      text-align: center;
      padding: 30px 20px;
      position: relative;
    }

    .header h1 {
      font-size: 36px;
      font-weight: bold;
      margin: 0;
      animation: glow 2s infinite alternate, rainbow-text 3s linear infinite;
      background-image: linear-gradient(45deg, red, orange, yellow, green, cyan, blue, violet);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
    }

    @keyframes glow {
      0% {
        text-shadow: 0 0 10px #ff4e50, 0 0 20px #ff4e50, 0 0 30px #f9d423, 0 0 40px #f9d423;
      }
      100% {
        text-shadow: 0 0 20px #ff4e50, 0 0 30px #f9d423, 0 0 40px #f9d423, 0 0 50px #ff4e50;
      }
    }

    @keyframes rainbow-text {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 20px;
    }

    .intro {
      font-size: 24px;
      color: #003366;
      font-weight: normal;
      text-align: center;
      margin-bottom: 40px;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .section {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      margin-bottom: 40px;
      flex-wrap: wrap;
      animation: slideIn 2s ease-in-out;
    }

    @keyframes slideIn {
      from {
        transform: translateX(-100%);
      }
      to {
        transform: translateX(0);
      }
    }

    .section .image img {
      width: 80%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s;
    }

    .section .image img:hover {
      transform: scale(1.1);
    }

    .section .text-container {
      flex: 1;
      padding: 20px;
    }

    .text-container .title {
      font-size: 28px;
      font-weight: bold;
      color: #d9534f;
      margin-bottom: 10px;
      background-image: linear-gradient(45deg, red, orange, yellow, green, cyan, blue, violet);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      animation: rainbow-text 3s linear infinite;
    }

    .text-container .text {
      font-size: 20px;
      color: #003366;
      line-height: 1.6;
    }

    .floating-icons {
      position: fixed;
      bottom: 10px;
      right: 10px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .floating-icons a {
      width: 50px;
      height: 50px;
      background-color: #ff4e50;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s;
    }

    .floating-icons a:hover {
      transform: scale(1.2);
    }

    .floating-icons a img {
      width: 60%;
      height: auto;
    }

    .footer {
      text-align: center;
      padding: 20px;
      background-color: #003366;
      color: white;
      margin-top: 40px;
    }

    .footer p {
      margin: 0;
      font-size: 18px;
    }

    .hobbies {
      margin: 40px;
      text-align: center;
      animation: slideUp 2s ease-in-out;
    }

    @keyframes slideUp {
      from {
        transform: translateY(100%);
      }
      to {
        transform: translateY(0);
      }
    }

    .hobbies .title {
      font-size: 30px;
      font-weight: bold;
      margin-bottom: 20px;
      color: #ff4e50;
      background-image: linear-gradient(45deg, red, orange, yellow, green, cyan, blue, violet);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      animation: rainbow-text 3s linear infinite;
    }

    .hobbies-list {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }

    .hobby {
      background-color: #fff;
      border-radius: 12px;
      padding: 20px;
      width: 250px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }

    .hobby:hover {
      transform: scale(1.1);
    }

    .hobby img {
      width: 100%;
      border-radius: 12px;
    }

    .hobby .hobby-title {
      font-size: 22px;
      font-weight: bold;
      color: #003366;
      margin-top: 10px;
    }

    .hobby .hobby-description {
      font-size: 18px;
      color: #666;
      margin-top: 5px;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>NGUYỄN NGỌC THỊNH XIN CHÀO</h1>
  </div>

  <div class="container">
    <div class="intro">
      Mình tên là Nguyễn Ngọc Thịnh hiện đang theo học tại ngôi trường THPT Chuyên Bến Tre, mình rất hân hạnh được giới thiệu bản thân mình.
    </div>

    <div class="section">
      <div class="image">
        <img src="462578825_1082412466900930_547812731579927046_n.jpg" alt="Ảnh 1">
      </div>
      <div class="text-container">
        <div class="title">Thông tin cá nhân</div>
        <div class="text">Hiện tại mình học lớp 12 Lý, trường THPT Chuyên Bến Tre. Mình nặng 65kg và cao 1,80m</div>
      </div>
    </div>

    <div class="section">
      <div class="text-container">
        <div class="title">Nguyện vọng tương lai</div>
        <div class="text">Mình chọn thi khối Khoa học tự nhiên, nguyện vọng 1 là ngành Vi mạch bán dẫn trường đại học Bách Khoa.</div>
      </div>
      <div class="image">
        <img src="1.jpg" alt="Ảnh 2">
      </div>
    </div>
  </div>

  <div class="hobbies">
    <div class="title">Sở thích của tôi</div>
    <div class="hobbies-list">
      <div class="hobby">
        <img src="https://img.icons8.com/color/256/badminton.png" alt="Đánh cầu lông">
        <div class="hobby-title">Đánh cầu lông</div>
        <div class="hobby-description">Môn thể thao giúp tôi rèn luyện sức khỏe và tinh thần đồng đội.</div>
      </div>
      <div class="hobby">
        <img src="ball.jpg" alt="Đá bóng">
        <div class="hobby-title">Đá bóng</div>
        <div class="hobby-description">Niềm đam mê từ nhỏ, luôn mang lại sự hào hứng.</div>
      </div>
      <div class="hobby">
        <img src="chess.jpg" alt="Đánh cờ vua">
        <div class="hobby-title">Đánh cờ vua</div>
        <div class="hobby-description">Trò chơi trí tuệ tôi yêu thích để rèn luyện tư duy.</div>
      </div>
      <div class="hobby">
        <img src="https://img.icons8.com/color/256/league-of-legends.png" alt="Đấu Trường Chân Lý">
        <div class="hobby-title">Đấu Trường Chân Lý</div>
        <div class="hobby-description">Thỏa sức sáng tạo với chiến thuật và đội hình độc đáo.</div>
      </div>
      <div class="hobby">
        <img src="mập.jpg" alt="Ngắm các nàng thơ và chọc thằng mậpmập">
        <div class="hobby-title">Ngắm các nàng thơ</div>
        <div class="hobby-description">Khoảnh khắc dịu dàng và cảm hứng cho cuộc sống.</div>
      </div>
    </div>
  </div>

  <div class="floating-icons">
    <a href="#"><img src="https://img.icons8.com/color/48/facebook-circled--v1.png" alt="Facebook"></a>
    <a href="#"><img src="https://img.icons8.com/color/48/instagram-new--v1.png" alt="Instagram"></a>
    <a href="#"><img src="https://img.icons8.com/color/48/youtube-play--v1.png" alt="YouTube"></a>
  </div>

  <div class="footer">
    <p>&copy; 2025 Nguyễn Ngọc Thịnh - Tất cả các quyền được bảo lưu.</p>
  </div>
</body>
</html>
