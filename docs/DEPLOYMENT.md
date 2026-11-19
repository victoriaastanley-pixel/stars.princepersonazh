# GitHub → Vercel

## Подключение

- Репозиторий: https://github.com/victoriaastanley-pixel/stars.princepersonazh
- Production Branch: `main`.
- Рабочее пространство Vercel: `prince-cec8`.
- Team ID: `team_EnnYzWtv2o7MP0i1FUcT3gvX`.
- Проект: `stars-princepersonazh`.
- Project ID: `prj_qXQeGaHmAeGdHUYYQenzr6XJngvV`.
- Основной адрес: https://stars-princepersonazh.vercel.app/
- Панель: https://vercel.com/prince-cec8/stars-princepersonazh

19 ноября 2026 года пользователь подтвердил доступ к рабочему пространству, связал аккаунт GitHub и разрешил приложению Vercel доступ к репозиторию. Проект создан через встроенную Git-интеграцию. Первая production-публикация `dpl_76PSN1GjyoMCfDc7yimed48CfKXE` завершилась со статусом `READY` из коммита `21feaa9feb0e745f2eecbd7dccd8fb5afddbfd37`.

## Как выходят обновления

Изменения, отправленные в `main`, автоматически запускают публикацию Vercel. Для других веток и pull request создаются предпросмотры. GitHub Actions, отдельный сервер и база данных текущей игре не нужны.

- `vercel.json`: статические файлы из корня, без установки зависимостей и сборки.
- `.vercelignore`: исключение документации и локальных служебных файлов из загрузки сайта.
- `.gitignore`: исключение `.env` и локальных настроек из обычного добавления в Git.

Для игры секреты и переменные окружения не нужны. Пароли, коды и любые секреты пользователь вводит самостоятельно в сервисах; агент их не читает и не создаёт. Защита публикаций оставлена в исходных настройках Vercel.

## Проверка

Основной адрес открылся в браузере. Проверены нажатия на три разные звезды, счётчик «Поймано 3 из 3», открытие окна подарка, отображение логотипа и двух обложек, наличие исходной ссылки Google Drive. Содержимое самой методички не проверялось.

## Домен и тариф

Существующий домен `stars.princepersonazh.ru` и DNS не менялись. Подключать домен только по отдельному указанию пользователя. Платная подписка не оформлялась. Hobby ограничен личным или некоммерческим использованием; перед коммерческим запуском требуется отдельно решить вопрос тарифа.

## Документация

- https://vercel.com/docs/git/vercel-for-github
- https://vercel.com/docs/builds/configure-a-build
- https://vercel.com/docs/project-configuration/vercel-json
- https://vercel.com/docs/deployments/vercel-ignore
- https://vercel.com/legal/terms
