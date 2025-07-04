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
            padding: 1.5rem 0;
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
            font-size: 2rem;
        }
        
        .artworks {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 2rem;
        }
        
        .artwork {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            display: flex;
            flex-direction: column;
        }
        
        .artwork:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15);
        }
        
        .artwork-img-container {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #f0f0f0;
            padding: 1rem;
            min-height: 250px;
        }
        
        .artwork-img {
            max-width: 100%;
            max-height: 300px;
            width: auto;
            height: auto;
            object-fit: contain;
            border-radius: 4px;
        }
        
        .artwork-info {
            padding: 1.2rem;
            flex-grow: 1;
        }
        
        .artwork-title {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: #2c3e50;
        }
        
        .artwork-author {
            color: #7f8c8d;
            margin-bottom: 0.8rem;
            font-style: italic;
        }
        
        .artwork-desc {
            color: #34495e;
            line-height: 1.5;
            font-size: 0.95rem;
        }
        
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }
        
        .footer-links {
            margin-top: 1rem;
        }
        
        .footer-links a {
            color: #ecf0f1;
            margin: 0 10px;
            text-decoration: none;
        }
        
        .footer-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Галерея "Мир Картины"</h1>
        <p>Коллекция уникальных художественных произведений</p>
    </header>
    
    <div class="gallery-container">
        <h2 class="gallery-title">Коллекция картин</h2>
        
        <div class="artworks">
            <!-- Картины расположены в обратном порядке -->
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/tZGN4rRR/image.jpg" alt="Картина 19" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 19</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/PNhMGFF2/image.jpg" alt="Картина 18" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 18</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/R61Q6cq7/image.jpg" alt="Картина 17" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 17</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/4HJvzmhr/image.jpg" alt="Картина 16" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 16</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/06wCxgsH/image.jpg" alt="Картина 15" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 15</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/dhDBHkSF/image.jpg" alt="Картина 14" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 14</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/HV6z94z3/image.jpg" alt="Картина 13" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 13</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/Yhr8Fy6h/image.jpg" alt="Картина 12" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 12</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/mhGmLrh3/image.jpg" alt="Картина 11" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 11</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/WqnFj8zy/image.jpg" alt="Картина 10" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 10</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/Sj7DJpzB/image.jpg" alt="Картина 9" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 9</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/3074PV8p/image.jpg" alt="Картина 8" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 8</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/JDjHYMLM/image.jpg" alt="Картина 7" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 7</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/5HhFmjDs/image.jpg" alt="Картина 6" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 6</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/2qbZvn9q/image.jpg" alt="Картина 5" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 5</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/zbw3S7Cf/image.jpg" alt="Картина 4" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 4</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/jwYL7mJ9/image.jpg" alt="Картина 3" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 3</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/XZCrX4Xd/image.jpg" alt="Картина 2" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 2</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
            
            <div class="artwork">
                <div class="artwork-img-container">
                    <img src="https://i.postimg.cc/5XGHx69f/image.jpg" alt="Картина 1" class="artwork-img">
                </div>
                <div class="artwork-info">
                    <h3 class="artwork-title">Картина 1</h3>
                    <p class="artwork-author">Автор: Художник</p>
                    <p class="artwork-desc">Описание картины будет здесь.</p>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>© 2025 Галерея "Мир Картины". Все права защищены.</p>
        <div class="footer-links">
            <a href="#">О галерее</a>
            <a href="#">Контакты</a>
            <a href="#">Правила посещения</a>
        </div>
    </footer>
</body>
</html>
