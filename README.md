<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пётр — Профиль разработчика</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&display=swap');

        :root {
            --bg: linear-gradient(135deg, #a89cc9, #6a5a8a);
            --surface: #ffffff;
            --primary: #6366f1;
            --primary-hover: #4f46e5;
            --text: #1e293b;
            --text-secondary: #64748b;
            --border: #e2e8f0;
            --shadow: 0 25px 50px -12px rgba(0,0,0,0.05);
            --radius: 20px;
            --transition: 0.25s cubic-bezier(0.4, 0, 0.2, 1);
            --font: 'Nunito', system-ui, -apple-system, sans-serif;
        }

        body.dark {
            --bg: #0f172a;
            --surface: #1e293b;
            --primary: #818cf8;
            --primary-hover: #6366f1;
            --text: #f1f5f9;
            --text-secondary: #94a3b8;
            --border: #334155;
            --shadow: 0 25px 50px -12px rgba(0,0,0,0.4);
        }

        * { margin:0; padding:0; box-sizing:border-box; }

        body {
            font-family: var(--font);
            background: var(--bg);
            color: var(--text);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff8a8a, #a89cc9);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--text-secondary);
            margin-bottom: 20px;
        }

        .lang-switch {
            display: flex;
            justify-content: flex-end;
            gap: 10px;
            margin-bottom: 30px;
        }

        .lang-btn {
            padding: 8px 16px;
            border: none;
            border-radius: 10px;
            background: rgba(255, 255, 255, 0.8);
            cursor: pointer;
            transition: all var(--transition);
        }

        .lang-btn:hover {
            background: rgba(255, 255, 255, 1);
            transform: translateY(-2px);
        }

        .lang-btn.active {
            background: var(--primary);
            color: white;
        }

        .section {
            background: var(--surface);
            border-radius: var(--radius);
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: var(--shadow);
        }

        .section h2 {
            margin-bottom: 20px;
            color: var(--primary);
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
        }

        .skill-item {
            padding: 15px;
            text-align: center;
            border-radius: 10px;
            background: rgba(99, 102, 241, 0.05);
            transition: all var(--transition);
            position: relative;
            overflow: hidden;
        }

        .skill-item:hover {
            transform: translateY(-5px);
            background: rgba(99, 102, 241, 0.1);
        }

        .skill-icon {
            width: 32px;
            height: 32px;
            margin: 0 auto 10px;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .project-card {
            border: 1px solid var(--border);
            border-radius: 15px;
            overflow: hidden;
            transition: all var(--transition);
            position: relative;
        }

        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .project-content {
            padding: 20px;
        }

        .project-title {
            font-weight: 700;
            margin-bottom: 10px;
            color: var(--primary);
        }

        .contact-info {
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.3);
            color: rgba(255, 255, 255, 0.7);
        }

        /* Анимации */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* SVG стили */
        .svg-icon {
            width: 24px;
            height: 24px;
            fill: var(--primary);
            transition: transform var(--transition);
        }

        .svg-icon:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Пётр</h1>
            <p class="subtitle">Мне 12 лет, и я люблю программировать</p>
            <div class="lang-switch">
                <button class="lang-btn active" onclick="switchLanguage('ru')">RU</button>
                <button class="lang-btn" onclick="switchLanguage('en')">EN</button>
            </div>
        </header>

        <section class="section">
            <h2>Обо мне</h2>
            <p>Наш девиз: «Чтоб сгорела наша школа» (шутка). А если серьёзно, мне нравятся мемы про Меллстроя.</p>
            <p>Использую VS Code, PyCharm, Visual Studio. Пишу код несколько раз в день по часу.</p>
        </section>

        <section class="section">
            <h2>Навыки</h2>
            <div class="skills-grid">
                <!-- HTML/CSS -->
                <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path fill="currentColor" d="M12 2L4 6v12l8 4 8-4V6l-8-4zm0 14.5l-6-3v-9l6 3 6-3v9l-6 3z"/>
                </svg>
                HTML/CSS
            </div>


            <!-- JavaScript -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path fill="currentColor" d="M10 4h4v4h-4zm6 0h4v4h-4zM6 10h4v4H6zm4 6h4v4h-4z"/>
                </svg>
                JavaScript
            </div>

            <!-- Python -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path fill="currentColor" d="M8 6h8v2H8zm0 4h8v2H8zm0 4h8v2H8z"/>
                </svg>
                Python
            </div>

            <!-- SQLite3 -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path fill="currentColor" d="M4 4h16v16H4zm2 2v12h12V6z"/>
                </svg>
                SQLite3
            </div>

            <!-- Flask -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <circle cx="12" cy="12" r="8" fill="currentColor"/>
                </svg>
                Flask
            </div>

            <!-- C++ -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path fill="currentColor" d="M6 6h12v2H6zm0 4h12v2H6zm0 4h12v2H6z"/>
                </svg>
                C++
            </div>

            <!-- C# -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path fill="currentColor" d="M8 8h8v8H8z"/>
                </svg>
                C#
            </div>

            <!-- GAVA -->
            <div class="skill-item">
                <svg class="skill-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <!-- Абстрактная иконка для GAVA -->
                    <circle cx="12" cy="12" r="10" fill="none" stroke="currentColor" stroke-width="2"/>
            <line x1="8" y1="12" x2="16" y2="12" stroke="currentColor" stroke-width="2"/>
            <line x1="12" y1="8" x2="12" y2="16" stroke="currentColor" stroke-width="2"/>
                </svg>
                GAVA
            </div>
        </div>
    </section>

    <section class="section">
        <h2>Проекты</h2>
        <div class="projects-grid">
            <!-- Проект GAVA -->
            <div class="project-card">
                <div class="project-content">
                    <h3 class="project-title">GAVA</h3>
                    <p>Мой язык программирования на C++</p>
            <a href="https://github.com/wassss337/gava" class="btn" target="_blank">GitHub</a>
                </div>
            </div>

            <!-- Проект Utils for C++20 -->
            <div class="project-card">
                <div class="project-content">
                    <h3 class="project-title">Utils for C++20</h3>
            <p>Набор void‑функций, облегчающих работу</p>
            <a href="https://github.com/wassss337/utils-for-C-17---C-20" class="btn" target="_blank">GitHub</a>
                </div>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>Контакты</h2>
        <p class="contact-info">Почта (Яндекс): mamkin-nagibator10000@yandex.ru</p>
        <form class="contact-form">
            <input type="text" id="name" placeholder="Ваше имя" required class="input-field">
            <input type="email" id="email" placeholder="Ваш email" required class="input-field">
            <textarea id="message" placeholder="Сообщение" rows="4" required class="input-field"></textarea>
            <button type="submit" id="submitBtn" class="btn">Отправить</button>
        </form>
    </section>
</div>

<footer>
    <p>© 2024 Пётр. Все права защищены.</p>
</footer>

<script>
    // Переключение языка
    function switchLanguage(lang) {
        const buttons = document.querySelectorAll('.lang-btn');
        buttons.forEach(btn => btn.classList.remove('active'));
        event.target.classList.add('active');

        // Здесь можно добавить логику переключения контента на другой язык
        console.log('Выбран язык:', lang);
    }

    // Анимация появления элементов при загрузке
    document.addEventListener('DOMContentLoaded', function() {
        const sections = document.querySelectorAll('.section');
        sections.forEach((section, index) => {
            section.style.animation = `fadeIn 0.5s ease ${index * 0.2}s forwards`;
        });
    });
</script>
</body>
</html>
                
