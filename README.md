<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Галерея "Мир Картины"</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
        }
        
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        
        .gallery-container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        
        .gallery-title {
            text-align: center;
            margin-bottom: 2rem;
            color: #2c3e50;
        }
        
        .artworks {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .artwork {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            display: flex;
            flex-direction: column;
        }
        
        .artwork:hover {
            transform: translateY(-5px);
        }
        
        .artwork-img-container {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #f0f0f0;
            padding: 1rem;
        }
        
        .artwork-img {
            max-width: 100%;
            max-height: 300px;
            width: auto;
            height: auto;
            object-fit: contain;
        }
        
        .artwork-info {
            padding: 1rem;
            flex-grow: 1;
        }
        
        .artwork-title {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: #2c3e50;
        }
        
        .artwork-author {
            color: #7f8c8d;
            margin-bottom: 0.5rem;
        }
        
        .artwork-desc {
            color: #34495e;
            line-height: 1.5;
        }
        
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Мир Картины</h1>
        <p>Галерея прекрасных произведений искусства</p>
    </header>
    
    <div class="gallery-container">
        <h2 class="gallery-title">Наши картины</h2>
        
        <div class="artworks">
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/4m2SW5dB/image.jpg" alt="Загадочный пейзаж" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Загадочный пейзаж</h3>
                    <p class="artwork-author">Автор: Неизвестен</p>
                    <p class="artwork-desc">Прекрасный пейзаж с загадочной атмосферой, передающий глубину природы и человеческих эмоций.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/8z7W7ZxT/art2.jpg" alt="Городские огни" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Городские огни</h3>
                    <p class="artwork-author">Автор: Мария Иванова</p>
                    <p class="artwork-desc">Яркая картина, изображающая ночной город с его огнями и движением.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/J4Y7k1XH/art3.jpg" alt="Морской бриз" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Морской бриз</h3>
                    <p class="artwork-author">Автор: Алексей Петров</p>
                    <p class="artwork-desc">Свежесть морского воздуха и мощь океана переданы в этой удивительной работе.</p>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>© 2023 Галерея "Мир Картины". Все права защищены.</p>
        <p>Контакт: info@mir-kartiny.ru</p>
    </footer>
</body>
</html>
