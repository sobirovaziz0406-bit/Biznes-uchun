# Biznes-uchun
Monay 
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biznes uchun</title>
    <style>
        body {
            background: #162447;
            color: #fff;
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
        }
        header {
            background: #1f4068;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: #e43f5a;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 20px;
            background: #1b1b2f;
            border-radius: 18px;
            box-shadow: 0 0 16px #0f3460;
        }
        .blogers {
            display: flex;
            flex-wrap: wrap;
            gap: 22px;
            justify-content: center;
        }
        .bloger-card {
            background: #162447;
            border: 2px solid #1f4068;
            border-radius: 12px;
            width: 240px;
            padding: 14px;
            text-align: center;
            box-shadow: 0 2px 10px #1f4068;
        }
        .bloger-card img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
            border: 3px solid #e43f5a;
        }
        .bloger-card h3 {
            margin: 8px 0 4px 0;
            font-size: 1.3em;
        }
        .bloger-card p {
            margin: 6px 0;
            font-size: 1em;
        }
        .price {
            color: #e43f5a;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .btn {
            background: #e43f5a;
            color: #fff;
            border: none;
            border-radius: 6px;
            padding: 8px 18px;
            font-size: 1em;
            cursor: pointer;
            transition: background 0.2s;
        }
        .btn:hover {
            background: #f95a80;
        }
        footer {
            text-align: center;
            margin: 32px 0 10px 0;
            color: #eee;
            font-size: 1em;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 9px;
            margin: 8px 0;
            border-radius: 6px;
            border: 1px solid #1f4068;
            background: #162447;
            color: #fff;
        }
        .contact-form textarea {
            resize: vertical;
            min-height: 70px;
        }
        .contact-form button {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Biznes uchun</h1>
        <nav>
            <a href="#blogers">Blogerlar</a>
            <a href="#services">Xizmatlar</a>
            <a href="#contact">Aloqa</a>
        </nav>
    </header>

    <div class="container">
        <!-- Bosh sahifa qisqacha info -->
        <section>
            <h2>O‘z biznesingizni mashhur blogerlar yordamida rivojlantiring!</h2>
            <p>Biznesingiz uchun eng yaxshi blogerlar bilan 30 daqiqa uchrashuvni bron qiling va o‘z sohangizda o‘sish imkoniyatini qo‘lga kiriting.</p>
        </section>

        <!-- Blogerlar ro'yxati -->
        <section id="blogers">
            <h2>Mashhur Blogerlar</h2>
            <div class="blogers">
                <!-- Bloger 1 -->
                <div class="bloger-card">
                    <img src="https://randomuser.me/api/portraits/women/45.jpg" alt="Bloger 1">
                    <h3>Malika Akbarova</h3>
                    <p>Marketing va SMM bo‘yicha ekspert</p>
                    <div class="price">30 daqiqa: $50</div>
                    <button class="btn">Uchrashuvga yozilish</button>
                </div>
                <!-- Bloger 2 -->
                <div class="bloger-card">
                    <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Bloger 2">
                    <h3>Jasur Bekmurodov</h3>
                    <p>Biznes strategiya va kontent yaratuvchi</p>
                    <div class="price">30 daqiqa: $50</div>
                    <button class="btn">Uchrashuvga yozilish</button>
                </div>
                <!-- Bloger 3 -->
                <div class="bloger-card">
                    <img src="https://randomuser.me/api/portraits/men/52.jpg" alt="Bloger 3">
                    <h3>Aziza Nurmatova</h3>
                    <p>Branding va PR mutaxassisi</p>
                    <div class="price">30 daqiqa: $50</div>
                    <button class="btn">Uchrashuvga yozilish</button>
                </div>
                <!-- Blogerlar sonini oson ko'paytirish mumkin -->
            </div>
        </section>

        <!-- Xizmatlar -->
        <section id="services">
            <h2>Xizmatlar</h2>
            <ul>
                <li>Blogerlar bilan onlayn uchrashuvlar tashkil qilish</li>
                <li>Biznes, marketing va PR bo‘yicha maslahatlar</li>
                <li>Branding va reklama strategiyasi tuzish</li>
                <li>SMM va kontent yaratishda yordam</li>
            </ul>
        </section>

        <!-- Kontakt -->
        <section id="contact">
            <h2>Aloqa</h2>
            <form class="contact-form">
                <input type="text" placeholder="Ismingiz" required>
                <input type="email" placeholder="Email" required>
                <textarea placeholder="Savolingiz yoki buyurtmangiz..." required></textarea>
                <button type="submit" class="btn">Yuborish</button>
            </form>
        </section>
    </div>

    <footer>
        Biznes uchun &copy; 2025. Barcha huquqlar himoyalangan.
    </footer>
</body>
</html>