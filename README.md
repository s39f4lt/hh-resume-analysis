# Анализ резюме HeadHunter

Исследование структуры данных, преобразование признаков, визуализация зависимостей и очистка данных с HeadHunter.

## Файлы проекта

- `solution.ipynb` - выполненное задание с графиками и выводами.
- `template.ipynb` - исходный шаблон.
- `data/ExchangeRates.csv` - исторические курсы валют.
- `data/dst-3.0_16_1_hh_database.csv` - исходные данные о резюме.

## Датасет

Файл резюме весит более 450 МБ и исключён из Git. Перед запуском скачайте его по ссылке и поместите в папку `data` под исходным именем.

**Ссылка на датасет:** https://drive.google.com/file/d/1ktAIhiR9Y8iNiQ_A9GmwW8ROi-_oTf8l/view?usp=share_link.

Файл курсов валют `data/ExchangeRates.csv` остаётся в репозитории.

## Запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Откройте `solution.ipynb` и выполните ячейки последовательно. Графики сохранены в выводе ноутбука.
