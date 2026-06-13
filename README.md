<p align="center">
  <a href="/README.en.md">🇺🇸 English</a> •
  <a href="/README.md"><b>🇷🇺 Русский</b></a> •
  <a href="/README.zh.md">🇨🇳 简体中文</a> •
  <a href="/README.zh-TW.md">🇹🇼 繁體中文</a> •
  <a href="/README.fa.md">🇮🇷 فارسی</a> •
  <a href="/README.es.md">🇪🇸 Español</a>
</p>

<p align="center">
  <a href="https://github.com/JINXPIL/json-yaml-ai/releases">
    <img src="https://img.shields.io/github/v/release/jinxpil/json-yaml-ai?style=for-the-badge&logo=github&color=181717" alt="Release">
  </a>
  <a href="https://github.com/JINXPIL/json-yaml-ai/releases/latest">
    <img src="https://img.shields.io/github/downloads/jinxpil/json-yaml-ai/total?style=for-the-badge&color=brightgreen" alt="Downloads">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License">
  </a>
  <a href="https://github.com/JINXPIL/json-yaml-ai/stargazers">
    <img src="https://img.shields.io/github/stars/jinxpil/json-yaml-ai?style=for-the-badge&color=yellow" alt="Stars">
  </a>
</p>

<h1 align="center">🧠 Ultimate JSON/YAML Academy v26.0</h1>

<p align="center">
  <b>Ультимативная локальная среда разработки (IDE), интерактивный курс и ИИ-помощник в одном файле.</b><br>
  <i>Валидация JSON, конвертация в YAML, генерация HAPP-ссылок и Base64 без серверов и баз данных.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON">
  <img src="https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white" alt="YAML">
</p>

<p align="center">
  <a href="https://jinxpil.github.io/json-yaml-ai/">
    <img src="https://img.shields.io/badge/🚀_ОТКРЫТЬ_WEB--ВЕРСИЮ-0052FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open Web Version">
  </a>
</p>

> [!IMPORTANT]
> **Zero-Trust & 100% Offline.** Приложение представляет собой единый монолитный HTML-файл. Все вычисления, ИИ-анализ, генерация ссылок и парсинг происходят **строго локально в оперативной памяти вашего устройства**. Никакие ваши конфиги или данные не отправляются в интернет.

> [!TIP]
> **PWA & Mobile Ready:** Откройте сайт на смартфоне (iOS/Android) и нажмите «Добавить на главный экран». Приложение установится как полноценная нативная программа, которая будет работать даже в авиарежиме!

---

### 🔥 Главные функции (Что внутри?)

* 🤖 **Offline AI-Assistant:** Встроенный чат-бот, который умеет проверять ваш код. Просто перетащите `.json` файл в чат или напишите *"исправь код"*, и алгоритм автоматически найдет и починит синтаксические ошибки (висячие запятые, одинарные кавычки, комментарии).
* 🎓 **Интерактивная Академия:** Встроенный курс из 15 шагов: от базовых типов JSON до сложных конфигураций Proxy-маршрутизации (Outbounds, Rules, Clash API) и финального Экзамена.
* 🚀 **Конструктор HAPP / Base64:** Мгновенное сжатие (Minify) вашего кода и генерация `happ://routing/...` диплипнков для быстрой имплементации правил маршрутизации в клиенты (v2Ray, Sing-box).
* 🎨 **Ultimate UI (Resizability):** Абсолютная свобода интерфейса. Каждое окно можно растягивать в любые стороны. Настраиваемые цвета (Custom Themes), экспорт/импорт дизайна и масштабирование шрифта через `rem`.
* 🔗 **Share & Iframe:** Написали крутой конфиг? Нажмите *"Поделиться"*, и приложение сгенерирует URL, внутри которого зашифрован ваш код. Или скопируйте Iframe-код для встраивания редактора на свой сайт!
* 📝 **System Logger:** Профессиональная вкладка детальных логов (с точностью до миллисекунд) для отладки процессов с возможностью выгрузки в `.txt`.
* 🌍 **Мультиязычность (i18n):** Мгновенное переключение всего интерфейса на 6 языков (включая RTL-поддержку для арабской вязи).

---

### 📸 Интерфейс

<p align="center">
  <i>(Здесь будут ваши скриншоты. Загрузите пару красивых скринов приложения в папку `media` вашего репозитория и обновите эти ссылки)</i>
  <br><br>
  <img alt="Editor View" src="https://via.placeholder.com/800x400.png?text=Скриншот+Редактора+Кода" width="48%">
  <img alt="AI Chat View" src="https://via.placeholder.com/800x400.png?text=Скриншот+ИИ+Чата" width="48%">
</p>

---

### 🛠️ Инструкция по использованию HAPP-генератора

Инструмент идеально подходит для создания кастомных правил обхода блокировок для VPN/Proxy клиентов.
1. Откройте вкладку **Редактор Кода**.
2. Выберите урок **12 (Routing Rules)** или вставьте свой конфиг маршрутизации в окно слева.
3. Проверьте синтаксис кнопкой `⚙️ Проверить JSON`.
4. Нажмите `🚀 HAPP`.
5. Приложение удалит все пробелы, переведет конфиг в Base64 (UTF-8 safe) и скопирует в буфер обмена готовую ссылку вида `happ://routing/onadd/eyJ...`.
6. Вставьте ссылку в ваш клиент.

---

### 📥 Установка и Запуск

Приложение не требует установки Node.js, серверов или баз данных. 

1. Скачайте `index.html` из последнего [Релиза](https://github.com/JINXPIL/json-yaml-ai/releases).
2. Кликните по файлу дважды, чтобы открыть его в любом браузере (Chrome, Edge, Safari).
3. **Или** просто пользуйтесь [Web-версией](https://jinxpil.github.io/json-yaml-ai/) напрямую из репозитория!

---

### ⭐ Поддержка проекта

**Если JSON/YAML Academy помогла вам разобраться в синтаксисе или ускорила настройку прокси, пожалуйста, поставьте звезду этому репозиторию! Это лучшая мотивация.** :star2:

[![Stargazers over time](https://starchart.cc/JINXPIL/json-yaml-ai.svg?variant=adaptive)](https://starchart.cc/JINXPIL/json-yaml-ai)
