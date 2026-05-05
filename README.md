[README (1).md](https://github.com/user-attachments/files/27395661/README.1.md)
# -# 💱 Currency Converter - Конвертер валют

**Автор:** Милушов Даниил Юрьевич 
**GitHub:** [https://github.com/gladi0lus000/-.git](https://github.com/gladi0lus000/-.git)

## 📖 Описание

Currency Converter — это графическое приложение на Python с использованием библиотеки Tkinter для конвертации валют по актуальным курсам. Программа использует внешнее API (ExchangeRate-api.com) для получения актуальных курсов валют, сохраняет историю конвертаций в JSON-файл и позволяет загружать данные из истории.

## 🔑 Как получить API-ключ

Для работы программы необходим бесплатный API-ключ от ExchangeRate-api.com:

1. Перейдите на сайт [https://app.exchangerate-api.com/sign-up](https://app.exchangerate-api.com/sign-up)
2. Зарегистрируйтесь (можно через Google или email)
3. После регистрации вы получите API-ключ
4. В коде программы замените `YOUR_API_KEY` на полученный ключ:
   ```python
   API_KEY = "ваш_ключ_здесь"

## 🛠 Установка и запуск

### Требования
- Python 3.6 или выше
- Стандартные библиотеки: `tkinter`, `json`, `os`, `datetime`

### Запуск

```bash
# Клонировать репозиторий
git clone https://gitverse.ru/Ваш_Ник/имя_репозитория.git

# Перейти в директорию проекта
cd имя_репозитория

# Запустить программу
python CurrencyConverter.py
