<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Симулятор: Собери ПК</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { background: #0f172a; color: #f8fafc; overflow-x: hidden; scroll-behavior: smooth; }
        
        /* Главный экран */
        .hero-section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(135deg, #1e1b4b 0%, #0f172a 100%);
            padding: 20px;
        }
        h1 { font-size: 3.5rem; margin-bottom: 20px; color: #38bdf8; text-shadow: 0 0 20px rgba(56, 189, 248, 0.2); }
        p { font-size: 1.2rem; max-width: 600px; margin-bottom: 40px; color: #94a3b8; line-height: 1.6; }
        
        /* Красивая кнопка с анимацией */
        .start-btn {
            padding: 15px 40px;
            font-size: 1.2rem;
            font-weight: bold;
            color: #fff;
            background: linear-gradient(90deg, #0ea5e9, #2563eb);
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            transition: transform 0.2s, box-shadow 0.2s;
            box-shadow: 0 4px 15px rgba(37, 99, 235, 0.4);
        }
        .start-btn:hover { transform: translateY(-3px); box-shadow: 0 8px 25px rgba(37, 99, 235, 0.6); }

        /* Интерактивная секция */
        .game-section { height: 100vh; display: flex; justify-content: center; align-items: center; background: #111827; }
        .game-placeholder { text-align: center; font-size: 2rem; color: #64748b; border: 3px dashed #334155; padding: 50px; border-radius: 20px; }
    </style>
</head>
<body>
<!-- ЭКРАН 1: Вводная часть -->
<section class="hero-section">
    <h1>Собери свой идеальный ПК</h1>
    <p>Добро пожаловать в интерактивный тренажер! Здесь вы узнаете, из чего состоит компьютер, проверите свои силы в сборке разных конфигураций и сможете посоревноваться в викторине на скорость с ботами.</p>
    <a href="#game" class="start-btn">Запустить симулятор</a>
</section>

<!-- ЭКРАН 2: Интерактивная часть -->
<section id="game" class="game-section">
    <div class="game-placeholder">
        🎮 Здесь будет зона сборки и выбора ПК
    </div>
</section>
</body>
</html>
