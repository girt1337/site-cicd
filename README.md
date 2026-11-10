# site-cicd

Небольшой статический сайт на HTML и CSS с автоматической публикацией через GitHub Actions и GitHub Pages.

## Структура проекта

```text
site-cicd/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
├── style.css
└── README.md
```

## Локальный запуск

Откройте `index.html` в браузере. Дополнительные зависимости и сборка не требуются.

## Публикация на GitHub Pages

1. Создайте репозиторий GitHub и загрузите в него файлы проекта.
2. Убедитесь, что основная ветка называется `main`.
3. Откройте **Settings → Pages**.
4. В разделе **Build and deployment** выберите **GitHub Actions** в качестве источника.
5. Отправьте изменения в ветку `main` или вручную запустите workflow **Deploy static site to GitHub Pages** на вкладке **Actions**.
6. После успешного выполнения workflow адрес опубликованного сайта появится в настройках Pages и в результате задания.

## Изменение сайта

- Разметка и текст: `index.html`.
- Цвета, размеры и внешний вид: `style.css`.
- Настройки автоматической публикации: `.github/workflows/deploy.yml`.
