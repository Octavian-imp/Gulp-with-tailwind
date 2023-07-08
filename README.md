# `Сборка Gulp 08.07.2023`

перед началом работы выполнить
```bash 
    npm install
```

### `Структура сборки`
```bash
├───app
│   ├───assets
│   │   ├───fonts
│   │   │   ├───dist
│   │   │   └───src
│   │   └───images
│   │       ├───dist
│   │       │   └───stack
│   │       └───src
│   ├───components
│   ├───js
│   ├───minify -- минифицированные версии файлов из папок js и scss
│   │   ├───css
│   │   └───js
│   ├───pages
│   ├───scss
│   └───*.html -- страницы сгенерированные gulp-includoм
└───build
    ├───assets
    │   ├───fonts
    │   │   └───dist
    │   └───images
    │       └───dist
    ├───minify
    │    ├───css
    │    └───js
    └───*.html -- конечные страницы проекта
```
