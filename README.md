# Алексей Чеголин — Python / DevOps / MLOps

Автоматизирую всё: от GPU-обучения до туннелей и watchdog'ов.
Студент 3-го курса КИП ФИН, строю инфраструктуру, на которой сам же и работаю.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

## Чем занимаюсь

- **Self-hosted GPU CI** — GitHub Actions runner на RTX 2070 SUPER: ночные тренировки, метрики и артефакты вместо «у меня локально работает».
- **Свой AI-шлюз** (`nexgate`) — FastAPI + SQLite + nginx, публичный HTTPS, лимиты, биллинг, healthchecks, алерты в Telegram.
- **Домашний сервер как прод** (`server-hub`) — туннели, watchdog'и, IaC-конфиги, бэкапы с проверкой целостности.
- **RL на GPU** (`mk-ai`) — self-play файтинг: 361 эпизод, счёт 184:173, обучение на одной 2070 SUPER.
- **ML-пайплайн на GPU** (`transcriber`) — faster-whisper с бенчмарками и Docker-сборкой.
- **Контент-завод** — FastAPI + Celery + PostgreSQL + Redis: очередь задач, воркеры, публикация в Telegram и Дзен.

## Избранные проекты

| Проект | Что внутри |
|---|---|
| [mk-ai](https://github.com/Chegolin123/mk-ai) | Reinforcement learning, self-play файтинг, GPU-обучение, Docker + CI со смоук-тренировкой |
| [mlops-runner](https://github.com/Chegolin123/mlops-runner) | Self-hosted GitHub Actions runner на RTX 2070 SUPER: systemd/Docker, ночные тренировки, метрики артефактом |
| [whisper-gpu](https://github.com/Chegolin123/whisper-gpu) | faster-whisper на CUDA: CLI, Docker-образ, замер RTF на своём железе |
| [sberbox-staros-toolkit](https://github.com/Chegolin123/sberbox-staros-toolkit) | Инструменты для SberBox на StarOS |
| [Ai_Alex](https://github.com/Chegolin123/Ai_Alex) | Локальный AI-ассистент |

`nexgate`, `transcriber` и `server-hub` остаются приватными: внутри есть инфраструктура и коммерческая часть.

## Обзоры приватных проектов

Код закрыт, но по каждому проекту есть технический разбор: задача, архитектура, решения и что не сработало.

| Обзор | О чём |
|---|---|
| [NexGate](https://github.com/Chegolin123/nexgate-overview) | Шлюз к LLM: OpenAI- и Anthropic-совместимый API, биллинг по фактическим токенам |
| [Server Hub](https://github.com/Chegolin123/server-hub-overview) | MCP над SSH: 21 инструмент для серверов, Docker, файлов и видео |
| [Transcriber](https://github.com/Chegolin123/transcriber-overview) | Пайплайн расшифровки на faster-whisper: txt/srt/json |
| [AI-агенты для рекламы](https://github.com/Chegolin123/advertising-ai-overview) | MCP-инструменты для Яндекс.Директ и VK Ads |
| [Ludi](https://github.com/Chegolin123/ludi-overview) | Фреймворк Telegram-ботов-персон с конфигом в JSON |
| [Arin](https://github.com/Chegolin123/podcast-overview) | Статья → подкаст с диалогом ведущих и пост для соцсетей |
| [Алекс](https://github.com/Chegolin123/alex-assistant-overview) | Локальный голосовой ассистент без облака |
| [MCP-лаборатория](https://github.com/Chegolin123/mcp-lab-overview) | Четыре MCP-сервера: база знаний, дневник, Telegram, текст на картинке |

## Сейчас изучаю

DevOps-фундамент: namespaces и cgroups, сеть (маршрутизация, nftables, туннели), тома и файловые системы, отладка контейнеров без «перезапусти и молись».

## Контакты

Лучший способ связаться — issue или PR в любом из репозиториев.
