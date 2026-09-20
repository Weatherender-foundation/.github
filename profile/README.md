<img src="https://avatars.githubusercontent.com/u/323290598?s=100&v=4" align="left" width="70" style="margin-right: 15px;">

# Weatherender Foundation

**Open-source weather intelligence for alpine sports, travelers, and developers.**

We build production-grade tools that turn raw meteorological data into actionable insights. Our flagship project, **Weatherender**, combines a Flask web interface, a CLI tool, and a high-performance async FastAPI API into a single weather intelligence platform for real-world use.

---

## 🌟 Our flagship project: Weatherender

### ✨ What it does
- **Real-time weather** + 3-day forecast for any city
- **Advanced Snow Surface Condition Index (SSCI)** — a proprietary snow-quality model that classifies conditions from *"Dry champagne powder!"* to *"Spring slush"* and *"Wind slab"*
- **Web UI**, **CLI tool**, and **FastAPI v2 API** in one unified codebase
- **Automatic location detection** via IP with a fallback geolocation chain
- **Redis-backed caching** for fast API responses and lower upstream API load
- **Production-grade resiliency** — retries, rate limiting, graceful degradation, health checks, Prometheus metrics, and structured logging

### 🛠️ Tech stack
- **Backend:** Python 3.13, Flask, FastAPI, Uvicorn, Gunicorn, SQLAlchemy, Alembic
- **Database & cache:** PostgreSQL, Redis
- **Infrastructure:** Docker, Docker Compose, GitHub Actions, APScheduler
- **Testing:** 119+ pytest tests, k6 smoke/load/stress/spike scripts, Codecov
- **Security:** Talisman, Flask-Limiter, SlowAPI, request validation, User-Agent checks
- **Observability:** Prometheus metrics, structured JSON logging

---

## 🚀 Try it now
**Live demo:** [weather-7icc.onrender.com](https://weather-7icc.onrender.com)  
*(Hosted on Render free tier; cold starts may take 30–50 seconds on first request after inactivity)*

**API docs:** [weather-7icc.onrender.com/v2/docs](https://weather-7icc.onrender.com/v2/docs)

> The project runs in production with Render, Supabase PostgreSQL, and Upstash Redis.

---

## 📚 Key documentation

| Document | Description |
| :--- | :--- |
| [README.md](README.md) | Main project guide: setup, install, CLI, API, and local deployment |
| [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md) | System architecture, components, request flow, and deployment layout |
| [docs/DEPLOYMENT.md](docs/DEPLOYMENT.md) | Production deployment on Render + Supabase + Upstash |
| [docs/PERFORMANCE.md](docs/PERFORMANCE.md) | Load testing, bottlenecks, and resilience benchmarks |
| [docs/API.md](docs/API.md) | Full API reference, parameters, responses, and rate limiting |
| [docs/FAQ.md](docs/FAQ.md) | Common questions and operational notes |
| [docs/ROADMAP.md](docs/ROADMAP.md) | Planned and completed project milestones |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Contribution workflow and developer guidelines |
| [SECURITY.md](SECURITY.md) | Security reporting and disclosure process |
| [MAINTAINERS.md](MAINTAINERS.md) | Maintainer information |
| [GOVERNANCE.md](GOVERNANCE.md) | Community governance and decision-making process |

---

## 🤝 Join the foundation
We welcome contributors of all skill levels — whether you want to fix a bug, improve the SSCI algorithm, add a new feature, or help with documentation.

1. Read [CONTRIBUTING.md](CONTRIBUTING.md)
2. Look for issues labeled `good first issue` or `help wanted`
3. Open a discussion or issue and start contributing

---

## 📬 Contact
- **Founder & lead developer:** Alexey Lyapin
- **GitHub:** [LyapinAlexey](https://github.com/LyapinAlexey)
- **Telegram:** [@LyapinAlexey](https://t.me/LyapinAlexey)

---

## 📄 License
This project is licensed under the **Apache License 2.0**.

See [LICENSE](LICENSE) for the full terms. Project names and branding are covered separately in [TRADEMARKS.md](TRADEMARKS.md).

---

## 💖 Support
If you find Weatherender useful:
- ⭐ **Star** the repository on GitHub
- 🐛 **Report bugs** via Issues
- 💬 **Share** it with fellow skiers and developers
- 🧑‍💻 **Contribute** code or documentation

---

*Built with ❄️ and ☕ by Alexey Lyapin, an alpine skier and software engineer.*  
*Inspired by the slopes, the weather, and the love for clean engineering.*
