# Лабораторная работа №4: ETL-процесс в Apache Spark

## Описание

В этом репозитории реализована лабораторная работа по теме **ETL-процессы в Apache Spark (PySpark)**.  
Студенты выполняют полный цикл: извлечение данных из CSV и SQLite, объединение, очистка и трансформация, агрегирование, фильтрация и загрузка результатов обратно — в базу и в файл Parquet.

## Данные

- **major-tech-stock-2019-2024.csv** — исторические котировки акций (Date, Open, High, Low, Close, Adj Close, Volume, Ticker) (https://www.kaggle.com/datasets/alfredkondoro/major-tech-stocks-time-series-2019-2024?resource=download).  
- **companies_db.sqlite** — база данных SQLite со справочной таблицей `companies` (Symbol, CompanyName, Sector, Country).  
  Таблица содержит компании, соответствующие тикерам из CSV.
- **USD_RUB_HistoricalData.csv** - файл содержит исторические данные по курсу доллара США (USD) к российскому рублю (RUB) за период примерно с 2019 по конец 2024 года. Данные представляют собой ежедневные котировки валютной пары USD/RUB.


