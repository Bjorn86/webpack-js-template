# Template JS проекта с Webpack

## Оглавление

- [Дополнительные библиотеки](#дополнительные-библиотеки)
- [Сценарии запуска](#сценарии-запуска)
- [Автор](#автор)

## Дополнительные библиотеки

- Webpack:
  - [`webpack`](https://webpack.js.org/)
  - [`webpack-cli`](https://www.npmjs.com/package/webpack-cli)
  - [`webpack-dev-server`](https://www.npmjs.com/package/webpack-dev-server)
  - [`clean-webpack-plugin`](https://www.npmjs.com/package/clean-webpack-plugin)
  - [`html-webpack-plugin`](https://www.npmjs.com/package/html-webpack-plugin)
  - [`css-minimizer-webpack-plugin`](https://www.npmjs.com/package/css-minimizer-webpack-plugin)
  - [`mini-css-extract-plugin`](https://www.npmjs.com/package/mini-css-extract-plugin)
  - [`terser-webpack-plugin`](https://www.npmjs.com/package/terser-webpack-plugin)
- Стили
  - [`sass`](https://www.npmjs.com/package/sass)
  - [`sass-loader`](https://www.npmjs.com/package/sass-loader)
  - [`css-loader`](https://www.npmjs.com/package/css-loader)
  - [`postcss-loader`](https://www.npmjs.com/package/postcss)
  - [`postcss-preset-env`](https://www.npmjs.com/package/postcss-preset-env)
- JS:
  - [`@babel/core`](https://babeljs.io/)
  - [`babel-loader`](https://www.npmjs.com/package/babel-loader)
  - [`@babel/preset-env`](https://babeljs.io/docs/en/babel-preset-env)
  - [`core-js`](https://www.npmjs.com/package/core-js)
- Линтер
  - [`eslint`](https://eslint.org/)
  - [`eslint-config-prettier`](https://www.npmjs.com/package/eslint-config-prettier)
  - [`eslint-config-airbnb-base`](https://www.npmjs.com/package/eslint-config-airbnb-base)
  - [`eslint-plugin-import`](https://www.npmjs.com/package/eslint-plugin-import)
- Форматирование кода
  - [`prettier`](https://prettier.io/)
- Менеджеры Git hooks
  - [`husky`](https://typicode.github.io/husky/)
  - [`lint-staged`](https://www.npmjs.com/package/lint-staged)
  - [`commitizen`](https://www.npmjs.com/package/commitizen)
  - [`cz-conventional-changelog`](https://www.npmjs.com/package/cz-conventional-changelog)
- Прочии
  - [`cross-env`](https://www.npmjs.com/package/cross-env)

## Сценарии запуска

- `npm start` - режим разработки с запуском локального сервера
- `npm run build` - режим сборки проекта в продакшн
- `npm run lint` - запускает линтер
- `npm run lint:fix` - запускает линтер, в режиме устранения мелких замечаний
- `npm run format` - запуск форматера кода
- `npm run prepare` - подготавливает Husky к работе, запускается единожды при старте проекта
- `npm run commit` - запускает commitizen для коммита

## Автор

**Данила Легкобытов**

- e-mail: [legkobytov-danila@yandex.ru](mailto:legkobytov-danila@yandex.ru)
- LinkedIn: [in/danila-legkobytov](https://www.linkedin.com/in/danila-legkobytov/)
- Telegram: [@danila_legkobytov](https://t.me/danila_legkobytov)
- Frontend Mentor: [@danila_legkobytov](https://www.frontendmentor.io/profile/Bjorn86)
