<div align="center">

# Chabupelik

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=1000&color=58A6FF&center=true&vCenter=true&width=550&lines=Python+Backend+Developer;REST+API+%E2%80%A2+Server+Architecture;PostgreSQL+%E2%80%A2+Redis+%E2%80%A2+Docker+%E2%80%A2+FastAPI;High-Reliability+%26+Async+Services" alt="Typing SVG" />
</a>

<p align="center">
  Бэкенд-разработчик на Python. Проектирую производительные REST API, серверную логику,<br/>
  оптимизирую работу с базами данных и упаковываю сервисы в Docker.
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

### 📚 [StudyManager](https://github.com/Chabupelik/StudyManager)
> Комплексная клиент-серверная платформа управления учебным процессом, расписанием, посещаемостью и дежурствами.

<p>
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/WebSockets-161b22?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Nginx-161b22?style=flat-square&logo=nginx&logoColor=009639" />
  <img src="https://img.shields.io/badge/Vue_3-161b22?style=flat-square&logo=vuedotjs&logoColor=4FC08D" />
</p>

* 🏛️ **Clean Architecture:** Полная изоляция слоёв: API-контроллеры, доменные сервисы бизнес-логики и репозитории SQLAlchemy (asyncpg).
* 🔄 **WebSockets Live Sync:** Конструктор расписания с семестровыми интервалами, оверрайдами «на лету» и мгновенным пушем изменений клиентам без перезагрузки страниц.
* 👥 **Мультигрупповой RBAC:** Иерархия ролей (`superadmin` → `curator` → `headman` → `student`) с возможностью членства одного пользователя в нескольких группах.
* 🌉 **Интеграции:** Двусторонний шлюз сообщений (VK ↔ Telegram Bridge), Telegram Mini App и экспорт ведомостей в Excel.

---

### 🌾 [AgroMachines](https://github.com/Chabupelik/AgroMachines)
> Production-ready платформа каталога сельхозтехники с системой оформления заявок и интеграцией в Telegram-CRM.

<p>
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/MinIO_S3-161b22?style=flat-square&logo=minio&logoColor=C72C48" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Nginx-161b22?style=flat-square&logo=nginx&logoColor=009639" />
  <img src="https://img.shields.io/badge/Vue_3-161b22?style=flat-square&logo=vuedotjs&logoColor=4FC08D" />
</p>

* 🛡️ **Защита от Race Condition:** Частичный уникальный индекс PostgreSQL (`WHERE status IN ('NEW', 'IN_PROGRESS')`) и атомарные обновления — исключают дублирование заявок на уровне СУБД.
* ⚡ **Асинхронная доставка:** Интеграционные задачи отправки уведомлений вынесены в `BackgroundTasks`, обеспечивая моментальный `200 OK` клиенту.
* 🤖 **Telegram Webhook CRM:** Моментальное создание карточки заявки в чате менеджеров с Inline-кнопками управления («Взять в работу» / «Завершить») и обновлением статуса по вебхуку.
* 🔒 **Комплексная безопасность:** Token Bucket Rate-limiting в Redis, валидация номеров телефонов через Google Libphonenumber и MinIO S3 для медиа.

---

### 🖥️ [Deskrift](https://github.com/Chabupelik/Deskrift)
> Высокопроизводительный self-hosted удаленный доступ к экрану Windows через браузер (<50 мс, 60 FPS).

<p>
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/WebSockets-161b22?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-161b22?style=flat-square&logo=go&logoColor=00ADD8" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Vue_3-161b22?style=flat-square&logo=vuedotjs&logoColor=4FC08D" />
</p>

* 📡 **WebSocket Video Streaming:** Потоковая трансляция H.264 чанков без протокольного оверхеда с аппаратным декодированием через WebCodecs API в браузере.
* 🎛️ **Бэкенд-маршрутизация:** FastAPI управляет жизненным циклом сессий, пирами и проксированием потоков между десктопным Go-агентом и клиентом.
* ⌨️ **Низколатентное управление:** Двусторонняя передача событий ввода (мышь, клавиатура) напрямую в Win32 API.
* 🔑 **Беспарольный вход:** Мгновенная авторизация через личного Telegram-бота с генерацией одноразовых токенов с коротким TTL в Redis.

---

### 🛡️ [Wispr](https://github.com/Chabupelik/Wispr)
> Клиент-серверная платформа изолированного веб-сёрфинга и защищённого туннелирования трафика.

<p>
  <img src="https://img.shields.io/badge/Fastify-161b22?style=flat-square&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/Redis-161b22?style=flat-square&logo=redis&logoColor=DC382D" />
  <img src="https://img.shields.io/badge/WebSockets-161b22?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-161b22?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Tauri-161b22?style=flat-square&logo=tauri&logoColor=24C8DB" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" />
</p>

* 🌐 **WISP WebSocket Gateway:** Серверный шлюз распаковывает сетевые TCP/UDP пакеты, инкапсулированные в зашифрованный WebSocket-канал, маскируя трафик под стандартный HTTPS.
* 🔐 **Идентификация и сессии:** Валидация клиентов по аппаратному идентификатору (HWID), управление сессиями через Redis и хранение логов в PostgreSQL.
* 🛡️ **Предотвращение утечек:** Блокировка WebRTC/DNS-утечек с резолвингом на стороне сервера и аварийный сброс соединений (Killswitch).
