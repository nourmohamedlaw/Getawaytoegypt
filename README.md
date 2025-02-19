# Getawaytoegypt
شركة سياحه

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة سياحة - Getaway Egypt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
        }
        .logo {
            width: 150px;
        }
        .banner {
            width: 100%;
            max-height: 400px;
        }
        .container {
            padding: 20px;
        }
        .services {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .service-box {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 250px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact {
            background: #007BFF;
            color: white;
            padding: 20px;
            margin-top: 20px;
        }
        .contact a {
            color: yellow;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- هيدر مع اللوجو -->
    <header>
        <img src="logo.png" alt="لوجو الشركة" class="logo">
        <h1>مرحبًا بكم في Getaway Egypt</h1>
        <p>اكتشف جمال مصر معنا!</p>
    </header>

    <!-- بوستر سياحي -->
    <img src="poster.jpg" alt="بوستر سياحي" class="banner">

    <!-- الخدمات -->
    <div class="container">
        <h2>خدماتنا</h2>
        <div class="services">
            <div class="service-box">
                <h3>جولات سياحية</h3>
                <p>استمتع بجولات سياحية في أجمل الأماكن في مصر.</p>
            </div>
            <div class="service-box">
                <h3>حجوزات فنادق</h3>
                <p>نوفر لك أفضل العروض على الفنادق والمنتجعات.</p>
            </div>
            <div class="service-box">
                <h3>رحلات بحرية</h3>
                <p>عيش المغامرة مع رحلاتنا البحرية الرائعة!</p>
            </div>
        </div>
    </div>

    <!-- تواصل معنا -->
    <div class="contact">
        <h2>تواصل معنا</h2>
        <p>📞 الهاتف: 0123456789</p>
        <p>📧 الإيميل: <a href="info@getawayegypt.com">info@getawayegypt.com</a></p>
        <p>🌍 موقعنا: <a href="https://getawayegypt.com">getawayegypt.com</a></p>
    </div>

</body>
</html>
