<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meow Meow Tarot</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .header {
            background-color: #d4af37; /* vàng */
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            color: #8a6d3b; /* nâu */
        }
        .links a {
            color: #d4af37; /* vàng */
            text-decoration: none;
            margin: 0 10px;
        }
        .links a:hover {
            text-decoration: underline;
        }
        .footer {
            background-color: #d4af37; /* vàng */
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .sample {
            flex: 1;
            min-width: 300px;
        }
        .feedbacks {
            margin-top: 20px;
        }
        .feedback {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Meow Meow Tarot</h1>
        <p>Điện thoại: 0907983371 | Địa chỉ: Quận 3, TP Thủ Đức</p>
    </header>

    <div class="container">
        <section class="section">
            <h2>Dịch vụ của chúng tôi</h2>
            <p>Chúng tôi cung cấp các dịch vụ xem bài tarot, lenormand, oracle, tea-leaf, kinh dịch, tử vi, bản đồ sao, chỉ tay, và thần số học. Hãy liên hệ với chúng tôi để khám phá những điều thú vị và bí ẩn trong cuộc sống của bạn!</p>
        </section>

        <section class="section">
            <h2>Liên kết mạng xã hội</h2>
            <div class="links">
                <a href="https://www.facebook.com/MeowMeowTarot" target="_blank">Facebook</a>
                <a href="https://www.tiktok.com/@meowmeowtarot" target="_blank">TikTok</a>
                <a href="https://www.instagram.com/meowmeowtarot" target="_blank">Instagram</a>
            </div>
        </section>

        <section class="section">
            <h2>Trải bài mẫu</h2>
            <div class="gallery">
                <div class="sample">
                    <img src="path-to-your-image1.jpg" alt="Trải bài mẫu 1" style="width:100%; max-width:600px;">
                    <p>Mô tả trải bài mẫu 1.</p>
                </div>
                <div class="sample">
                    <img src="path-to-your-image2.jpg" alt="Trải bài mẫu 2" style="width:100%; max-width:600px;">
                    <p>Mô tả trải bài mẫu 2.</p>
                </div>
                <!-- Thêm các trải bài mẫu khác tại đây -->
            </div>
        </section>

        <section class="section">
            <h2>Liên hệ và Đặt lịch</h2>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <label for="name">Họ và tên:</label><br>
                <input type="text" id="name" name="name" required><br><br>
                
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                
                <label for="phone">Số điện thoại:</label><br>
                <input type="tel" id="phone" name="phone"><br><br>
                
                <label for="message">Tin nhắn:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                
                <input type="submit" value="Gửi">
            </form>
        </section>

        <section class="section">
            <h2>Phản hồi của khách hàng</h2>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <label for="feedback-name">Họ và tên:</label><br>
                <input type="text" id="feedback-name" name="name" required><br><br>
                
                <label for="feedback-email">Email:</label><br>
                <input type="email" id="feedback-email" name="email" required><br><br>
                
                <label for="feedback-message">Phản hồi:</label><br>
                <textarea id="feedback-message" name="message" rows="4" required></textarea><br><br>
                
                <input type="submit" value="Gửi">
            </form>
            <h3>Phản hồi từ khách hàng:</h3>
            <div class="feedbacks">
                <div class="feedback">
                    <p><strong>Nguyễn Văn A:</strong> Dịch vụ tuyệt vời! Tôi đã có những trải nghiệm thú vị và chính xác.</p>
                </div>
                <div class="feedback">
                    <p><strong>Trần Thị B:</strong> Thật sự ấn tượng với sự chuyên nghiệp và chính xác của các trải bài. Cảm ơn rất nhiều!</p>
                </div>
                <!-- Thêm phản hồi từ khách hàng tại đây -->
            </div>
        </section>
    </div>

    <footer class="footer">
        <p>&copy; 2024 Meow Meow Tarot. Tất cả quyền được bảo lưu.</p>
    </footer>

    <!-- Begin Tawk.to Widget -->
    <script type="text/javascript">
        var Tawk_API = Tawk_API || {}, Tawk_LoadStart = new Date();
        (function() {
            var s1 = document.createElement("script"), s0 = document.getElementsByTagName("script")[0];
            s1.async = true;
            s1.src = 'https://embed.tawk.to/your-tawkto-id/default';
            s1.charset = 'UTF-8';
            s1.setAttribute('crossorigin', '*');
            s0.parentNode.insertBefore(s1, s0);
        })();
    </script>
    <!-- End Tawk.to Widget -->

</body>
</html>
