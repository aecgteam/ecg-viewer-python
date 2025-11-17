# Annotated ECG HL7 parser and viewer

A minimalist app for parsing and viewing aECG files.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://annotated-ecg.streamlit.app/)

1. Клонирование репозитория
```
git clone https://github.com/ghilesmeddour/ecg-viewer.git
cd ecg-viewer
```
2. Создание виртуального окружения (рекомендуется)
```
# Для Windows
python -m venv venv
venv\Scripts\activate

# Для Linux/Mac
python3 -m venv venv
source venv/bin/activate
```
3. Установка зависимостей
```
pip install -r requirements.txt
```
Если файла requirements.txt нет, установите зависимости вручную:
```
pip install streamlit plotly pandas numpy scipy
```
4. Запуск приложения
```
streamlit run app.py
```
Или если основной файл называется иначе:
```
streamlit run main.py
```
5. Открытие в браузере
Приложение автоматически откроется в браузере по адресу: http://localhost:8501

<img src="res/app_screen.png" width="900">
