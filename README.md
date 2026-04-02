<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DressCoder — Политика конфиденциальности</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: #0A0A0A;
            color: #E0E0E0;
            line-height: 1.7;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        h1 {
            font-size: 28px;
            font-weight: 900;
            color: #F8CA1F;
            letter-spacing: 1px;
            margin-bottom: 8px;
        }
        .subtitle {
            font-size: 12px;
            color: rgba(255,255,255,0.4);
            letter-spacing: 3px;
            text-transform: uppercase;
            margin-bottom: 32px;
        }
        h2 {
            font-size: 18px;
            font-weight: 800;
            color: #F8CA1F;
            margin-top: 32px;
            margin-bottom: 12px;
            padding-left: 12px;
            border-left: 3px solid #C11702;
        }
        h3 {
            font-size: 15px;
            font-weight: 700;
            color: #E8572A;
            margin-top: 20px;
            margin-bottom: 8px;
        }
        p, li {
            font-size: 14px;
            color: rgba(255,255,255,0.7);
            margin-bottom: 10px;
        }
        ul {
            padding-left: 20px;
            margin-bottom: 12px;
        }
        li { margin-bottom: 6px; }
        .highlight {
            background: rgba(248, 202, 31, 0.08);
            border: 1px solid rgba(248, 202, 31, 0.15);
            padding: 14px 16px;
            margin: 16px 0;
            font-size: 14px;
        }
        .section { margin-bottom: 24px; }
        a { color: #F8CA1F; text-decoration: none; }
        a:hover { text-decoration: underline; }
        .footer {
            margin-top: 48px;
            padding-top: 20px;
            border-top: 1px solid rgba(255,255,255,0.08);
            font-size: 12px;
            color: rgba(255,255,255,0.3);
        }
    </style>
</head>
<body>

<h1>Политика конфиденциальности</h1>
<p class="subtitle">DressCoder &mdash; AI-стилист</p>

<div class="highlight">
    DressCoder уважает вашу приватность. Ваш гардероб, фотографии и предпочтения хранятся только на вашем устройстве и никогда не передаются на наши серверы.
</div>

<div class="section">
    <h2>1. Какие данные мы собираем</h2>

    <h3>1.1. Данные аккаунта</h3>
    <p>При регистрации мы собираем:</p>
    <ul>
        <li><strong>Имя</strong> &mdash; отображается в вашем профиле</li>
        <li><strong>Адрес электронной почты</strong> &mdash; используется для входа и восстановления пароля</li>
        <li><strong>Пароль</strong> &mdash; хранится в зашифрованном виде в Firebase Authentication</li>
    </ul>
    <p>При входе через Google или Apple мы получаем только имя и email, предоставленные этими сервисами.</p>

    <h3>1.2. Фотографии</h3>
    <p>Вы можете загружать фотографии одежды через камеру или галерею. Все фотографии:</p>
    <ul>
        <li>Хранятся <strong>только на вашем устройстве</strong></li>
        <li>Обрабатываются AI <strong>локально на устройстве</strong> (без отправки на серверы)</li>
        <li>Никогда не передаются третьим лицам</li>
    </ul>

    <h3>1.3. Данные гардероба</h3>
    <p>Информация о ваших вещах (тип, цвет, стиль, паттерн) и сохранённых образах хранится <strong>исключительно на вашем устройстве</strong> в локальных файлах приложения.</p>

    <h3>1.4. Данные обучения AI</h3>
    <p>Приложение запоминает ваши предпочтения для улучшения рекомендаций:</p>
    <ul>
        <li>Исправления AI-классификации (когда вы меняете тип вещи)</li>
        <li>Предпочтения по стилям и цветам</li>
        <li>Статистика сохранённых образов</li>
    </ul>
    <p>Эти данные хранятся <strong>локально</strong> и используются только для персонализации подборок.</p>

    <h3>1.5. Фото профиля</h3>
    <p>Аватар профиля хранится <strong>только на вашем устройстве</strong> и не загружается в облако.</p>
</div>

<div class="section">
    <h2>2. Как мы используем данные</h2>
    <ul>
        <li><strong>Аутентификация</strong> &mdash; email и пароль для входа в приложение</li>
        <li><strong>AI-классификация</strong> &mdash; анализ фотографий одежды для определения типа, цвета и стиля. Выполняется полностью на устройстве с помощью Core ML</li>
        <li><strong>Генерация образов</strong> &mdash; подбор сочетаний одежды на основе вашего гардероба и предпочтений</li>
        <li><strong>Персонализация</strong> &mdash; адаптация рекомендаций на основе ваших действий</li>
        <li><strong>Уведомления</strong> &mdash; напоминания о подборе образа (по вашему выбору)</li>
    </ul>
</div>

<div class="section">
    <h2>3. Сторонние сервисы</h2>

    <h3>3.1. Firebase (Google)</h3>
    <p>Мы используем следующие сервисы Firebase:</p>
    <ul>
        <li><strong>Firebase Authentication</strong> &mdash; для безопасной аутентификации пользователей</li>
        <li><strong>Cloud Firestore</strong> &mdash; для хранения новостных статей и историй (контент от редакции, не ваши личные данные)</li>
    </ul>
    <p>Firebase Analytics в нашем приложении <strong>отключена</strong>. Мы не собираем аналитику и не отслеживаем ваше поведение.</p>
    <p>Политика конфиденциальности Google: <a href="https://policies.google.com/privacy">policies.google.com/privacy</a></p>

    <h3>3.2. Google Sign-In</h3>
    <p>При входе через Google мы получаем только ваше имя и email. Мы не получаем доступа к вашим контактам, файлам или другим данным Google-аккаунта.</p>

    <h3>3.3. Apple Sign-In</h3>
    <p>При входе через Apple мы получаем имя и email (или скрытый email, если вы выберете эту опцию). Apple не передаёт нам дополнительных данных.</p>
</div>

<div class="section">
    <h2>4. Хранение данных</h2>

    <div class="highlight">
        <strong>Локально на устройстве:</strong> фотографии одежды, данные гардероба, сохранённые образы, предпочтения AI, аватар профиля.<br><br>
        <strong>В облаке (Firebase):</strong> только данные аутентификации (email, имя) и редакционный контент (новости, истории).
    </div>

    <p>Ваши персональные данные гардероба <strong>не синхронизируются</strong> между устройствами и не загружаются на серверы.</p>
</div>

<div class="section">
    <h2>5. Камера и фотографии</h2>
    <p>Приложение запрашивает доступ к камере для фотографирования вещей. Доступ к галерее запрашивается для выбора существующих фотографий.</p>
    <p>Все фотографии обрабатываются исключительно на устройстве:</p>
    <ul>
        <li>Удаление фона &mdash; локально с помощью Apple Vision</li>
        <li>Определение типа одежды &mdash; локально с помощью Core ML</li>
        <li>Анализ цветов &mdash; локально</li>
    </ul>
    <p><strong>Ни одна фотография не покидает ваше устройство.</strong></p>
</div>

<div class="section">
    <h2>6. Уведомления</h2>
    <p>Приложение использует <strong>локальные уведомления</strong> (не push-уведомления с сервера):</p>
    <ul>
        <li><strong>Утреннее напоминание</strong> (07:00) &mdash; беззвучное предложение собрать образ</li>
        <li><strong>Субботний совет</strong> (15:00) &mdash; напоминание о модных советах</li>
    </ul>
    <p>Оба типа уведомлений можно включить или выключить в настройках приложения. Разрешение на отправку запрашивается только один раз при первом запуске.</p>
</div>

<div class="section">
    <h2>7. Безопасность</h2>
    <ul>
        <li>Пароли хранятся в зашифрованном виде через Firebase Authentication</li>
        <li>Вход через Apple использует криптографический nonce (SHA-256)</li>
        <li>Локальные данные защищены стандартными механизмами iOS (sandbox)</li>
        <li>Приложение не использует незащищённые сетевые соединения</li>
    </ul>
</div>

<div class="section">
    <h2>8. Права пользователя</h2>
    <p>Вы можете в любой момент:</p>
    <ul>
        <li><strong>Удалить данные гардероба</strong> &mdash; через функцию очистки в приложении</li>
        <li><strong>Удалить аккаунт</strong> &mdash; связавшись с нами по email</li>
        <li><strong>Отключить уведомления</strong> &mdash; в настройках приложения или в настройках iOS</li>
        <li><strong>Отозвать доступ к камере</strong> &mdash; в системных настройках iOS</li>
    </ul>
</div>

<div class="section">
    <h2>9. Дети</h2>
    <p>DressCoder не предназначен для детей младше 13 лет. Мы сознательно не собираем данные несовершеннолетних. Если вы обнаружите, что ребёнок предоставил нам свои данные, свяжитесь с нами для их удаления.</p>
</div>

<div class="section">
    <h2>10. Изменения политики</h2>
    <p>Мы можем обновлять данную политику. Актуальная версия всегда доступна в приложении и на этой странице. При существенных изменениях мы уведомим вас через приложение.</p>
</div>

<div class="section">
    <h2>11. Контакты</h2>
    <p>По всем вопросам, связанным с конфиденциальностью:</p>
    <p><strong>Email:</strong> <a href="mailto:fhjjytddtubvdrgvs@gmail.com">fhjjytddtubvdrgvs@gmail.com</a></p>
</div>

<div class="footer">
    <p>Последнее обновление: 14 марта 2026 г.</p>
    <p>DressCoder &copy; 2026. Все права защищены.</p>
</div>

</body>
</html>
