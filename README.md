# ProfitLab AI

**Responsive static demo** for business analytics (hackathon project)  
**Адаптивное статическое демо** для бизнес-аналитики (хакатон-проект)

A lightweight no-server HTML/CSS/JavaScript prototype that analyzes sales data from CSV files.  
Calculates revenue, costs, profit, margins, identifies loss-making and low-margin products — all processed locally in the browser.

Лёгкий прототип без сервера на HTML/CSS/JavaScript, который анализирует данные продаж из CSV-файлов.  
Считает выручку, затраты, прибыль, маржу, определяет убыточные и низкомаржинальные товары — всё обрабатывается локально в браузере.

## Features / Возможности

- Upload CSV and instantly get analytics / Загрузка CSV и мгновенный анализ
- Revenue, cost, profit and margin calculations / Расчёт выручки, затрат, прибыли и маржи
- Grouping by product / Группировка по товарам
- Flagging of loss-making products / Выделение убыточных позиций
- Lowest margin products ranking / Рейтинг товаров с самой низкой маржой
- Fully responsive design / Полностью адаптивный дизайн
- Multilingual interface (Russian / Kazakh / English) / Мультиязычный интерфейс
- No backend, no database — everything runs in the browser / Без бэкенда и базы данных

## How to run / Как запустить

1. Download or clone this repository / Скачайте или клонируйте репозиторий
2. Open `index.html` in any modern browser / Откройте `index.html` в любом современном браузере
3. Click **Open demo / Открыть демо**
4. Upload your CSV file or download the sample CSV / Загрузите CSV или скачайте пример

## CSV Format / Формат CSV

| Column / Колонка | Description / Описание              |
|------------------|-------------------------------------|
| `product`        | Product name / Название товара      |
| `quantity`       | Number of units sold / Количество   |
| `price`          | Selling price per unit / Цена       |
| `cost`           | Cost per unit / Себестоимость       |

Example / Пример:

```csv
product,quantity,price,cost
Laptop,12,89900,65000
Mouse,45,2500,1100
Keyboard,28,7800,4200
```

## Languages / Языки

- Русский
- Қазақша
- English

Language preference is saved in the browser.  
Выбранный язык сохраняется в браузере.

## Important Notes / Важные замечания

This is a **static MVP prototype**.  
Это **статический MVP-прототип**.

- All calculations are rule-based (not powered by an external AI model)  
  Все расчёты выполняются по правилам (не с помощью внешней AI-модели)
- Dashboard numbers are illustrative until you upload a real CSV  
  Цифры на дашборде носят иллюстративный характер, пока вы не загрузите свой CSV
- Data never leaves your browser  
  Данные никогда не покидают ваш браузер

### Current Limitation / Текущее ограничение

At the moment the system works **only with CSV files**.  
На данный момент система работает **только с CSV-файлами**.

In the future a text robot (chat interface) will be added, so you will be able to ask questions in natural language.  
В будущем будет добавлен текстовый робот (чат-интерфейс), чтобы можно было задавать вопросы обычным текстом.
```