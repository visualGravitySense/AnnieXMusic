<!-- ✨ Анимированный заголовок (Верх) -->

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</p>

<!-- 👤 Аватар + Печатающийся баннер -->

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://files.catbox.moe/r2ga8f.jpg" width="90px" style="border-radius: 50%;" />
      </td>
      <td>
        <img src="https://readme-typing-svg.herokuapp.com?color=00BFFF&width=600&lines=Привет!+Это+Certified+Coder+%F0%9F%A5%80+%E2%9D%97%EF%B8%8F" />
      </td>
    </tr>
  </table>
</div>

<!-- 👁 Счётчик посетителей -->

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=CertifiedCoders&style=flat-square" />
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=FF69B4&width=500&lines=Добро+пожаловать+в+Annie+%F0%9F%8E%B6+Робота;Ваш+лучший+музыкальный+Telegram+бот" />
</h1>

<p align="center">
  <a href="https://t.me/CertifiedCoders">
    <img src="https://files.catbox.moe/eh780q.jpg" width="600">
  </a>
</p>

<p align="center">
  <a href="https://t.me/AnnieXRobot"><img src="https://img.shields.io/badge/Попробовать%20бота-@AnnieXRobot-blue?style=for-the-badge&logo=telegram"/></a>
</p>

<p align="center">
  <a href="https://github.com/CertifiedCoders/AnnieXMusic/stargazers"><img src="https://img.shields.io/github/stars/CertifiedCoders/AnnieXMusic?style=flat-square"/></a>
  <a href="https://github.com/CertifiedCoders/AnnieXMusic/network/members"><img src="https://img.shields.io/github/forks/CertifiedCoders/AnnieXMusic?style=flat-square"/></a>
  <a href="https://github.com/CertifiedCoders/AnnieXMusic/issues"><img src="https://img.shields.io/github/issues/CertifiedCoders/AnnieXMusic?style=flat-square"/></a>
  <a href="https://github.com/CertifiedCoders/AnnieXMusic/commits/main"><img src="https://img.shields.io/github/last-commit/CertifiedCoders/AnnieXMusic?style=flat-square"/></a>
  <a href="https://github.com/CertifiedCoders/AnnieXMusic/actions"><img src="https://img.shields.io/badge/CI-Статус-grey?style=flat-square"/></a>
</p>

## 🌟 Что такое AnnieXMusic?

**AnnieXMusic** — это современный Telegram-бот, который транслирует **музыку высокого качества** в голосовые чаты групп.
Работает на базе **Pyrogram + PyTgCalls** и поддерживает множество платформ, таких как **YouTube, Spotify, Apple Music, SoundCloud, Resso и другие**.
Также включает **базовые функции управления группами** для удобства.

## 🚀 Возможности

<table>
<tr>
<td>
  <img src="https://files.catbox.moe/la0sxq.jpg" width="300" />
</td>
<td>

| 🌟 Функция               | 🔎 Описание                                    |
| ------------------------ | ---------------------------------------------- |
| 🎶 Стриминг HQ-музыки    | HD-аудио без лагов в голосовых чатах           |
| 🌐 Мультиплатформенность | YouTube, Spotify, Apple Music, Resso и др.     |
| 👮 Управление группой    | Повышение/понижение, мут/кик и т.д.            |
| ⚡ Быстрая установка      | Развёртывание в один клик: Heroku, VPS, Docker |
| 🔄 Автоконфигурация      | Скрипт быстрой настройки с проверками          |

</td>
</tr>
</table>

## 🔑 Переменные окружения

Ниже приведены обязательные и необязательные переменные окружения для запуска.

```env
API_ID=              # Обязательно — получить на https://my.telegram.org
API_HASH=            # Обязательно — https://my.telegram.org
BOT_TOKEN=           # Обязательно — получить у t.me/BotFather
OWNER_ID=            # Обязательно — ваш Telegram ID
LOGGER_ID=           # Обязательно — ID группы/канала для логов
STRING_SESSION=      # Обязательно — сгенерировать через @SessionBuilderbot
MONGO_DB_URI=        # Обязательно — строка подключения MongoDB
COOKIE_URL=          # Обязательно — ссылка на cookies YouTube

DEEP_API=            # Необязательно — https://deepai.org
API_KEY=             # Необязательно — внешний API для скачивания музыки
VIDEO_API_URL=       # Необязательно — API для скачивания видео
API_URL=             # Необязательно — API для скачивания аудио
```

