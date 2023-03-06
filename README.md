# devops-netology
Следующие файлы будут проигнорированы в будущем благодаря добавленному в файл terraform/.gitignore содержимому из https://github.com/github/gitignore/blob/master/Terraform.gitignore

* Все вложенные Локальные директории .terraform **/.terraform/*

* .tfstate files *.tfstate *.tfstate.*

* Файлы журнала сбоев crash.log crash.*.log

* Исключены все файлы .tfvars, которые могут содержать конфиденциальные данные, такие как пароль, закрытые ключи и другие секреты. *.tfvars *.tfvars.json

* Игнорировать файлы переопределения, поскольку они обычно используются для локального переопределения ресурсов   override.tf override.tf.json *_override.tf *_override.tf.json

* Игнорировать файлы конфигурации командной строки   .terraformrc terraform.rc

