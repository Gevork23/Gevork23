🇬🇧 [English](README.md) | 🇷🇺 Русский

# 🧑‍💻 @Gevork23 (Геворк Мирзоян)

---

## 👋 Обо мне

Я Backend-разработчик с опытом работы в продакшене.

Сочетаю области Backend-разработки с областью системного администрирования и работы с Linux-инфраструктурой. Это позволяет мне создавать надежные, масштабируемые приложения и эффективно взаимодействовать с DevOps-процессами.

### 🛠 Tech Stack, что я приношу команде

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
### Чистый, поддерживаемый код, следующий принципам SOLID, DRY, KISS и PEP 8
- ![PEP 8](https://img.shields.io/badge/PEP_8-3776AB?style=for-the-badge&logo=python&logoColor=white)
### Опыт работы с 
- ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
- ![Django REST Framework](https://img.shields.io/badge/DRF-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
- ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
### Проектирование баз данных и оптимизация запросов
- ![PostgreSQL](https://img.shields.io/badge/postgresql-4169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white)
- ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
### Контейнеризация приложений с помощью
- ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
- ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
- ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
- ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
- ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
- ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
### Покрытие кода тестами с использованием
- ![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=0a9edc)
- ![Flake8](https://img.shields.io/badge/flake8-008000?style=for-the-badge&logo=python&logoColor=white)
- ![Black](https://img.shields.io/badge/black-000000?style=for-the-badge&logo=python&logoColor=white)
### Навыки эффективной коммуникации и опыт работы в команде
### Умение решать бизнес-задачи с помощью кода и автоматизировать рутинные процессы
- ![pip](https://img.shields.io/badge/pip-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![uv](https://img.shields.io/badge/uv-0A2B3E?style=for-the-badge&logo=python&logoColor=white)

---

## 🚀 Ключевые проекты

### 🗣 Голосовой бот для МФЦ — Продакшен-решение

**Стек:** Python, aiogram, REST API, Webhooks, TTS (синтез речи)

- Разработал и развернул **голосовой бот-уведомитель** для центра госуслуг (МФЦ) для трансляции объявлений в зале ожидания
- Интегрировал с мессенджерами **Telegram** и **VK** через **webhooks** с использованием **aiogram**
- Реализовал **REST API (GET/POST)** между интерфейсом администратора и системой воспроизведения
- Настроил синтез речи (TTS) для преобразования текстовых сообщений в голосовые объявления
- Решил реальную бизнес-задачу с минимальным бюджетом, сократив ручную нагрузку на администраторов

**Результат:** Автоматизированная система массовых уведомлений, ежедневно используемая 20+ сотрудниками.

---

### 🍽 DineTogether — Командный проект: REST API для бронирования столов

**Стек:** FastAPI, PostgreSQL, Docker, Celery, Redis, Pytest, JWT

**Командный проект** (4 разработчика) в рамках выпускной работы Яндекс Практикума.

- Разработал REST API для бронирования столов в ресторанах с ролевым доступом (USER, MANAGER, ADMIN)
- Реализовал управление медиафайлами для кафе и блюд
- Провел рефакторинг модуля аутентификации: убрал генерацию refresh_token для повышения безопасности
- Исправил ошибки валидации и унифицировал формат ответов об ошибках для улучшения взаимодействия с фронтендом
- Написал комплексное покрытие тестами с использованием **pytest**, снизив количество регрессионных ошибок
- Использовал **Docker Compose** для локальной разработки и развертывания

**Результат:** Полнофункциональный API-сервис с чистой архитектурой и высоким покрытием тестами.

---

### 🍳 Foodgram — Платформа для обмена рецептами (бэкенд)

**Стек:** Django, Django REST Framework, PostgreSQL, Docker, Nginx, Gunicorn, JWT

**URL:** [https://oski.myftp.biz](https://oski.myftp.biz)

- Построил бэкенд для платформы обмена рецептами с подписками и корзиной покупок
- Спроектировал схему базы данных для пользователей, рецептов, ингредиентов, тегов, избранного и корзины
- Реализовал JWT-аутентификацию, фильтрацию, поиск и оптимизацию запросов
- Настроил продакшен-развертывание с помощью **Docker Compose**, **Gunicorn** и **Nginx**

---

### 🔧 Дополнительные проекты

- **YaNote** — REST API для заметок (DRF, JWT, Swagger)
- **Blogicum** — Многостраничный блог на Django с панелью администратора
- **Practicum Bot** — Telegram-бот с интеграцией внешнего API
- **Крестики-нолики** — Игра с GUI на Pygame, реализованная в ООП-стиле

---

## 💼 Опыт работы

### Системный администратор и внутренний разработчик
**МФЦ Мясниковского района (МАУ)** | 2024 — настоящее время

- Поддерживал IT-инфраструктуру: 20+ рабочих станций, серверы, сеть
- Автоматизировал рутинные задачи с помощью скриптов на **Python** и **Bash**
- Разработал и развернул описанный выше **голосовой бот**
- Обучал сотрудников и решал технические проблемы

---

## 🎓 Образование

🎓 **Донской государственный технический университет**
* Информационные системы и технологии (магистратура) | 2024 – 2026

🎓 **Донской государственный технический университет**
* Прикладная информатика (бакалавриат) | 2020 – 2024

🎓 **Яндекс Практикум**
* Python-разработчик (продвинутый курс) | 2025 – 2026

---

## 📫 Контакты

- 📧 [i@mirzoyan-gevork.ru](mailto:i@mirzoyan-gevork.ru)
- 💼 [GitHub](https://github.com/Gevork23)
- 💬 [Telegram](https://t.me/oski_txa)
- 🎨 [ArtStation](https://artstation.com/gevork23) — 3D-арт и игровые проекты (хобби)

---

## 📊 Статистика GitHub

[![Статистика Gevork](https://github-readme-stats.vercel.app/api?username=Gevork23&show_icons=true&theme=dark)](https://github.com/Gevork23)
[![Топ языков](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Gevork23&layout=compact&theme=vision-friendly-dark)](https://github.com/Gevork23)

---

⭐ **Открыт к удаленным вакансиям.**
