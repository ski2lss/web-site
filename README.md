# GreenShop

Одностраничный макет магазина растений. В проекте нет JavaScript: меню Plant Care открывается тегом `<details>`, а окно Login/Register — с помощью CSS.

## Где что находится

- `index.html` — содержимое страницы.
- `style.scss` — подключает остальные стили.
- `variables.scss` — цвета.
- `mixins.scss` — общий контейнер.
- `reset.scss` — сброс браузерных отступов.
- `header.scss`, `button.scss`, `card.scss`, `footer.scss` — стили частей страницы.
- `style.css` — готовые стили, которые загружает браузер.

Открой `index.html` в браузере. После изменения SCSS пересобери его в `style.css` кнопкой **Watch Sass** в VS Code.
