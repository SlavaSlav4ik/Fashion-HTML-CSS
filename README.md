👗 Fashion-HTML-CSS — адаптивный лендинг для модного бренда
Fashion-HTML-CSS — это статический одностраничный сайт-лендинг для демонстрации коллекции одежды, реализованный с прицелом на современные практики фронтенда и сборку через Webpack.

📦 Ключевые технологии и инструменты
HTML5 — семантическая разметка страниц, SEO-оптимизация.

CSS3 (Flexbox, Grid, медиазапросы) — адаптивная верстка под любые устройства.

JavaScript (ES6+) — интерактивность: слайдер, мобильное меню и прочие UI-элементы.

Webpack — в качестве сборщика:

webpack.common.js — общие настройки (точка входа index.js, правила для CSS и изображений).

webpack.config.dev.js — dev-сборка с локальным сервером (webpack-dev-server), HMR и source-maps.

webpack.config.prod.js — продакшен-сборка с минификацией, оптимизацией ассетов и кэш-бастингом.

package.json — npm-скрипты:

npm run dev — запускает локальный сервер разработки (webpack serve).

npm run build — генерирует оптимизированные файлы в папку dist.

Static assets:

Папки img/ и PHOTO/ — растровые и векторные изображения.

favicon.ico, icon.png, site.webmanifest — поддержка PWA и «домашних экранов» на мобильных.

PWA-ready:

Есть robots.txt и 404.html для корректной маршрутизации на GitHub Pages и SEO.


🚀 Локальный запуск и сборка
Установить зависимости
npm install

Dev-сервер
npm run dev
Откроется http://localhost:8080 (или порт из конфига) с включённым HMR и source-maps.

gh-pages: https://slavaslav4ik.github.io/Fashion-HTML-CSS/
