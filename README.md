# GETAWAY TO EGYPT
Tourism company

1️⃣ ملف index.html (الصفحة الرئيسية)

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Getaway Egypt - شركة سياحة</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>

    <!-- الهيدر -->
    <header class="header">
        <div class="logo">Getaway <span>Egypt</span></div>
        <nav>
            <ul>
                <li><a href="#services">الخدمات</a></li>
                <li><a href="#about">عنّا</a></li>
                <li><a href="#contact">تواصل معنا</a></li>
            </ul>
        </nav>
    </header>

    <!-- بوستر متحرك -->
    <section class="hero">
        <h1>اكتشف سحر <span>مصر</span> معنا</h1>
        <p>رحلات سياحية فاخرة بأفضل الأسعار</p>
        <a href="#contact" class="btn">احجز رحلتك الآن</a>
    </section>

    <!-- الخدمات -->
    <section id="services" class="services">
        <h2>خدماتنا</h2>
        <div class="service-box">
            <h3>جولات سياحية</h3>
            <p>استمتع بجولات فريدة في أفضل الأماكن التاريخية.</p>
        </div>
        <div class="service-box">
            <h3>حجوزات فنادق</h3>
            <p>نوفر لك أفضل العروض في أفخم الفنادق.</p>
        </div>
        <div class="service-box">
            <h3>رحلات بحرية</h3>
            <p>اكتشف سحر البحر الأحمر برحلات بحرية ممتعة.</p>
        </div>
    </section>

    <!-- قسم التواصل -->
    <section id="contact" class="contact">
        <h2>تواصل معنا</h2>
        <p>📞 الهاتف: 0123456789</p>
        <p>📧 الإيميل: <a href="info@getawayegypt.com">info@getawayegypt.com</a></p>
        <p>🌍 موقعنا: <a href="https://getawayegypt.com">getawayegypt.com</a></p>
    </section>

</body>
</html>


---

2️⃣ ملف styles.css (تصميم الصفحة)

/* إعدادات عامة */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #000;
    color: #FFD700;
    text-align: center;
}

/* الهيدر */
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background: rgba(0, 0, 0, 0.9);
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.logo span {
    color: #FFD700;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #FFD700;
}

/* البوستر */
.hero {
    height: 100vh;
    background: url('poster.jpg') no-repeat center center/cover;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.7);
}

.hero h1 {
    font-size: 50px;
}

.hero span {
    color: #FFD700;
}

.hero .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background: #FFD700;
    color: #000;
    text-decoration: none;
    font-size: 20px;
    border-radius: 5px;
    transition: 0.3s;
}

.hero .btn:hover {
    background: white;
    color: black;
}

/* الخدمات */
.services {
    padding: 50px 20px;
    background: #111;
}

.service-box {
    background: #222;
    padding: 20px;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(255, 215, 0, 0.5);
}

/* تواصل معنا */
.contact {
    background: #000;
    padding: 40px 20px;
}

.contact a {
    color: #FFD700;
    text-decoration: none;
}


---

3️⃣ ملف script.js (الحركة عند التمرير)
