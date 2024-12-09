https://Ashuksu.github.io/test-project/public

https://Ashuksu.github.io/test-project/public/second

## Использование

* `npm i` --- усстановка нод_модулей

* `npm run dev` --- сборка проекта (CSS и HTML файлы потом также будут собираться этой командой), и в папке /public/js появятся файлы bundle.js и bundle.js.map.

* `npm run build` --- сборка проекта, но уже итоговая (с оптимизацией, максимальной минимизацией файла), которую можно выкладывать на хостинг.

* `npm run watch` --- режим автоматического просмотра изменений файлов проекта с автоматическим сборкой измененных файлов.

* `npm run start` --- запуск локального сервера, который запустит HTML страницу и также будет отслеживать изменения в файлах.

* `npm run build-and-beautify` --- сборка проекта, в папке public появится собранный статический сайт.



## Git

#### Flow

Основная модель - [Branching model](https://nvie.com/posts/a-successful-git-branching-model)

#### Branching

* `master` - ветка кода `production` окружения

* `develop` - основная ветка куда заливаются все `feature/<issue-key>` ветки например `feature/CODE-123`, ветка для разработки



## Сборка

#### Исходник

Простой статический сайт на Webpack 4 ( [ссылка на github](https://github.com/Harrix/static-site-webpack-habr) )

#### Минимальные версии node, npm

* `node -v` v17.4.0

* `npm -v` 8.4.1

