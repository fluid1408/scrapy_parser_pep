# Проект асинхронного парсинга

## Функции, которые выполняет парсер

- Сбор данных обо всех документах PEP (номер, название и статус)
- Подсчет количества документов PEP в каждом статусе и подсчет общего количества PEP-документов

## Технологии проекта

- Python — высокоуровневый язык программирования;
- Scrapy - фрэймворк для асинхронного парсинга;
- csv - библиотека для работы с файлами в формате csv в Python


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/fluid1408/scrapy_parser_pep.git

cd scrapy_parser_pep
```

Cоздать виртуальное окружение:

```
python3 -m venv venv
```

Активировать виртуальное окружение

```
source venv/bin/activate
```

Обновить менеджер пакетов pip

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

### Запуск асинхронного парсера из корневой директории командой

```
scrapy crawl pep
```

Автор: Шлемин С.А.
