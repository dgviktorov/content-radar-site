# Content Radar — public site

Public pages for Content Radar (home, Privacy Policy, Terms of Use). They are used as the app's home page and policy links on the Google OAuth consent screen.

Публичные страницы Content Radar: главная, политика конфиденциальности и условия использования. Нужны для экрана согласия Google OAuth (раздел Branding в Google Cloud).

## Адреса

- Главная: https://dgviktorov.github.io/content-radar-site/
- Privacy Policy: https://dgviktorov.github.io/content-radar-site/privacy.html
- Terms of Use: https://dgviktorov.github.io/content-radar-site/terms.html

Эти адреса вписаны (или будут вписаны) в Google Cloud. Если переименовать файл или репозиторий, ссылки в Google Cloud перестанут работать. Поэтому имена не менять.

## Как устроено

- Обычные HTML-страницы и один файл стилей `style.css`. Без JavaScript, аналитики, cookies, шрифтов и библиотек с чужих сайтов.
- Публикует GitHub Pages: ветка `main`, корень репозитория. Сборки нет. Пустой файл `.nojekyll` говорит GitHub отдавать файлы как есть.
- Адрес работает только по HTTPS.

## Как изменить текст

1. Открой нужный файл на GitHub (например, `privacy.html`) и нажми значок карандаша **Edit**.
2. Измени текст. Если меняется смысл политики или условий, обнови дату в строке `Last updated`.
3. Нажми **Commit changes…** → **Commit changes**.
4. Через 1–2 минуты изменения появятся на сайте. Ход публикации виден на вкладке **Actions** репозитория.

## Важно: репозиторий публичный

Всё, что лежит здесь, видно всем. Не добавлять сюда:

- ключи, токены, пароли, содержимое `.env`;
- личные данные, почту, финансовые сведения;
- содержимое `private/`, файлы выпусков, заметки;
- сведения о серверах.

Политика конфиденциальности должна описывать то, что программа делает на самом деле. Если меняется работа с Google Drive, сначала обновить `privacy.html`, потом включать изменение.
