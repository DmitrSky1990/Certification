# Certification
Откройте Postman и импортируйте (import) коллекцию JSON 
POST https://api.github.com/repos/DmitrSky1990/Certification/issues -команда для создания issue(проблема)
GET https://api.github.com/issues - команда для выведения списка issues, перечисляет issue(проблемы), во всех видимых репозиториях пользователя, включая собственные репозитории, репозитории участников и репозитории организаций
GET https://api.github.com/- команда для выведения списка issues, привязанных к конкретному репозиторию.
PATCH repos/DmitrSky1990/Certification/issues/1- команда для изменения конкретной issue(проблемы)
PUT repos/DmitrSky1990/Certification/issues/1/lock- поскольку в Github не предусмотрено удаление issue(проблемы), с помощью REST API, данная команда позволяет заблокировать issue с возможностью указать причину (lock_reason)
DELETE repos/DmitrSky1990/Certification/issues/1/lock- данная команда позволяет разблокировать issue (проблему).
