<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Полина ❤️ Кэтэлин</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ffe6ef, #fff5f8);
            color: #5c3042;
            text-align: center;
        }

        header {
            padding: 60px 20px 40px;
        }

        h1 {
            font-size: 50px;
            color: #d83f72;
            margin-bottom: 10px;
        }

        h2 {
            color: #b83c67;
            font-size: 30px;
            margin-top: 50px;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        .intro {
            max-width: 700px;
            margin: auto;
            padding: 20px;
        }

        .heart {
            font-size: 70px;
            animation: heartbeat 1.5s infinite;
        }

        @keyframes heartbeat {
            50% {
                transform: scale(1.2);
            }
        }

        .photos {
            max-width: 1100px;
            margin: 30px auto;
            padding: 20px;

            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .photo {
            background: white;
            padding: 12px;
            border-radius: 20px;

            box-shadow: 0 10px 30px rgba(180, 60, 100, 0.15);

            transition: 0.3s;
        }

        .photo:hover {
            transform: translateY(-8px);
        }

        .photo img {
            width: 100%;
            height: 300px;
            object-fit: cover;
            border-radius: 15px;
        }

        .photo p {
            margin-bottom: 5px;
            color: #c43f6d;
            font-weight: bold;
        }

        .date {
            margin: 50px auto;
            max-width: 700px;
            background: white;
            padding: 30px;
            border-radius: 25px;
            box-shadow: 0 10px 30px rgba(180, 60, 100, 0.15);
        }

        .date strong {
            color: #d83f72;
        }

        footer {
            margin-top: 60px;
            padding: 30px;
            background: #ffd9e6;
            color: #8d4a63;
        }

        @media (max-width: 800px) {
            h1 {
                font-size: 38px;
            }

            .photos {
                grid-template-columns: 1fr;
            }

            .photo img {
                height: 350px;
            }
        }
    </style>
</head>

<body>

<header>

    <div class="heart">❤️</div>

    <h1>Полина ❤️ Кэтэлин</h1>

    <div class="intro">
        <p>
            Наша маленькая история в фотографиях
        </p>

        <p>
            Мы познакомились <strong>5 ноября 2024 года</strong> 💕
        </p>

        <p>
            А встречаться начали <strong>1 марта 2025 года</strong> ❤️
        </p>
    </div>

</header>


<h2>📸 Наши фотографии</h2>


<div class="photos">

    <div class="photo">
        <img src="1.jpg" alt="Наша фотография">
        <p>Наш момент ❤️</p>
    </div>

    <div class="photo">
        <img src="photos/photo2.jpg" alt="Наша фотография">
        <p>Вместе 💕</p>
    </div>

    <div class="photo">
        <img src="photos/photo3.jpg" alt="Наша фотография">
        <p>Любимое воспоминание 🥰</p>
    </div>

    <div class="photo">
        <img src="photos/photo4.jpg" alt="Наша фотография">
        <p>Ещё один момент 🌸</p>
    </div>

    <div class="photo">
        <img src="photos/photo5.jpg" alt="Наша фотография">
        <p>Просто мы ❤️</p>
    </div>

    <div class="photo">
        <img src="photos/photo6.jpg" alt="Наша фотография">
        <p>Навсегда в памяти 💖</p>
    </div>

</div>


<div class="date">

    <h2>💕 Важные даты</h2>

    <p>
        🌸 Полина — <strong>05.05.2010</strong>
    </p>

    <p>
        💙 Кэтэлин — <strong>20.02.2008</strong>
    </p>

    <p>
        ✨ Знакомство — <strong>05.11.2024</strong>
    </p>

    <p>
        ❤️ Начало отношений — <strong>01.03.2025</strong>
    </p>

</div>


<footer>

    <p>
        Сделано с ❤️ для Полины
    </p>

    <p>
        Кэтэлин
    </p>

</footer>

</body>
</html>
