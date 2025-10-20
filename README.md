# Plexi GeoAI Platform v0.2  
*An open, modular AI‑powered system for quantitative seismic, rock physics, reservoir and geostatistical interpretation — integrating Fortran HPC cores with Python and modern ML.*

---

## 🌍 Vision  
Plexi GeoAI соединяет точность физических моделей и гибкость искусственного интеллекта, создавая единую экосистему для численного анализа, обучения и интерпретации геонаучных данных.  
Проект совмещает Fortran‑ядра, Python‑фреймворк и RAG‑базу знаний, превращая классическую интерпретацию в осмысленный, объяснимый процесс.

---

## 🧠 Core Modules  

| Модуль | Предметная область | Назначение |
|--------|--------------------|-------------|
| **Seismic Core** | Сейсмика и атрибуты | Импорт ZGY/SEGY, 3D вьюеры, спектральный анализ, PhaseMismatch plugin |
| **Rock Physics Core** | Рок‑физика | Узловой редактор DEM/SCA/Gassmann, AutoML петроупругих моделей |
| **QI & Inversion Core** | Количественная интерпретация | Байесовская инверсия, facies / uncertainty моделирование |
| **GeoStat Core** | Геостатистика | SGS/MPS симуляции, вариограммы, ко‑симуляции с атрибутами |
| **GeoMech Core** | Геомеханика | Давления (Eaton/Bowers), напряжения и уплотнение |
| **Knowledge Core (RAG)** | Научная память | Каталог 24 классических источников (Mavko, Vernik, Doyen, Dutta и др.) |
| **GeoAI Assistants** | Искусственный интеллект | Пять агентов (Seismic, RockPhysics, QI, GeoStat, GeoMech) для объяснимых анализов |

---

## 🛠️ Tech Stack  
Python 3.11 | Fortran (f2py / OpenMP) | PySide6 Qt 6.7 | NumPy | xarray | Dask | VisPy | RAG AI | Sphinx | Poetry | CI/CD.  

---

## 📅 Roadmap v0.2  

| Этап | Цель | Состояние |
|------|------|-----------|
| E0 | Архитектура Knowledge Core | ✅ done |
| E1 | Векторная индексация RAG и BM25 поиск | ⏳ in progress |
| E2 | Ассистенты Seismic и RockPhysics | planned |
| E3 | Ассистенты QI и GeoStat + AI Insights Dock | planned |
| E4 | Геомеханика и Fortran Pressure/Stress | planned |
| E5 | Интеграция и демо‑сборка v0.2 | scheduled |

Ориентировочный срок до демо: ≈ 30 недель.  

---

## 📂 Repository Structure  

```
plexi-geoai-platform/
│
├── plexi_geoai/
│   ├── core/            # seismic, petroelastic, geostat, inversion modules
│   ├── ai_core/         # знаниевое ядро и ассистенты
│   ├── ui/              # Qt-интерфейс и виджеты
│   ├── fortran_src/     # DEM, Gassmann, AVO, SGS, GeoPressure
│   └── __init__.py
│
├── knowledge_root/      # RAG-библиотека дисциплин
│   ├── seismic_core/
│   ├── rock_physics_core/
│   ├── qi_core/
│   ├── geostat_core/
│   ├── geomech_core/
│   └── heterogeneous_media/
│
├── examples/            # демо-проекты и синтетика
├── tests/               # pytest-наборы
├── docs/                # sphinx-документация
├── LICENSE
└── README.md
```

---

## 📘 License  
MIT License — свободно для науки, образования и open research инициатив.  

---

_“From wavefield to insight — Plexi GeoAI unites physics and intelligence.”_
```

***


