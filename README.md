<div align="center">

# Chabupelik

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=1000&color=58A6FF&center=true&vCenter=true&width=550&lines=Python+Backend+Developer;FastAPI+%E2%80%A2+PostgreSQL+%E2%80%A2+Redis+%E2%80%A2+Docker;High-Load+Backends+%26+Async+Architecture" alt="Typing SVG" />
</a>

<p align="center">
  Бэкенд-разработчик на Python. Проектирую REST API, серверную логику,<br/>
  оптимизирую работу с базами данных и контейнеризирую сервисы в Docker.
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,redis,rabbitmq,docker,linux,nginx,git&theme=dark" alt="Tech Stack" />
  </a>
</p>

---

</div>

### 🛠️ Стек технологий

* **Бэкенд:** `Python 3` • `FastAPI` • `Pydantic` • `REST API` • `Celery` • `BackgroundTasks` • `WebSockets`
* **Базы данных и кэш:** `PostgreSQL` • `SQLAlchemy 2.0 (asyncpg)` • `Alembic` • `Redis`
* **Инфраструктура:** `Docker` • `Docker Compose` • `Linux` • `Nginx` • `Git` • `CI/CD` • `JWT (RBAC)`

---

### 🚀 Проекты

### 🖥️ [Deskrift](https://github.com/Chabupelik/Deskrift)
**Self-hosted веб-удаленный доступ к экрану Windows без установки клиентского софта (<50 мс при 60 FPS).**

<p>
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/WebSockets-161b22?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-161b22?style=flat-square&logo=go&logoColor=00ADD8" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Vue_3-161b22?style=flat-square&logo=vuedotjs&logoColor=4FC08D" />
</p>

* **Видеопоток:** Аппаратный захват экрана из видеопамяти (DXGI/NVENC) и передача чанков H.264 по WebSocket с аппаратным декодированием в браузере через WebCodecs API.
* **Бэкенд:** Координация сессий на FastAPI, маршрутизация потоков и низколатентная трансляция пользовательского ввода (мышь, клавиатура).
* **Авторизация:** Беспарольный вход через Telegram-бота по одноразовым токенам с коротким TTL в Redis.

---

### 📚 [StudyManager](https://github.com/Chabupelik/StudyManager)
**Платформа управления учебным процессом с Live-синхронизацией расписания, посещаемостью и ролевой моделью.**

<p>
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/WebSockets-161b22?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Nginx-161b22?style=flat-square&logo=nginx&logoColor=009639" />
  <img src="https://img.shields.io/badge/Vue_3-161b22?style=flat-square&logo=vuedotjs&logoColor=4FC08D" />
</p>

* **Архитектура:** Чистая многослойная архитектура (Clean Architecture): изоляция API-контроллеров, доменных сервисов и репозиториев (SQLAlchemy asyncpg).
* **Синхронизация:** Конструктор расписания с мгновенной рассылкой изменений (отмены, замены, переносы) клиентам по WebSocket без перезагрузки страниц.
* **Ролевая модель:** Иерархический RBAC (`superadmin` → `curator` → `headman` → `student`) с поддержкой одновременного членства в нескольких группах.
* **Интеграции:** Telegram Mini App, автоматический подсчёт академических часов и двусторонний мост сообщений VK ↔ Telegram.

---

### 🌾 [AgroMachines](https://github.com/Chabupelik/AgroMachines)
**Каталог спецтехники и CRM-система со сквозной обработкой заявок клиентами и менеджерами в Telegram.**

<p>
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/MinIO_S3-161b22?style=flat-square&logo=minio&logoColor=C72C48" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Nginx-161b22?style=flat-square&logo=nginx&logoColor=009639" />
  <img src="https://img.shields.io/badge/Vue_3-161b22?style=flat-square&logo=vuedotjs&logoColor=4FC08D" />
</p>

* **Telegram-CRM:** Заявки с витрины моментально приходят в чат менеджеров; управление статусами («В работе», «Завершено») идёт кнопками через вебхуки на бэкенд.
* **Целостность данных:** Частичный уникальный индекс в PostgreSQL исключает дублирование активных заявок по номеру телефона при повторных кликах.
* **Асинхронность:** Отправка уведомлений вынесена в BackgroundTasks, обеспечивая мгновенный ответ API клиенту без блокировок.
* **Безопасность:** Token Bucket Rate-limiting в Redis от спама, валидация номеров (Google Libphonenumber) и медиахранилище MinIO S3.

---

### 🛡️ [Wispr](https://github.com/Chabupelik/Wispr)
**Изолированный браузер и шлюз для безопасного веб-сёрфинга без сохранения следов на диске.**

<p>
  <img src="https://img.shields.io/badge/Fastify-161b22?style=flat-square&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/WebSockets-161b22?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-161b22?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Tauri-161b22?style=flat-square&logo=tauri&logoColor=24C8DB" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
</p>

* **Туннелирование:** Трафик маскируется под защищённый WebSocket-канал (протокол WISP) для обхода DPI и сетевых фильтров.
* **Серверный шлюз:** Прокси распаковывает сетевые TCP/UDP пакеты и отправляет запросы во внешнюю сеть от имени VPS.
* **Изоляция:** Сессии работают строго в оперативной памяти без сохранения кук и кэша на диск; блокируются WebRTC и DNS-утечки.
