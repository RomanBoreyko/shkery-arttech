# shkery-arttech

# 📁 Структура проекта "Шхеры — ArtTech MVP"

# === Корневая структура ===
# 📁 shkery-arttech/
# ├── README.md
# ├── .gitignore
# ├── requirements.txt
# ├── scripts/
# ├── data/
# ├── lore/
# ├── personas/
# ├── events/
# ├── economy/
# ├── notebooks/
# └── streamlit_app/


# === README.md ===
"""
# Shkery ArtTech MVP

Интерактивная симуляция мира Шхер: экономика, политика, меметика, хроники.

## Модули:
- 💾 Лор: markdown-база сеттинга
- 📈 Экономика: симулятор биржи ШОБ
- 🤖 AI-хронист: ответы от имени персонажей
- 🌐 Streamlit-интерфейс (опционально)

## Как запустить:
1. `pip install -r requirements.txt`
2. Запусти примеры из notebooks/
3. Лор-структура: смотри папки lore/, personas/, events/
"""


# === .gitignore ===
"""
__pycache__/
.env
*.pyc
.ipynb_checkpoints/
data/generated/
"""


# === requirements.txt ===
"""
openai
pandas
streamlit
python-dotenv
llama-index
langchain
"""


# === scripts/generate_report.py ===
"""
Генерирует аналитическую записку в стиле В. Виры по событиям из events/
"""

# === lore/ ===
# Markdown-файлы со статьями о ЦРБ, Медкорпусе, Канцелярии, Ходоках и т.д.

# === personas/ ===
# Досье персонажей: В. Вира, Святоша, С. Шейн-Шиловски и т.д.

# === events/ ===
# Хронология событий в мире: биологические кризисы, диверсии, биржевые скачки.

# === economy/shob_simulator.py ===
"""
Python-модуль, симулирующий биржу ШОБ: опционы, спот, поставки.
"""

# === notebooks/ ===
# Jupyter-ноутбуки для аналитики и тестирования AI-агента

# === streamlit_app/ ===
# Интерфейс для визуализации состояния мира и общения с AI-хрониста
