<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DigiApp SassPro - README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #000;
            background: #f5f5f5;
            padding: 20px;
            min-height: 100vh;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            border: 1px solid #ddd;
        }

        .header {
            background: #000;
            color: white;
            padding: 50px 40px;
            text-align: center;
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            font-weight: 700;
        }

        .header p {
            font-size: 1.2em;
            opacity: 0.9;
        }

        .content {
            padding: 40px;
        }

        h2 {
            color: #000;
            margin-top: 40px;
            margin-bottom: 20px;
            font-size: 2em;
            border-bottom: 3px solid #000;
            padding-bottom: 10px;
        }

        h3 {
            color: #333;
            margin-top: 25px;
            margin-bottom: 15px;
            font-size: 1.5em;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .feature-card {
            background: #000;
            color: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            border: 1px solid #333;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-card h3 {
            color: white;
            margin-top: 0;
            font-size: 1.3em;
        }

        .tech-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }

        .badge {
            background: #000;
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: 600;
            border: 1px solid #333;
        }

        .code-block {
            background: #f5f5f5;
            color: #000;
            padding: 20px;
            border-radius: 8px;
            overflow-x: auto;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
            border: 1px solid #ddd;
        }

        .code-block code {
            color: #000;
        }

        .project-structure {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #000;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
            font-size: 0.9em;
        }

        .modules {
            display: grid;
            gap: 15px;
            margin: 20px 0;
        }

        .module-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #000;
        }

        .module-item strong {
            color: #000;
        }

        .screenshot {
            margin: 30px 0;
            text-align: center;
        }

        .screenshot img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .footer {
            background: #000;
            color: white;
            padding: 30px 40px;
            text-align: center;
        }

        .footer a {
            color: #ccc;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
            color: white;
        }

        .footer hr {
            border: none;
            border-top: 1px solid #333;
            margin: 20px 0;
        }

        ul {
            margin: 15px 0;
            padding-left: 30px;
        }

        li {
            margin: 10px 0;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }

            .content {
                padding: 20px;
            }

            h2 {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🚀 DigiApp SassPro</h1>
            <p>Modern ve Responsive Web Uygulaması</p>
        </div>

        <div class="content">
            <h2>📋 Özellikler</h2>
            <div class="features">
                <div class="feature-card">
                    <h3>✨ Modern Tasarım</h3>
                    <p>Güncel ve şık kullanıcı arayüzü</p>
                </div>
                <div class="feature-card">
                    <h3>📱 Responsive</h3>
                    <p>Tüm cihazlarda mükemmel görünüm</p>
                </div>
                <div class="feature-card">
                    <h3>🎨 SCSS</h3>
                    <p>Modüler ve organize CSS yapısı</p>
                </div>
                <div class="feature-card">
                    <h3>🚀 Optimize</h3>
                    <p>Hızlı yüklenme ve performans</p>
                </div>
            </div>

            <h2>🛠️ Teknolojiler</h2>
            <div class="tech-badges">
                <span class="badge">HTML5</span>
                <span class="badge">CSS3</span>
                <span class="badge">SCSS</span>
                <span class="badge">Remix Icon</span>
                <span class="badge">Live Sass Compiler</span>
            </div>

            <h2>📁 Proje Yapısı</h2>
            <div class="project-structure">
digiapp-sasspro/
│
├── assets/
│   ├── about.png
│   ├── feedback-1.jpg
│   ├── feedback-2.jpg
│   ├── feedback-3.jpg
│   ├── feedback-4.jpg
│   ├── hero.png
│   ├── logo.avif
│   └── portfolio.jpg
│
├── styles/
│   ├── _about.scss
│   ├── _feedback.scss
│   ├── _footer.scss
│   ├── _header.scss
│   ├── _hero.scss
│   ├── _mixin.scss
│   ├── _newsletter.scss
│   ├── _portfolio.scss
│   ├── _reset.scss
│   ├── _service.scss
│   ├── _variables.scss
│   ├── style.scss
│   ├── style.css
│   └── style.css.map
│
├── index.html
├── digiapp.gif
└── digiapp.png
            </div>

            <h2>🚀 Kurulum</h2>
            <div class="code-block">
# Projeyi klonlayın
git clone https://github.com/kenansonmez1617-hub/digiapp-sasspro.git

# Proje dizinine gidin
cd digiapp-sasspro

# index.html dosyasını tarayıcıda açın
            </div>

            <h2>💻 Geliştirme</h2>
            <p>SCSS dosyalarını düzenlemek için:</p>
            <ol>
                <li>VS Code'da Live Sass Compiler eklentisini yükleyin</li>
                <li><code>styles/style.scss</code> dosyasını açın</li>
                <li>"Watch Sass" butonuna tıklayın</li>
                <li>SCSS dosyalarınızı düzenleyin, otomatik olarak CSS'e derlenecektir</li>
            </ol>

            <h2>📸 Proje Önizleme</h2>
            <div class="screenshot">
                <img src="digiapp.png" alt="DigiApp Proje Önizleme">
            </div>
            
            <h2>⚙️ Canlı Demo</h2>
            <div class="screenshot">
                <img src="digiapp.gif" alt="DigiApp Canlı Demo">
            </div>

            <h2>🎨 SCSS Modülleri</h2>
            <div class="modules">
                <div class="module-item">
                    <strong>_variables.scss:</strong> Renk, font ve genel değişkenler
                </div>
                <div class="module-item">
                    <strong>_mixin.scss:</strong> Tekrar kullanılabilir SCSS mixin'leri
                </div>
                <div class="module-item">
                    <strong>_reset.scss:</strong> CSS reset ve temel stiller
                </div>
                <div class="module-item">
                    <strong>_header.scss:</strong> Header/navigasyon stilleri
                </div>
                <div class="module-item">
                    <strong>_hero.scss:</strong> Ana banner/hero bölümü
                </div>
                <div class="module-item">
                    <strong>_about.scss:</strong> Hakkında bölümü
                </div>
                <div class="module-item">
                    <strong>_service.scss:</strong> Hizmetler bölümü
                </div>
                <div class="module-item">
                    <strong>_portfolio.scss:</strong> Portfoy bölümü
                </div>
                <div class="module-item">
                    <strong>_feedback.scss:</strong> Geri bildirim/yorumlar bölümü
                </div>
                <div class="module-item">
                    <strong>_newsletter.scss:</strong> Bülten abonelik bölümü
                </div>
                <div class="module-item">
                    <strong>_footer.scss:</strong> Footer stilleri
                </div>
            </div>

            <h2>🤝 Katkıda Bulunma</h2>
            <ol>
                <li>Bu depoyu fork edin</li>
                <li>Yeni bir branch oluşturun (<code>git checkout -b feature/yeniOzellik</code>)</li>
                <li>Değişikliklerinizi commit edin (<code>git commit -am 'Yeni özellik eklendi'</code>)</li>
                <li>Branch'inizi push edin (<code>git push origin feature/yeniOzellik</code>)</li>
                <li>Pull Request oluşturun</li>
            </ol>
        </div>

        <div class="footer">
            <h3>🌟 Destek</h3>
            <p>Projeyi beğendiyseniz ⭐ vermeyi unutmayın!</p>
            <hr>
            <p align="center">
                <em>Son Güncelleme: 06 Şubat 2026</em><br>
                Made with ❤️ by Kenan Sönmez
            </p>
        </div>
    </div>
</body>
</html>