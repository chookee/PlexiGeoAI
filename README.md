# Plexi GeoAI Platform v0.2  

[![Project Status](https://img.shields.io/badge/status-active-green.svg)](https://github.com/chookee/PlexiGeoAI)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)
[![Docs Build](https://img.shields.io/badge/docs-Sphinx-blue.svg)](https://github.com/chookee/PlexiGeoAI/tree/main/docs)
[![Python](https://img.shields.io/badge/python-3.11%2B-orange.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey.svg)]()

*An open, modular AI‑powered ecosystem for quantitative seismic, rock physics, reservoir and geostatistical interpretation.*

---

## 🌍 Vision  
Plexi GeoAI соединяет физику, данные и интеллект в единой платформе.  
Цель — создать экосистему для интерпретации сейсмических и петрофизических данных, где модели и AI работают на уровне научных смыслов, а не просто чисел.

---

## 🧠 Core Modules  

| Модуль | Область | Назначение |
|--------|----------|------------|
| **Seismic Core** | Сейсмика и атрибуты | Импорт ZGY/SEGY, спектральный анализ, 3D визуализация |
| **Rock Physics Core** | Петрофизика | DEM, SCA, Gassmann, анизотропия, узловой редактор |
| **QI & Inversion Core** | Количественная интерпретация | Байесовская инверсия, фейси, неопределённость |
| **GeoStat Core** | Геостатистика | SGS/MPS симуляции, вариограммы, ко‑симуляции |
| **GeoMech Core** | Геомеханика | Давление Eaton/Bowers, stress path, уплотнение |
| **Knowledge Core (RAG)** | Знания и формулы | База 24 классических источников (Mavko, Vernik, Doyen, Dutta и др.) |
| **GeoAI Assistants** | Искусственный интеллект | Пять интерактивных агентов (Seismic, RockPhysics, QI, GeoStat, GeoMech) |

---

## 🛠️ Tech Stack  
Python 3.11 • Fortran (f2py/OpenMP) • PySide6 Qt 6.7 • NumPy • xarray • Dask • VisPy • RAG AI • Sphinx Docs  

---

## 📅 Roadmap v0.2  

| Этап | Цель | Статус |
|------|------|--------|
| E0 | Архитектура Knowledge Core | ✅ Done |
| E1 | Векторная индексация RAG / BM25 поиск | ⏳ In progress |
| E2 | Ассистенты Seismic + RockPhysics | 💡 Planned |
| E3 | Ассистенты QI и GeoStat + AI Insights Dock | 💡 Planned |
| E4 | GeoMech ядра давления/напряжений | 💡 Planned |
| E5 | Демо‑версия v0.2 и Sphinx Docs | 💡 Planned |

Всего ≈ 30 недель до демо‑релиза.  

---

## 📂 Repository Structure  

```
plexi-geoai-platform/
│
├── README.md
├── LICENSE
│
├── plexi_geoai/
│   └── __init__.py
│
└── knowledge_root/
    ├── README.md
    └── .keep
```

Эта минимальная структура — базис для дальнейшего развития.  
В будущем сюда добавятся Fortran‑модули, AI‑ядра и RAG‑индекс.

---

## 📘 License  
MIT License — свободно для науки, образования и open research инициатив.  

---

_“From wavefield to insight — Plexi GeoAI unites physics and intelligence.”_
```
