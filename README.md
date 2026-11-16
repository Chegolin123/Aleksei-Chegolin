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
| [mk-ai](https://github.com/Chegolin123/mk-ai) | Reinforcement learning, self-play файтинг, GPU-обучение, скриншоты и GIF из реальных прогонов |
| [sberbox-staros-toolkit](https://github.com/Chegolin123/sberbox-staros-toolkit) | Инструменты для SberBox на StarOS |
| [Ai_Alex](https://github.com/Chegolin123/Ai_Alex) | Локальный AI-ассистент |

Витрины `mlops-runner`, `nexgate`, `transcriber` и `server-hub` — в работе: публичные версии с `docker-compose`, healthchecks и бенчмарками.

## Сейчас изучаю

DevOps-фундамент: namespaces и cgroups, сеть (маршрутизация, nftables, туннели), тома и файловые системы, отладка контейнеров без «перезапусти и молись».

## Контакты

Лучший способ связаться — issue или PR в любом из репозиториев.
