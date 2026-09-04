<img src="https://avatars.githubusercontent.com/u/323290598?s=100&v=4" align="left" width="70" style="margin-right: 15px;">

# ❄️ Weatherender Foundation

**Open-source weather intelligence for alpine sports, travelers, and developers.**

We build production-grade tools that transform raw meteorological data into actionable insights. Our core project, **Weatherender**, is a complete weather intelligence platform — from a sleek web interface and CLI tool to a high‑performance async API, all backed by modern infrastructure and engineering practices.

---

## 🌟 Our Flagship Project: Weatherender

### ✨ What It Does
- **Real‑time weather** + 3‑day forecast for any city
- **Advanced Snow Surface Condition Index (SSCI)** — our proprietary algorithm that detects snow quality (from *"Dry champagne powder!"* to *"Spring slush"* and *"Wind slab"*)
- **Web UI** (Flask), **CLI tool**, and a **FastAPI v2** async API in one unified application
- **Automatic location detection** via IP (with fallback chain)
- **Redis‑cached responses** for lightning‑fast API replies
- **Production‑grade resiliency** — retries, rate limiting, graceful degradation, health checks, Prometheus metrics

### 🛠️ Tech Stack
- **Backend:** Python 3.13, FastAPI (ASGI), Flask (WSGI via WSGIMiddleware), Uvicorn, Gunicorn (gevent workers)
- **DB & Cache:** PostgreSQL + SQLAlchemy (sync/async), Alembic, Redis
- **Infra:** Docker, Docker Compose, GitHub Actions (CI/CD), APScheduler
- **Testing:** 119+ pytest tests, k6 (smoke, load, stress, spike)
- **Security:** Talisman, rate limiting (Flask‑Limiter + SlowAPI), User‑Agent validation
- **Observability:** Prometheus, structured JSON logging

---

## 🚀 Try It Now
**Live Demo:** [weather-7icc.onrender.com](https://weather-7icc.onrender.com)  
*(Hosted on Render free tier — first start may take 30–50 sec due to container cold start)*

**API Swagger Docs:** [weather-7icc.onrender.com/v2/docs](https://weather-7icc.onrender.com/v2/docs)

---

## 📂 Key Documentation
| Document | Description |
| :--- | :--- |
| [Weatherender/README](https://github.com/Weatherender-Foundation/Weatherender#readme) | Full project guide: setup, CLI, API reference |
| [ARCHITECTURE.md](https://github.com/Weatherender-Foundation/Weatherender/blob/main/docs/ARCHITECTURE.md) | Component diagram and data flow |
| [PERFORMANCE.md](https://github.com/Weatherender-Foundation/Weatherender/blob/main/docs/PERFORMANCE.md) | Load‑testing methodology and results |
| [DEPLOYMENT.md](https://github.com/Weatherender-Foundation/Weatherender/blob/main/docs/DEPLOYMENT.md) | Production deployment on Render + Supabase + Upstash |
| [CONTRIBUTING.md](https://github.com/Weatherender-Foundation/Weatherender/blob/main/CONTRIBUTING.md) | How to contribute |

---

## 🤝 Join the Foundation
We welcome contributors of all skill levels — whether you want to fix a bug, improve the SSCI algorithm, add a new feature, or help with documentation.

1.  Check our [CONTRIBUTING.md](https://github.com/Weatherender-Foundation/Weatherender/blob/main/CONTRIBUTING.md)
2.  Look for issues labeled `good first issue` or `help wanted`
3.  Open a discussion or issue — we're friendly!

---

## 📬 Contact
- **Founder & Lead Developer:** Alexey Lyapin
- **GitHub:** [LyapinAlexey](https://github.com/LyapinAlexey)
- **Telegram:** [@LyapinAlexey](https://t.me/LyapinAlexey)

---

## 📄 License
This project is licensed under the **SSCI Custom License v1.1** — non‑commercial use with attribution. Commercial use strictly prohibited without explicit permission.

---

## 💖 Support
If you find Weatherender useful:
- ⭐ **Star** the repository on GitHub
- 🐛 **Report bugs** via Issues
- 💬 **Share** it with fellow skiers and developers
- 🧑‍💻 **Contribute** code or documentation

---

*Built with ❄️ and ☕ by Alexey Lyapin, a alpine skier and full time student.*  
*Inspired by the slopes and the love for clean code.*
