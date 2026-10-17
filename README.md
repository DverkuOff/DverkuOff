## Иван · DverkuOff

**AI Engineer · LLM-агенты · DevOps**<br>
Москва · гибрид или удалённо · МАДИ, «Информатика и вычислительная техника», 2 курс, заочно

[Telegram @Dverku_oFF](https://t.me/Dverku_oFF) · [work@dverkuoff.uk](mailto:work@dverkuoff.uk) · [dverkuoff.github.io](https://dverkuoff.github.io)

Строю LLM-агентов и инфраструктуру под них: от self-hosted моделей на своём GPU до production-агента с RAG. Пишу на Python и Go, сервисы запускаю в Docker, мониторинг веду в Prometheus и Grafana.

### Проекты

**AI-агент для пресейла серверного оборудования** · production · 2025–2026<br>
Ведёт клиента от запроса до готового КП, в том числе по закупкам 44-ФЗ и 223-ФЗ. Основу заложил предыдущий разработчик, я довёл систему до production: все сценарии в n8n, векторизация базы знаний и RAG, сервис подбора комплектующих, веб-конфигуратор, доработка админки менеджера. На тестах от заявки до КП ~15 минут вместо ~3 дней. Код закрыт.

**iPhone Searcher** · 2025–2026<br>
Telegram-бот по подписке: присылает новые объявления о продаже iPhone по фильтрам пользователя. Переписали вдвоём с нуля, я отвечал за пайплайн данных. Рассылка работает отдельным сервисом на Go через RabbitMQ. ~50 активных подписчиков из 30+ городов. Код закрыт.

**Self-hosted AI Lab: голосовой LLM-пайплайн** · pet<br>
whisper.cpp и llama.cpp на своём GPU в Docker на WSL2, доступ через WireGuard-туннель на VPS, метрики в Prometheus и Grafana. Часовая запись распознаётся за ~1,5 минуты.

**[Foresight](https://github.com/DverkuOff/foresight)** · 2 место, Хакатон Московского транспорта 2026<br>
Командное решение: по потоковой телеметрии за 10–15 минут до прибытия прогнозирует задержку на остановке. Моя часть: ML-модель на CatBoost и backend на FastAPI.

**[kube-gateway-stand](https://github.com/DverkuOff/kube-gateway-stand)** · решение DevOps-кейса хакатона<br>
Kubernetes (kubeadm) на Ubuntu 24.04 одной командой: Gateway API (Traefik) с TLS и canary, Prometheus, Fluentd → Loki, Grafana, e2e-проверки в CI.

### Хакатоны 2026

Три вторых места в команде: Хакатон Московского транспорта, финал КосмоХакатона в Москве (кейс «Безопасный маршрут», моя часть: фильтр Калмана для навигации без GPS), окружной этап КосмоХакатона в Нижнем Новгороде.

### Стек

**AI / LLM:** LLM-агенты, RAG, MCP, n8n, Langfuse, OpenAI API, llama.cpp, Whisper<br>
**Backend:** Python, FastAPI, aiogram, SQLAlchemy, pytest, Go, Gin, REST, gRPC<br>
**Данные:** PostgreSQL, pgvector, Redis, RabbitMQ, MongoDB<br>
**DevOps:** Docker, Docker Compose, Linux, Bash, Nginx, Traefik, GitHub Actions, Terraform, Ansible, WireGuard<br>
**Мониторинг:** Prometheus, Grafana, Alertmanager, node_exporter, Loki, Fluentd<br>
**Базово:** Kubernetes (однонодовый стенд на kubeadm), Helm, Docker Swarm, LangGraph, Qdrant
