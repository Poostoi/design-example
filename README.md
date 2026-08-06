# Дизайны — Прототипы

Статичные HTML-прототипы дизайна главной страницы учебного центра «Профессия».

## Просмотр локально

```bash
python3 -m http.server 8000
```

Откройте http://localhost:8000

## Деплой на GitHub Pages

### Вариант 1: корневая папка репозитория

1. Залейте папку `designs-preview/` в репозиторий
2. Settings → Pages → Source → Deploy from a branch → `main` / `/designs-preview`
3. Сайт будет доступен по адресу:
   ```
   https://<username>.github.io/<repo>/
   ```

### Вариант 2: отдельный репозиторий

1. Скопируйте содержимое папки `designs-preview/` в новый репозиторий
2. Settings → Pages → Source → Deploy from a branch → `main` / `/root`
3. Сайт будет доступен по адресу:
   ```
   https://<username>.github.io/<repo-name>/
   ```

## Структура

| Файл            | Стиль          | Описание                              |
|-----------------|----------------|---------------------------------------|
| `index.html`    | Витрина        | Галерея со всеми превью               |
| `bento.html`    | Bento          | Модульная сетка карточек              |
| `editorial.html`| Editorial     | Журнальная вёрстка                    |
| `dark.html`     | Dark           | Тёмная премиальная тема               |
| `colorful.html` | Colorful       | Яркие градиенты                       |
| `minimal.html`  | Minimal        | Чистый минимализм                     |
| `gradient.html` | Gradient       | Градиенты с blur-эффектами            |
| `glass.html`    | Glass          | Glassmorphism                         |
| `brutalist.html`| Brutalist      | Брутализм с жёсткими рамками         |
| `pastel.html`   | Pastel         | Мягкая пастельная палитра            |

## Управление

Каждый дизайн имеет плавающую кнопку в правом нижнем углу для переключения между дизайнами и возврата на витрину.