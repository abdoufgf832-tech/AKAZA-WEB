# AKAZA-WEB
social media 
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AKAZA</title>
    <!-- رابط أيقونات Font Awesome -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 50px;
            letter-spacing: 2px;
            text-shadow: 0 0 10px #fff;
        }

        .social-links {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 100%;
            max-width: 300px;
        }

        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            text-decoration: none;
            color: #fff;
            font-size: 1.5em;
            padding: 12px 20px;
            border: 2px solid #fff;
            border-radius: 15px;
            position: relative;
            overflow: hidden;
            transition: all 0.4s ease;
        }

        /* تأثير التوهج */
        .social-links a::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(120deg, rgba(255,255,255,0.2), rgba(255,255,255,0.5), rgba(255,255,255,0.2));
            transform: skewX(-20deg);
            transition: all 0.5s ease;
        }

        .social-links a:hover::before {
            left: 100%;
        }

        .social-links a:hover {
            color: #000;
            background-color: #fff;
            box-shadow: 0 0 20px #fff;
        }

        /* أيقونات */
        .social-links i {
            font-size: 1.8em;
        }
    </style>
</head>
<body>

    <h1>AKAZA</h1>

    <div class="social-links">
        <a href="https://www.instagram.com/ak.4za" target="_blank">
            <i class="fab fa-instagram"></i> Instagram
        </a>
        <a href="https://www.snapchat.com/add/abdou_akaza" target="_blank">
            <i class="fab fa-snapchat"></i> Snapchat
        </a>
        <a href="https://wa.me/21776763235" target="_blank">
            <i class="fab fa-whatsapp"></i> WhatsApp
        </a>
        <a href="mailto:abdoufgf832@gmail.com">
            <i class="fas fa-envelope"></i> Gmail
        </a>
        <a href="tel:0776763235">
            <i class="fas fa-phone"></i> Phone
        </a>
    </div>

</body>
</html>
