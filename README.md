

```html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة طيبة لنقل الأثاث</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6600;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        header img {
            max-width: 150px;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        #main {
            padding: 20px;
            background: white;
            margin-top: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .service {
            background: #ff6600;
            color: white;
            padding: 20px;
            flex: 1;
            margin: 0 10px;
            border-radius: 10px;
            text-align: center;
        }
        .contact-form {
            background: #eee;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background: #ff6600;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <img src="path/to/your/logo.png" alt="شعار شركة طيبة">
        <h1>شركة طيبة لنقل الأثاث</h1>
    </header>
    <div class="container">
        <div id="main">
            <h2>عن الشركة</h2>
            <p>شركة طيبة لنقل الأثاث تقدم خدمات نقل العفش والأثاث لجميع المحافظات. نحن متخصصون في التغليف والرفع بالونش إلى أي دور، مع ضمان النقل بآمان تام.</p>
            
            <div class="services">
                <div class="service">
                    <h3>نقل لجميع المحافظات</h3>
                    <p>نقل الأثاث إلى أي محافظة بأمان تام.</p>
                </div>
                <div class="service">
                    <h3>التغليف</h3>
                    <p>تغليف الأثاث لضمان حمايته أثناء النقل.</p>
                </div>
                <div class="service">
                    <h3>الرفع بالونش</h3>
                    <p>استخدام الونش لرفع الأثاث إلى أي دور.</p>
                </div>
            </div>
            
            <h2>اتصل بنا</h2>
            <div class="contact-form">
                <form action="your_form_processing_script" method="post">
                    <label for="name">الاسم:</label>
                    <input type="text" id="name" name="name" required>
                    
                    <label for="email">البريد الإلكتروني:</label>
                    <input type="email" id="email" name="email" required>
                    
                    <label for="message">الرسالة:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                    
                    <button type="submit">إرسال</button>
                </form>
            </div>
        </div>
    </div>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2024 شركة طيبة لنقل الأثاث</p>
    </footer>
</body>
</html>
```

يرجى ملاحظة أنك بحاجة إلى تحديث المسار في وسم `<img>` ليناسب موقع الشعار الفعلي لديك. إذا كان لديك أي تعديلا
