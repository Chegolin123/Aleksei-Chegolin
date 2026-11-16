# Алексей Чеголин — веб-разработка · инфраструктура · ML

Веб-разработчик по образованию: фронт на React/Next.js, бэк на Laravel, Node.js и Python.
Дальше вырос в инфраструктуру — Docker, Linux, CI/CD — и в ML на своей видеокарте.
Студент 3-го курса КИП ФИН. Делаю продукт целиком: от вёрстки до сервера, на котором он живёт.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

## Веб

Сайты и веб-приложения под ключ — от макета до продакшена с доменом, TLS и аналитикой.

- **Личный сайт** (`vizitka`) — Next.js + Tailwind, статический экспорт: быстрые страницы, SEO, OG-картинки.
- **Сайт ремонтной компании** (`remont-akt`) — Laravel + Blade + Vite: каталог услуг, формы заявок, адаптив под мобильные.
- **Туроператор** (`tourtohell`) — React + Node.js + MySQL: бронирование, отзывы с модерацией, избранное, админ-панель с графиками, Яндекс.Карты.
- **Лендинг с 3D** (`leady-landing`) — Next.js + TypeScript, React Three Fiber и Framer Motion: WebGL-сцена и микроанимации без просадки по скорости.

## Инфраструктура

То, во что веб вырос: приложение надо не только написать, но и задеплоить, обновить и не потерять данные.

- **Self-hosted GPU CI** (`mlops-runner`) — GitHub Actions runner на RTX 2070 SUPER: ночные тренировки, метрики и артефакты вместо «у меня локально работает».
- **Свой AI-шлюз** (`nexgate`) — FastAPI + PostgreSQL + nginx: OpenAI- и Anthropic-совместимый API, кабинет, лимиты, биллинг, healthchecks.
- **Домашний сервер как прод** (`server-hub`) — туннели, watchdog'и, IaC-конфиги, бэкапы с проверкой целостности.
- **Контент-завод** — FastAPI + Celery + PostgreSQL + Redis: очередь задач, воркеры, публикация в Telegram и Дзен.

## ML на своей GPU

- **RL на GPU** (`mk-ai`) — self-play файтинг: 361 эпизод, счёт 184:173, обучение на одной 2070 SUPER.
- **Речь в текст** (`whisper-gpu`, `transcriber`) — faster-whisper на CUDA: txt/srt/json, Docker, замер RTF.

## Избранные проекты

| Проект | Что внутри |
|---|---|
| [vizitka](https://github.com/Chegolin123/vizitka) | Личный сайт: Next.js, TypeScript, Tailwind, статический экспорт |
| [tourtohell](https://github.com/Chegolin123/tourtohell) | Бронирование туров: React + Node.js + MySQL, админка с графиками, Яндекс.Карты |
| [remont-akt](https://github.com/Chegolin123/remont-akt) | Сайт ремонтной компании: Laravel, Blade, Vite, заявки |
| [leady-landing](https://github.com/Chegolin123/leady-landing) | Лендинг с WebGL-сценой: Next.js, React Three Fiber, Framer Motion |
| [mk-ai](https://github.com/Chegolin123/mk-ai) | Reinforcement learning, self-play файтинг, GPU-обучение, Docker + CI |
| [mlops-runner](https://github.com/Chegolin123/mlops-runner) | Self-hosted GPU runner: systemd/Docker, ночные тренировки, метрики артефактом |
| [whisper-gpu](https://github.com/Chegolin123/whisper-gpu) | faster-whisper на CUDA: CLI, Docker-образ, замер RTF |

`nexgate`, `transcriber` и `server-hub` остаются приватными: внутри есть инфраструктура и коммерческая часть.

## Обзоры приватных проектов

Код закрыт, но по каждому проекту есть технический разбор: задача, архитектура, решения и что не сработало. У части проектов веб — это не обёртка, а половина работы: кабинет, админка, публичные страницы.

| Обзор | О чём |
|---|---|
| [NexGate](https://github.com/Chegolin123/nexgate-overview) | Шлюз к LLM: API, кабинет и админка, биллинг по фактическим токенам |
| [Server Hub](https://github.com/Chegolin123/server-hub-overview) | MCP над SSH: 21 инструмент для серверов, Docker, файлов и видео |
| [Transcriber](https://github.com/Chegolin123/transcriber-overview) | Пайплайн расшифровки на faster-whisper: txt/srt/json |
| [AI-агенты для рекламы](https://github.com/Chegolin123/advertising-ai-overview) | MCP-инструменты для Яндекс.Директ и VK Ads + SaaS-отчётность |
| [Ludi](https://github.com/Chegolin123/ludi-overview) | Фреймворк Telegram-ботов-персон с конфигом в JSON |
| [Arin](https://github.com/Chegolin123/podcast-overview) | Статья → подкаст с диалогом ведущих и пост для соцсетей |
| [Алекс](https://github.com/Chegolin123/alex-assistant-overview) | Локальный голосовой ассистент без облака |
| [MCP-лаборатория](https://github.com/Chegolin123/mcp-lab-overview) | Четыре MCP-сервера: база знаний, дневник, Telegram, текст на картинке |

## Стек по слоям

| Слой | Чем работаю |
|---|---|
| Фронт | HTML, CSS, JavaScript, TypeScript, React, Next.js, Tailwind, React Three Fiber, Framer Motion |
| Бэк | PHP/Laravel, Node.js, Python/FastAPI, REST, MCP |
| Данные | PostgreSQL, MySQL, SQLite, Redis |
| Инфраструктура | Docker, Linux, nginx, systemd, GitHub Actions, бэкапы и мониторинг |
| ML | PyTorch, faster-whisper, CUDA, обучение и инференс на своей GPU |

## Сейчас изучаю

DevOps-фундамент: namespaces и cgroups, сеть (маршрутизация, nftables, туннели), тома и файловые системы, отладка контейнеров без «перезапусти и молись». Плюс TypeScript в строгом режиме — чтобы фронт не отставал от бэка.

## Контакты

Лучший способ связаться — issue или PR в любом из репозиториев.
