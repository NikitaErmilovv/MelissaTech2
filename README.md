# Melissa-tech2 (репозиторий MelissaTech2)

Второй монорепозиторий статических прототипов для **melissa-tech.ru**: отдельные папки → отдельные URL (`https://melissa-tech.ru/<папка>/`).

Первый набор сайтов остаётся в [Melissa-tech.ru](https://github.com/NikitaErmilovv/Melissa-tech.ru).  
Здесь — **новые** прототипы, без дублирования старых.

## Деплой (Timeweb)

1. Приложение **HTML / CSS / JS** в Timeweb, ветка **`master`**, webhook на push.
2. Корень репозитория = корень выкладки (как в первом проекте).
3. Каждый прототип — папка в корне, например `my-studio/`.
4. Прод: `https://melissa-tech.ru/my-studio/` (путь согласуем при добавлении сайта).
5. После изменений — push в `master` и при необходимости обновить `deploy-version.txt` в корне и в папке сайта.

```
deploy=git-push-timeweb-hook
```

## Новый прототип (шаблон как D2 / dark-detailing)

- Скопировать структуру из первого репо: `index.html`, `styles.css`, `nav.js`, `server.py`, `start.bat`, `deploy-version.txt`, `README.md`.
- Относительные ссылки, без жёсткого `/` в корне домена.
- Локально: `python server.py` в папке сайта.
- Добавить строку в таблицу «Сайты» ниже.

## Сайты

| Папка | Описание | Прод |
|-------|----------|------|
| `dark-detail/` | Dark Detailing, Оренбург (копия с `dark-detailing/`) | https://melissa-tech.ru/dark-detail/ |

## Локальная разработка

Корневая `index.html` — заглушка (как на первом репо), список проектов в открытом доступе не публикуем.
