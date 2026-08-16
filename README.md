# SERVGRI.AI

**Гришин Сергей** · ML Engineer / Python Developer · Казань

Открыт к middle-позициям. Делаю прикладные ML/LLM-системы полного цикла: данные → эксперименты → оценка → inference API → БД → Docker. Отдельное направление — ML для химии (QSAR, токсикология, molecular representations).

Tech Lead на 4 хакатонах, включая корпоративный хакатон Т1. Руководил волонтёрской организацией 300+ человек.

Победитель конкурса «50 лучших инновационных идей для Республики Татарстан» и конкурса НИР аспирантов «Техностарт».

[Портфолио](https://servgri.github.io) · [Резюме](https://servgri.github.io/resume.html) · [GitHub](https://github.com/servgri) · [GitVerse](https://gitverse.ru/servgri) · [Telegram](https://t.me/servgri) · [svg95@list.ru](mailto:svg95@list.ru)

---

## Стек

| Слой | Инструменты |
| --- | --- |
| Machine Learning | scikit-learn, CatBoost, XGBoost, LightGBM, Optuna |
| Deep Learning | PyTorch, Lightning, Transformers, fastai, GNN |
| LLM / RAG | Qwen, embeddings, RAG, vector search, agents |
| Backend | Python, FastAPI, Django, Flask, REST, Pydantic |
| Data & Infra | PostgreSQL, pgvector, Chroma, Docker, MLflow, Git |
| Chemoinformatics | RDKit, Tox21, ChEMBL, QSAR, ChemBERTa |

---

## Проекты

| Проект                                                                                                                      | Описание | Стек |
|-----------------------------------------------------------------------------------------------------------------------------| --- | --- |
| [ToxMol AI](https://github.com/servgri/toxmol) · [GV](https://gitverse.ru/servgri/toxmol_ai)                                | QSAR и molecular ML: токсичность по Tox21, pIC50 по ChEMBL, поиск аналогов, RAG по химическим базам | Python, PyTorch, RDKit, ChemBERTa, Transformers, XGBoost, MLflow, FastAPI, PostgreSQL, Docker |
| [Adaptive Interview](https://github.com/servgri/adaptive_interview) · [GV](https://gitverse.ru/servgri/adaptive_interview)  | Адаптивная оценка компетенций: BKT подбирает задачи, LLM генерирует новые, код в Docker-песочнице | Python, Django, PyTorch, BKT, DKT, GNN, Qwen, RAG, PostgreSQL, Docker |
| [FraudShield](https://github.com/servgri/FraudShield) · [GV](https://gitverse.ru/servgri/FraudShield)                       | Детекция фрода по транзакциям: дисбаланс классов, cost-sensitive threshold, SHAP, FastAPI | Python, scikit-learn, CatBoost, XGBoost, LightGBM, PyTorch, SHAP, MLflow, FastAPI, Docker |
| [BookHybrid RecSys](https://github.com/servgri/book_rec_sys) · [GV](https://gitverse.ru/servgri/book_rec_sys)               | Гибридные рекомендации книг: Two-Tower / ALS как кандидаты, LightGBM/CatBoost как ranker | Python, PyTorch, Two-Tower, RecTools, XGBoost, CatBoost, Embeddings, MLflow, Django |
| [MedVision](https://github.com/servgri/medcv) · [GV](https://gitverse.ru/servgri/medcv)                                     | Классификация MRI головного мозга (EfficientNet-B2, Grad-CAM, REST). Не медицинское изделие | PyTorch, fastai, torchvision, OpenCV, ResNet, EfficientNet, Grad-CAM, Django REST, Docker |
| [FinForecast Bot](https://github.com/servgri/forecast_bot) · [GV](https://gitverse.ru/servgri/forecast_bot)                 | Прогноз next-day return: chronological split, сравнение ARIMA / GBM / LSTM, Telegram/VK | Python, pandas, ARIMA, XGBoost, LightGBM, CatBoost, LSTM, MLflow, aiogram |
| [AI Recruiter](https://github.com/servgri/ai_recruter) · [GV](https://gitverse.ru/servgri/ai_recruter)                      | Анализ резюме и matching кандидатов с вакансиями | Python, SBERT, embeddings, Flask |
| [AutoHH](https://github.com/servgri/autohh) · [GV](https://gitverse.ru/servgri/autohh)                                      | Сбор вакансий HH/Habr, LLM-оценка по резюме, сопроводительные, дайджест в Telegram | Python, n8n, OpenRouter, Telegram |
| [Telegram Downloader](https://github.com/servgri/telebot_downloader) · [GV](https://gitverse.ru/servgri/telebot_downloader) | Desktop/CLI/web: скачивание и сортировка файлов из Telegram-каналов | Python, Pyrogram, Tkinter |
| [MuseumGuide](https://github.com/servgri/museum_guide) · [GV](https://gitverse.ru/servgri/museum_guide)                     | Семантический поиск и RAG-чат по музейным экспонатам | Python, Transformers, RAG, Flask, PostgreSQL |
| [ImageMaker](https://github.com/servgri/ImageMaker) · [GV](https://gitverse.ru/servgri/ImageMaker)                          | Генерация изображений | Python |
