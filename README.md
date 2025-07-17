<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trái Cây Nhà Vườn Long Thành</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
    }
    header {
      background-color: #43a047;
      color: white;
      padding: 30px;
      text-align: center;
    }
    nav {
      background-color: #2e7d32;
      text-align: center;
      padding: 15px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
      font-size: 16px;
    }
    .hero {
      padding: 60px 20px;
      background-image: url('https://images.unsplash.com/photo-1582515073490-dc98e2f52b89');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
    }
    .container {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .section {
      background-color: white;
      padding: 30px;
      border-radius: 12px;
      margin-bottom: 40px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .product {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      align-items: flex-start;
    }
    .product-item {
      flex: 1 1 250px;
      background: #f9f9f9;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 1px 5px rgba(0,0,0,0.05);
      text-align: center;
    }
    .product-item img {
      width: 100%;
      border-radius: 8px;
      height: 180px;
      object-fit: cover;
    }
    .product-item h3 {
      margin: 10px 0 5px;
      color: #388e3c;
    }
    .product-item p {
      font-size: 14px;
    }
    .product-item button {
      margin-top: 10px;
      background-color: #43a047;
      border: none;
      color: white;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }
    h2 {
      color: #2e7d32;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 25px;
    }
    .newsletter input {
      padding: 10px;
      width: 70%;
      max-width: 400px;
      border-radius: 4px;
      border: 1px solid #ccc;
      margin-right: 10px;
    }
    .newsletter button {
      padding: 10px 15px;
      background-color: #2e7d32;
      color: white;
      border: none;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Trái Cây Nhà Vườn Long Thành</h1>
    <p>Tươi ngon tại vườn – Giao hàng tận nhà TP.HCM & lân cận</p>
  </header>

  <nav>
    <a href="#about">Giới Thiệu</a>
    <a href="#products">Sản Phẩm</a>
    <a href="#offers">Ưu Đãi</a>
    <a href="#how">Thanh Toán</a>
    <a href="#contact">Liên Hệ</a>
  </nav>

  <section class="hero">
    <h2>Hoa quả tươi - Giá tận vườn - Giao nhanh 24h</h2>
    <p>Thơm ngon - An toàn - Gần gũi người Việt</p>
  </section>

  <section id="about" class="container section">
    <h2>Về Chúng Tôi</h2>
    <p>Chúng tôi là nhà vườn tại Long Thành – Đồng Nai, chuyên cung cấp trái cây sạch, tươi mới mỗi ngày. Tất cả sản phẩm đều được chọn lựa kỹ càng, hái trong ngày và đóng gói cẩn thận.</p>
    <p>Bán lẻ – Bán sỉ – Cung cấp cho quán ăn, cửa hàng và đơn vị tổ chức sự kiện.</p>
  </section>

  <section id="products" class="container section">
    <h2>Sản Phẩm Tiêu Biểu</h2>
    <div class="product">
      <div class="product-item">
        <img src="https://images.unsplash.com/photo-1584270354949-6ea6f3ff7b07" alt="Xoài">
        <h3>Xoài Cát Hòa Lộc</h3>
        <p>65.000đ/kg - Ngọt thanh, vỏ mỏng, chín tự nhiên.</p>
        <button onclick="window.open('https://zalo.me/0901234567', '_blank')">Đặt qua Zalo</button>
      </div>
      <div class="product-item">
        <img src="https://images.unsplash.com/photo-1576402187873-0571de7c8895" alt="Chôm Chôm">
        <h3>Chôm Chôm Nhãn</h3>
        <p>45.000đ/kg - Vỏ mỏng, cơm dày, ngọt thơm.</p>
        <button onclick="window.open('tel:0901234567')">Gọi đặt hàng</button>
      </div>
      <div class="product-item">
        <img src="https://images.unsplash.com/photo-1589905532400-5b5b55c2df3c" alt="Bưởi da xanh">
        <h3>Bưởi Da Xanh</h3>
        <p>70.000đ/trái - Mọng nước, ngọt mát, không hạt.</p>
        <button>Liên hệ ngay</button>
      </div>
    </div>
  </section>

  <section id="offers" class="container section">
    <h2>Ưu Đãi & Combo</h2>
    <ul>
      <li>🎁 Combo 3kg xoài + chôm chôm chỉ 150.000đ</li>
      <li>🚚 Miễn phí giao hàng đơn trên 300.000đ tại TP.HCM</li>
      <li>👨‍👩‍👧 Ưu đãi cho khách đặt hàng từ 2 lần trở lên</li>
    </ul>
  </section>

  <section id="how" class="container section">
    <h2>Thanh Toán & Giao Hàng</h2>
    <ul>
      <li>Giao nhanh 24h tại TP.HCM – Biên Hòa – Bình Dương</li>
      <li>Thanh toán khi nhận hàng hoặc chuyển khoản</li>
      <li>Hỗ trợ đổi trả nếu sản phẩm không đạt yêu cầu</li>
    </ul>
  </section>

  <section id="contact" class="container section">
    <h2>Liên Hệ Với Chúng Tôi</h2>
    <p>📞 Gọi ngay: <a href="tel:0901234567">0901 234 567</a></p>
    <p>📱 Zalo: <a href="https://zalo.me/0901234567" target="_blank">zalo.me/0901234567</a></p>
    <p>📧 Email: traicay.longthanh@gmail.com</p>
    <p>📍 Vườn tại xã Bình Sơn, Long Thành, Đồng Nai</p>
    <div class="newsletter">
      <h3>Đăng ký nhận ưu đãi & tin mới:</h3>
      <input type="text" placeholder="Nhập email hoặc số điện thoại">
      <button>Gửi</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Trái Cây Nhà Vườn Long Thành | Website gần gũi, dễ mua, dễ dùng.</p>
  </footer>
</body>
</html>
