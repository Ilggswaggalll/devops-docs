# Эксплуатация

1. Убедитесь, что проверка `pylint` в Pull Request прошла.
2. Выполните слияние в `main`.
3. В Actions откройте Publish documentation.
4. Дождитесь завершения `build` и `deploy`.
5. Откройте URL из окружения `github-pages` и проверьте главную страницу.

Для ручной публикации используйте Actions → Publish documentation → Run workflow.
При ошибке откройте журнал шага, на котором остановился запуск.
