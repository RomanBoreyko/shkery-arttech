shkhera-simulation/
│
├── README.md
├── LICENSE
│
├── lore/                        # Лор и хроники мира
│   ├── notas/                  # Аналитические ноты (опционы, отчёты)
│   ├── personas/               # Персонажи (досье, речи, роли)
│   ├── events/                 # События мира (кризисы, погромы, реформы)
│   ├── factions/               # ЦРБ, Медкорпус, Администрация и т.д.
│   └── glossary.md             # Глоссарий терминов
│
├── ai_agents/                  # Промпты и профили для ИИ
│   ├── vira.md                 # Вероника Вира — системный аналитик
│   ├── lilich.md               # Р. Лилич — торговка меметиками
│   └── system_prompt.md        # Общие принципы симуляции
│
├── simulation/                 # Финансовая и меметическая симуляция
│   ├── market_model.py         # Ценообразование на ШОБ
│   ├── incident_generator.py   # Генератор кризисов (AI или вручную)
│   ├── positions.csv           # История опционных позиций
│   └── parameters.yaml         # Настройки среды
│
├── streamlit_app/             # Интерфейс для пользователей
│   └── app.py
│
├── notebooks/                 # Jupyter-ноутбуки для анализа
│   └── forward_memetics.ipynb
│
└── tools/
    └── gpt_query.py           # Обёртка для OpenAI API
