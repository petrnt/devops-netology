# devops-netology
Следующие файлы будут проигнорированы в будущем благодаря добавленному terraform/.gitignore  https://github.com/github/gitignore/blob/master/Terraform.gitignore
# Все вложенные Локальные директории .terraform
**/.terraform/*

# .tfstate files
*.tfstate
*.tfstate.*

# Файлы журнала сбоев
crash.log
crash.*.log

# Исключить все файлы .tfvars, которые могут содержать конфиденциальные данные, такие как
# пароль, закрытые ключи и другие секреты.
*.tfvars
*.tfvars.json

# Игнорировать файлы переопределения, поскольку они обычно используются для локального переопределения ресурсов
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# ПРИМЕР Включить переопределенные файлы, которые вы хотите добавить в систему управления версиями, используя отрицаемый шаблон
# !example_override.tf

# ПРИМЕР Включить файлы tfplan, чтобы игнорировать вывод плана команды: terraform plan -out=tfplan
# example: *tfplan*

# Игнорировать файлы конфигурации командной строки
.terraformrc
terraform.rc

