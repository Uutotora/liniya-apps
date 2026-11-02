# Линия — приложения учеников

Выберите своё имя в таблице. Скачайте ZIP, распакуйте его полностью и запустите приложение.

| Ученик | Система | Скачать | Бот преподавателей | Готовность |
|---|---|---|---|---|
| Лиза | macOS | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-liza-macOS.zip) | [Линия · Лиза](https://t.me/liniya_liza_2026_bot) | Работает |
| Илья | macOS | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-ilya-macOS.zip) | [Линия · Илья](https://t.me/liniya_ilya_2026_bot) | Работает |
| Арсений | macOS | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-arseniy-macOS.zip) | [Линия · Арсений](https://t.me/liniya_arseniy_2026_bot) | Работает |
| Роман | Windows 11 | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-roman-Windows-win-x64.zip) | [Линия · Роман](https://t.me/liniya_roman_2026_bot) | Работает |
| Варя | Windows 11 | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-varya-Windows-win-x64.zip) | [Линия · Варя](https://t.me/liniya_varya_2026_bot) | Работает |
| Матвей | Windows 10 | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-matvey-Windows-win-x64.zip) | [Линия · Матвей](https://t.me/liniya_matvey_2026_bot) | Приложение готово; регистрация бота ожидает снятия лимита Telegram |
| Никита | Windows 10 | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-nikita-Windows-win-x64.zip) | [Линия · Никита](https://t.me/liniya_nikita_2026_bot) | Приложение готово; регистрация бота ожидает снятия лимита Telegram |
| Иван | Windows 10 | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-ivan-Windows-win-x64.zip) | [Линия · Иван](https://t.me/liniya_ivan_2026_bot) | Приложение готово; регистрация бота ожидает снятия лимита Telegram |
| Дарья | Windows 10 Pro | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-darya-Windows-win-x64.zip) | [Линия · Дарья](https://t.me/liniya_darya_2026_bot) | Приложение готово; регистрация бота ожидает снятия лимита Telegram |
| Мария | Windows 10 Pro | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-mariya-Windows-win-x64.zip) | [Линия · Мария](https://t.me/liniya_mariya_2026_bot) | Приложение готово; регистрация бота ожидает снятия лимита Telegram |
| Эля | Windows 10 Pro | [Архив](https://github.com/Uutotora/liniya-apps/releases/download/students-v2.1.0/Liniya-elya-Windows-win-x64.zip) | [Линия · Эля](https://t.me/liniya_elya_2026_bot) | Приложение готово; регистрация бота ожидает снятия лимита Telegram |

> 2 ноября 2026: Telegram ограничил создание новых ботов примерно на сутки после первых пяти. Для Матвея, Никиты, Ивана, Дарьи, Марии и Эли архивы подготовлены, но отправка преподавателю заработает после подключения их ботов. Ссылки на этих ботов пока зарезервированы в конфигурации, регистрация ещё не завершена.

## Первый запуск

Приложение уже настроено под ученика. Вводить коды и адреса не нужно. Оно покажет номер подключения: сообщите его преподавателю, чтобы он нажал «Подключить компьютер» в соответствующем боте. Это требуется только для нового подключения.

Преподаватель входит в бот сообщением `я учитель: ваш пароль`. Пароль выдаётся отдельно. Несколько преподавателей могут работать одновременно. После подтверждения компьютера снимки приходят всем вошедшим преподавателям. Ответьте текстом на нужный снимок — ученик увидит ответ в приложении.

Mac: **⇧⌘2** — отправить весь экран, **⇧⌘Пробел** — показать/скрыть панель. При первом снимке разрешите запись экрана.

Windows: **Ctrl+Shift+2** — отправить весь экран. Сочетания можно изменить в настройках.

## Совместимость

Mac: macOS 14+, Intel и Apple Silicon в одном архиве. Подпись ad-hoc, без нотарификации Apple. Если macOS блокирует приложение, разрешите именно его через «Конфиденциальность и безопасность».

Windows: x64, .NET включён. Рекомендуется Windows 11; Windows 10/Pro требует build 19041 или новее и проверки запуска на конкретном компьютере. Выпуск не проходил отдельную проверку на Windows 10. Подписи Authenticode пока нет. Для Windows ARM64 запросите отдельную сборку.

Нужен интернет. При отзыве доступа преподавателем переподключите компьютер через настройки. Не пересылайте учительский пароль ученикам.

В этом репозитории только приложения и инструкции. Каждый архив имеет свой сервер и профиль подключения; ключей доступа к ученику, токенов Telegram и пароля преподавателя внутри нет. Контрольные суммы SHA-256 лежат рядом с архивами в Releases.
