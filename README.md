# Yung543.github.io

<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Система контролю версій Git</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        h1 {
            color: #f1502f;
            border-bottom: 2px solid #f1502f;
            padding-bottom: 10px;
        }
        h2 {
            color: #2c3e50;
            margin-top: 30px;
        }
        p {
            margin-bottom: 15px;
        }
        ul, ol {
            margin-bottom: 20px;
            padding-left: 20px;
        }
        li {
            margin-bottom: 8px;
        }
        .command-list {
            list-style: none;
            padding: 0;
        }
        .command-item {
            background-color: #fff;
            border-left: 4px solid #f1502f;
            margin-bottom: 12px;
            padding: 12px 15px;
            border-radius: 0 4px 4px 0;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        code {
            background-color: #272822;
            color: #f8f8f2;
            padding: 3px 8px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
            font-size: 0.95em;
            display: inline-block;
            margin-bottom: 4px;
        }
        .command-description {
            margin: 0;
            color: #555;
        }
        .certificate-box {
            background-color: #eef9ff;
            border: 1px dashed #3498db;
            padding: 20px;
            text-align: center;
            border-radius: 6px;
            margin: 20px 0;
        }
        .certificate-box img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Система контролю версій Git</h1>
    </header>

    <main>
        <section>
            <h2>1. Що таке системи контролю версій та Git?</h2>
            <p>
                <strong>Система контролю версій (VCS — Version Control System)</strong> — це програмне забезпечення, яке допомагає розробникам відстежувати та керувати змінами в сирцевому коді проекту з часом.
            </p>
            <p>
                <strong>Git</strong> — це найпопулярніша розподілена система контролю версій, створена Лінусом Торвальдсом у 2005 році. На відміну від централізованих VCS, Git надає кожному розробнику повну копію історії проекту локально.
            </p>
        </section>

        <section>
            <h2>2. Основні можливості та переваги Git</h2>
            <ul>
                <li><strong>Розподілена архітектура:</strong> Кожен копіює локально повну історію проекту, що дозволяє працювати автономно без постійного підключення до мережі.</li>
                <li><strong>Швидкодія та ефективність:</strong> Git розроблений для швидкої обробки великих проектів.</li>
                <li><strong>Гнучке розгалуження (Branching):</strong> Легке створення та злиття гілок дозволяє паралельно розробляти нові функції чи виправляти помилки.</li>
                <li><strong>Висока надійність і цілісність:</strong> Зміни ідентифікуються за допомогою хеш-алгоритмів (SHA-1/SHA-256), що унеможливлює непомітну зміну даних.</li>
            </ul>
        </section>

        <section>
            <h2>3. 10 базових команд Git з коментарями</h2>
            <ul class="command-list">
                <li class="command-item">
                    <code>git init</code>
                    <p class="command-description">Ініціалізація нового локального репозиторію в поточній директорії.</p>
                </li>
                <li class="command-item">
                    <code>git clone &lt;url&gt;</code>
                    <p class="command-description">Клонування існуючого віддаленого репозиторію на локальний комп'ютер.</p>
                </li>
                <li class="command-item">
                    <code>git status</code>
                    <p class="command-description">Перегляд стану файлів (відстежувані, змінені, підготовлені до комміту).</p>
                </li>
                <li class="command-item">
                    <code>git add &lt;file_name&gt;</code> або <code>git add .</code>
                    <p class="command-description">Додавання зміненого файлу (або всіх файлів) до індексу (Staging Area).</p>
                </li>
                <li class="command-item">
                    <code>git commit -m "Опис змін"</code>
                    <p class="command-description">Фіксація збережених змін в історії репозиторію з повідомленням.</p>
                </li>
                <li class="command-item">
                    <code>git branch</code>
                    <p class="command-description">Перегляд списку гілок у репозиторії.</p>
                </li>
                <li class="command-item">
                    <code>git checkout -b &lt;name&gt;</code> (або <code>git switch -c &lt;name&gt;</code>)
                    <p class="command-description">Створення нової гілки та автоматичний перехід на неї.</p>
                </li>
                <li class="command-item">
                    <code>git merge &lt;branch_name&gt;</code>
                    <p class="command-description">Злиття вказаної гілки з поточною гілкою.</p>
                </li>
                <li class="command-item">
                    <code>git pull</code>
                    <p class="command-description">Отримання останніх змін із віддаленого репозиторію та їх злиття з локальною версією.</p>
                </li>
                <li class="command-item">
                    <code>git push origin &lt;branch_name&gt;</code>
                    <p class="command-description">Надсилання локальних коммітів до віддаленого репозиторію (наприклад, на GitHub).</p>
                </li>
            </ul>
        </section>

        <section>
            <h2>4. Сертифікат про проходження курсу по Git</h2>
            <div class="certificate-box">
                <p><em>(Примітка: замініть посилання в тегу &lt;img&gt; на ваше зображення або додайте скріншот сертифіката)</em></p>
                <!-- Замініть src="path/to/certificate.jpg" на реальне посилання -->
                <img src="https://via.placeholder.com/600x400?text=Сертифікат+Git" alt="Сертифікат про проходження курсу Git">
            </div>
        </section>

        <section>
            <h2>5. Джерела інформації</h2>
            <ul>
                <li><a href="https://git-scm.com/doc" target="_blank" rel="noopener noreferrer">Офіційна документація Git</a></li>
                <li><a href="https://learngitbranching.js.org/" target="_blank" rel="noopener noreferrer">Інтерактивний підручник «Learn Git Branching»</a></li>
                <li><a href="https://docs.github.com/" target="_blank" rel="noopener noreferrer">Документація GitHub Docs</a></li>
            </ul>
        </section>
    </main>

</body>
</html>
