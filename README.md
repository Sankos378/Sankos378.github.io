<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Hüseyin Polat - İletişim</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            /* Arka plan renk geçişi (Ekran görüntüsündeki gibi) */
            background: linear-gradient(180deg, #4b5263 0%, #292442 50%, #151121 100%);
            color: white;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            min-height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        
        .container-app {
            width: 100%;
            max-width: 450px;
            padding: 20px;
            box-sizing: border-box;
            padding-top: 40px;
        }

        /* Profil Fotoğrafı Alanı */
        .profile-pic {
            width: 120px;
            height: 120px;
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 50px;
            font-weight: 400;
            margin: 0 auto 20px auto;
            border: 2px solid rgba(255, 255, 255, 0.3);
            box-shadow: inset 0 0 10px rgba(0,0,0,0.1);
        }

        /* Başlıklar */
        .title-small {
            text-align: center;
            font-size: 14px;
            font-weight: 600;
            letter-spacing: 1px;
            color: rgba(255, 255, 255, 0.9);
            margin-bottom: 5px;
        }

        .title-large {
            text-align: center;
            font-size: 32px;
            font-weight: 700;
            margin-bottom: 30px;
        }

        /* Yuvarlak Butonlar */
        .action-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
        }

        .action-btn {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.15);
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            color: white;
            font-size: 22px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: background-color 0.2s;
        }
        
        .action-btn:active {
            background-color: rgba(255, 255, 255, 0.3);
        }

        /* Alt Bilgi Kartı */
        .info-card {
            background-color: rgba(255, 255, 255, 0.08);
            border-radius: 20px;
            padding: 5px 20px;
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .info-row {
            display: block;
            text-decoration: none;
            border-bottom: 1px solid rgba(255, 255, 255, 0.15);
            padding: 15px 0;
            color: inherit;
        }
        
        .info-row:active {
            opacity: 0.6;
        }

        .info-row:last-child {
            border-bottom: none;
        }

        .info-label {
            color: #b3a5d8;
            font-size: 14px;
            margin-bottom: 4px;
            font-weight: 500;
        }

        .info-value {
            font-size: 18px;
            font-weight: 500;
            color: white;
        }

        /* Paylaş Butonu */
        .share-btn {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
            font-size: 18px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <div class="container-app">
        
        <!-- Profil Kısmı -->
        <div class="profile-pic">
            HP
        </div>
        
        <div class="title-small">
            BİLİNMEYEN
        </div>
        <div class="title-large">
            Hüseyin Polat
        </div>

        <!-- Hızlı İşlem Butonları -->
        <div class="action-buttons">
            <!-- Arama Butonu -->
            <a href="tel:+905055967758" class="action-btn" aria-label="Ara">
                <i class="fas fa-phone" style="transform: scaleX(-1);"></i>
            </a>
            <!-- WhatsApp Butonu -->
            <a href="https://wa.me/905055967758" target="_blank" class="action-btn" aria-label="WhatsApp">
                <i class="fab fa-whatsapp"></i>
            </a>
            <!-- Mail Butonu -->
            <a href="mailto:huseyinpol92@gmail.com" class="action-btn" aria-label="Mail Gönder">
                <i class="fas fa-envelope"></i>
            </a>
        </div>

        <!-- İletişim Bilgileri Listesi -->
        <div class="info-card">
            
            <!-- Telefon Numarası -->
            <a href="tel:+905055967758" class="info-row">
                <div class="info-label">cep</div>
                <div class="info-value">0 (505) 596 77 58</div>
            </a>
            
            <!-- Mail Adresi -->
            <a href="mailto:huseyinpol92@gmail.com" class="info-row">
                <div class="info-label">ev</div>
                <div class="info-value">huseyınpol92@gmail.com</div>
            </a>
            
            <!-- Konum (Google Maps) -->
            <a href="https://maps.app.goo.gl/ihq9y9mACX7A7Equ5" target="_blank" class="info-row py-4">
                <div class="info-label" style="font-size: 16px;">Konum</div>
            </a>
            
            <!-- Instagram -->
            <a href="https://www.instagram.com/apinefrin/" target="_blank" class="info-row py-4">
                <div class="info-label" style="font-size: 16px;">instagram</div>
            </a>

        </div>

    </div>

    <!-- Sağ Alt Paylaş İkonu (Görsel Maksatlı) -->
    <div class="share-btn">
        <i class="fas fa-arrow-up-from-bracket"></i>
    </div>

</body>
</html>
