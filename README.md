# Personal Manager

Personal Manager - это приложение для управления сотрудниками, созданное с использованием React и Vite.

## Установка

1. Клонируйте репозиторий:
    ```sh
    git clone https://github.com/ksavdev/personal-manager.git
    ```
2. Перейдите в директорию проекта:
    ```sh
    cd personal-manager
    ```
3. Установите зависимости:
    ```sh
    npm install
    ```

## Скрипты

- `npm run dev` - Запуск приложения в режиме разработки.
- `npm run build` - Сборка приложения для продакшена.
- `npm run lint` - Запуск ESLint для проверки кода.
- `npm run preview` - Предпросмотр собранного приложения.

## Структура проекта

```
personal-manager/
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── README.md
├── vite.config.js
├── public/
└── src/
    ├── index.css
    ├── main.jsx
    ├── assets/
    └── components/
        ├── app/
        │   ├── app.css
        │   └── app.jsx
        ├── app-filter/
        │   ├── app-filter.css
        │   └── app-filter.jsx
        ├── app-info/
        │   ├── app-info.css
        │   └── app-info.jsx
        ├── employees-add-form/
        │   ├── employees-add-form.css
        │   └── employees-add-form.jsx
        ├── employees-list/
        │   ├── employees-list.css
        │   └── employees-list.jsx
        ├── employees-list-item/
        │   ├── employees-list-item.css
        │   └── employees-list-item.jsx
        └── search-panel/
            ├── search-panel.css
            └── search-panel.jsx
```

## Используемые технологии

- React
- Vite
- ESLint
- Bootstrap
- Font Awesome

