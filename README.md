<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعي الأول</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>مرحبًا بك في موقعي!</h1>
        <nav>
            <ul>
                <li><a href="#about">من نحن</a></li>
                <li><a href="#services">الخدمات</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <!-- هنا يمكنك إضافة الأقسام الجديدة -->
    <section id="about">
        <h2>من نحن</h2>
        <p>نحن فريق مبدع نعمل على إنشاء مواقع ويب رائعة.</p>
    </section>

    <section id="services">
        <h2>الخدمات</h2>
        <ul>
            <li>تصميم مواقع الويب</li>
            <li>تطوير تطبيقات الويب</li>
            <li>تحسين محركات البحث (SEO)</li>
        </ul>
    </section>

    <section id="contact">
        <h2>اتصل بنا</h2>
        <form>
            <label for="name">الاسم:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">الرسالة:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">إرسال</button>
        </form>
    </section>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2023</p>
    </footer>
</body>
</html>
