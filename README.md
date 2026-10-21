# Мое портфолио

Кейс «Как я встроил дизайн в разработку KasperskyOS for Mobile».

## Файлы

- `index.html` — страница со стилями и навигацией.
- `assets/` — изображения, SVG-схемы, локальные шрифты Inter и PDF-резюме.
- `.nojekyll` — статическая публикация без обработки Jekyll.

## Просмотр

Откройте `index.html` в браузере или запустите в корне `python3 -m http.server 8000` и откройте `http://localhost:8000`.

## Публикация на GitHub Pages

После слияния PR в `main`: Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save. Адрес опубликованной страницы появится в настройках Pages.

Страница использует относительные пути и работает в подкаталоге репозитория. Резюме скачивается из `assets/Alexander-Egorov-Resume.pdf`.

Шрифты Inter распространяются по лицензии SIL Open Font License; текст лицензии включён в `assets/Inter-LICENSE.txt`.
