<html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abrarul Hoque with Tanisha Tasfi | ব্যবসায়িক ওয়েবসাইট</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background: #f5f7fa;
            color: #222;
        }
        header {
            background: #164863;
            color: #fff;
            padding: 16px 0;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 2px 8px #0001;
        }
        .logo {
            font-size: 1.7rem;
            font-weight: 700;
            letter-spacing: 1.2px;
            margin-left: 32px;
            display: flex;
            align-items: center;
        }
        .logo::before {
            content: "🅰";
            font-size: 2.2rem;
            margin-right: 10px;
        }
        nav {
            margin-right: 32px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 24px;
            font-weight: 500;
            font-size: 1.1rem;
            transition: color 0.2s;
        }
        nav a:hover {
            color: #ffd700;
        }
        .hero {
            background: linear-gradient(110deg, #164863 70%, #427D9D 100%);
            color: #fff;
            padding: 70px 0 50px 0;
            text-align: center;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.3rem;
            margin-bottom: 30px;
        }
        .hero .contact-btn {
            background: #ffd700;
            color: #164863;
            border: none;
            padding: 14px 34px;
            font-size: 1.1rem;
            font-weight: 700;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.2s;
        }
        .hero .contact-btn:hover {
            background: #ffa500;
            color: #fff;
        }
        section {
            margin: 48px auto;
            max-width: 960px;
            background: #fff;
            border-radius: 10px;
            padding: 38px 32px 28px 32px;
            box-shadow: 0 2px 12px #0001;
        }
        section h2 {
            color: #164863;
            margin-bottom: 12px;
            font-size: 2rem;
            border-left: 4px solid #ffd700;
            padding-left: 10px;
        }
        .services-list {
            display: flex;
            flex-wrap: wrap;
            gap: 32px;
            margin-top: 16px;
        }
        .service-item {
            flex: 1 1 260px;
            background: #f5f7fa;
            border-radius: 8px;
            padding: 24px 18px;
            transition: box-shadow 0.2s;
            box-shadow: 0 1px 6px #0001;
        }
        .service-item h3 {
            color: #427D9D;
            margin-bottom: 8px;
        }
        .service-item p {
            font-size: 1rem;
        }
        .contact-info {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        .contact-form {
            margin-top: 24px;
        }
        .contact-form label {
            display: block;
            margin-bottom: 6px;
            font-weight: 500;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 16px;
            border: 1px solid #bbb;
            border-radius: 5px;
            font-size: 1rem;
        }
        .contact-form button {
            background: #164863;
            color: #fff;
            font-weight: 700;
            border: none;
            padding: 13px 28px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.2s;
        }
        .contact-form button:hover {
            background: #427D9D;
        }
        footer {
            background: #164863;
            color: #fff;
            text-align: center;
            padding: 18px 0;
            font-size: 1rem;
            margin-top: 36px;
        }
        @media (max-width: 700px) {
            .services-list { flex-direction: column; }
            header, nav, .logo { flex-direction: column; margin: 0; }
            nav { margin: 0; }
            section { padding: 20px 10px; }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Abrarul Hoque with Tanisha Tasfi</div>
        <nav>
            <a href="#home">হোম</a>
            <a href="#about">আমাদের সম্পর্কে</a>
            <a href="#services">সেবা</a>
            <a href="#contact">যোগাযোগ</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <h1>বিশ্বাসযোগ্য ব্যবসায়িক সমাধান</h1>
        <p>আপনার ব্যবসাকে ডিজিটাল জগতে নিয়ে যেতে <b>Abrarul Hoque with Tanisha Tasfi</b> সবসময় পাশে আছে।</p>
        <button class="contact-btn" onclick="window.location='#contact'">যোগাযোগ করুন</button>
    </div>

    <section id="about">
        <h2>আমাদের সম্পর্কে</h2>
        <p>
            আমরা <b>Abrarul Hoque with Tanisha Tasfi</b> — আধুনিক, পেশাদার এবং নির্ভরযোগ্য ব্যবসায়িক সেবা প্রদান করে থাকি।  
            আপনার ব্যবসার জন্য ওয়েবসাইট ডিজাইন, ডিজিটাল মার্কেটিং, ব্র্যান্ডিং এবং আইটি কনসালটেন্সি সার্ভিস দিয়ে থাকি।  
            অভিজ্ঞ টিম এবং আধুনিক প্রযুক্তি দিয়ে আমরা আপনাকে সফলতার প্রতিশ্রুতি দিচ্ছি।
        </p>
    </section>

    <section id="services">
        <h2>আমাদের সেবা</h2>
        <div class="services-list">
            <div class="service-item">
                <h3>ওয়েবসাইট ডিজাইন ও ডেভেলপমেন্ট</h3>
                <p>আপনার কোম্পানির জন্য আধুনিক, মোবাইল-রেসপনসিভ ওয়েবসাইট তৈরি করুন আমাদের মাধ্যমে।</p>
            </div>
            <div class="service-item">
                <h3>ডিজিটাল মার্কেটিং</h3>
                <p>সামাজিক যোগাযোগ মাধ্যম, এসইও ও অনলাইন বিজ্ঞাপন—সবকিছু এক জায়গায়।</p>
            </div>
            <div class="service-item">
                <h3>ব্র্যান্ডিং ও গ্রাফিক্স ডিজাইন</h3>
                <p>লোগো, ভিজিটিং কার্ড, ব্যানার এবং ব্র্যান্ড আইডেন্টিটি ডিজাইন।</p>
            </div>
            <div class="service-item">
                <h3>আইটি কনসালটেন্সি</h3>
                <p>ব্যবসায়িক সমস্যা এবং আইটি সলিউশন—দ্রুত ও নির্ভরযোগ্য পরামর্শ।</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>যোগাযোগ করুন</h2>
        <div class="contact-info">
            <strong>ফোন:</strong> <a href="tel:0151429994">0151429994</a><br>
            <strong>ই-মেইল:</strong> <a href="mailto:info@abrarulhoque.com">info@abrarulhoque.com</a>
        </div>
        <form class="contact-form">
            <label for="name">নাম</label>
            <input type="text" id="name" name="name" required>
            <label for="email">ই-মেইল</label>
            <input type="email" id="email" name="email" required>
            <label for="message">আপনার বার্তা</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">পাঠান</button>
        </form>
    </section>

    <footer>
        &copy; 2025 Abrarul Hoque with Tanisha Tasfi | ডিজাইন ও ডেভেলপমেন্ট: Abrarul Hoque with Tanisha Tasfi Team
    </footer>

    <script>
        // ফেক সাবমিট (demo only)
        document.querySelector('.contact-form').addEventListener('submit', function(e){
            e.preventDefault();
            alert('আপনার বার্তা সফলভাবে পাঠানো হয়েছে! (ডেমো)');
            this.reset();
        });
    </script>
</body>
</html># ah