⚠️ **Никогда не публикуйте cookies или токены в публичных репозиториях.**
Используйте безопасные сервисы вставки, такие как [Pastebin](https://pastebin.com) или [Batbin](https://batbin.me).

##

<details>
  <summary><b>Где получить каждый ключ?</b></summary>

  <br/>

  <table>
    <thead>
      <tr>
        <th>Ключ</th>
        <th>Где получить</th>
        <th>Шаги</th>
        <th>Примечания</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>API_ID</code> и <code>API_HASH</code></td>
        <td><a href="https://my.telegram.org" target="_blank">my.telegram.org</a> → <i>API Development Tools</i></td>
        <td>
          1) Войти через Telegram →
          2) Открыть <b>API Development Tools</b> →
          3) Создать приложение →
          4) Скопировать значения
        </td>
        <td>Храните в секрете. Нужно для userbot и bot-клиента.</td>
      </tr>
      <tr>
        <td><code>BOT_TOKEN</code></td>
        <td><a href="https://t.me/BotFather" target="_blank">@BotFather</a></td>
        <td>
          1) <b>/newbot</b> →
          2) Задать имя и username →
          3) Скопировать токен
        </td>
        <td>При утечке пересоздайте. Храните в <code>.env</code>.</td>
      </tr>
      <tr>
        <td><code>STRING_SESSION</code></td>
        <td><a href="https://t.me/SessionBuilderbot" target="_blank">@SessionBuilderbot</a></td>
        <td>
          1) Запустить бота →
          2) Ввести <code>API_ID</code>/<code>API_HASH</code> →
          3) Завершить вход →
          4) Скопировать строку
        </td>
        <td>Авторизация userbot для Pyrogram.</td>
      </tr>
      <tr>
        <td><code>LOGGER_ID</code></td>
        <td>Ваш <b>канал или группа</b> в Telegram</td>
        <td>
          1) Создать приватный канал/группу →
          2) Добавить бота администратором →
          3) Получить ID через <code>@AnnieXRobot</code> или <code>@MissRose_Bot</code>
        </td>
        <td>Используйте приватное место для логов.</td>
      </tr>
      <tr>
        <td><code>MONGO_DB_URI</code></td>
        <td><a href="https://www.mongodb.com/atlas/database" target="_blank">MongoDB Atlas</a></td>
        <td>
          1) Создать бесплатный кластер →
          2) Добавить пользователя БД и IP →
          3) Скопировать строку подключения
        </td>
        <td>Нужно для сохранения данных (очереди, настройки).</td>
      </tr>
      <tr>
        <td><code>COOKIE_URL</code></td>
        <td>Любой безопасный хостинг (Pastebin, Batbin)</td>
        <td>
          1) Загрузить <code>cookies.txt</code> приватно →
          2) Установить доступ <b>Unlisted</b> →
          3) Скопировать <b>raw</b>-ссылку
        </td>
        <td>Повышает стабильность YouTube.</td>
      </tr>
      <tr>
        <td><code>DEEP_API</code> / <code>API_KEY</code> / <code>API_URL</code> / <code>VIDEO_API_URL</code></td>
        <td>Любой провайдер</td>
        <td>Регистрация → генерация ключа → вставить сюда</td>
        <td>Необязательные интеграции.</td>
      </tr>
    </tbody>
  </table>

  <br/>
</details>

##

### ☕ Руководство по установке на VPS

```bash
🎵 Развёртывание AnnieXMusic на VPS

# Шаг 1: Обновление и установка зависимостей
sudo apt update && sudo apt upgrade -y
sudo apt install -y git curl python3-pip python3-venv ffmpeg unzip tmux

# Шаг 2: Установка Deno (для yt-dlp)
curl -fsSL https://deno.land/install.sh | sh
source ~/.bashrc

# Шаг 3: Клонирование и настройка
git clone https://github.com/CertifiedCoders/AnnieXMusic
cd AnnieXMusic
tmux new -s Annie

python3 -m venv venv
source venv/bin/activate
pip install -U pip && pip install -r requirements.txt

bash setup
bash start
```

##

### 🐳 Развёртывание через Docker

```bash
git clone https://github.com/CertifiedCoders/AnnieXMusic
cd AnnieXMusic

nano .env
docker build -t anniexmusic .
docker run -d --name annie --env-file .env --restart unless-stopped anniexmusic
```

##

### ☁️ Быстрый деплой

| Платформа           | Ссылка             |
| ------------------- | ------------------ |
| 🔑 Генерация сессии | @SessionBuilderbot |
| 🌍 Heroku           | Deploy to Heroku   |

## 💬 Сообщество и поддержка

(ссылки сохранены без изменений)

##

### 🔖 Благодарности

* **Особая благодарность <a href="https://github.com/AnonymousX1025">AnonY</a> за <a href="https://github.com/AnonymousX1025/AnonXMusic">AnonXMusic</a>**
* **Создано с любовью командой <a href="https://github.com/CertifiedCoders">Certified Coders</a>**
