# DevOps-netology
Мой репозиторий для курса DevOps

## .gitignore для Terraform
В папке terraform добавлен .gitignore, который будет игнорировать:
- Папки **/.terraform/ - содержат скачанные модули и провайдеры
- Файлы *.tfstate и *.tfstate.* - содержат состояние инфраструктуры
- Файлы crash.log - логи ошибок
- Файлы *.tfvars и *.tfvars.json - содержат чувствительные переменные
- Файлы override.tf, *_override.tf - файлы переопределения
- Файлы .terraformrc и terraform.rc - конфигурации CLI

## Что игнорируется в terraform/.gitignore (расшифровка правил)

В файле `.gitignore` используются следующие паттерны:

- `**/.terraform/*` — игнорируются все файлы и папки, находящиеся в любой папке `.terraform` на любом уровне вложенности (символы `**` означают "любая вложенность", а `*` — "любые символы")

- `*.tfstate` и `*.tfstate.*` — игнорируются все файлы, заканчивающиеся на `.tfstate`, а также файлы, в имени которых после `.tfstate` идёт точка и любые символы (например, `.tfstate.backup`)

- `crash.log` — игнорируется конкретный файл с именем `crash.log`

- `*.tfvars` и `*.tfvars.json` — игнорируются все файлы, заканчивающиеся на `.tfvars`, а также файлы, заканчивающиеся на `.tfvars.json` (символ `*` означает "любое имя файла")

- `override.tf`, `override.tf.json`, `*_override.tf`, `*_override.tf.json` — игнорируются конкретные файлы override.tf и override.tf.json, а также любые файлы, которые заканчиваются на `_override.tf` или `_override.tf.json` (символ `*` заменяет любую часть имени)

- `.terraformrc` и `terraform.rc` — игнорируются конкретные файлы с такими именами

## Скриншоты выполнения задания

![](screenshots/1.png)

![](screenshots/2.png)

![](screenshots/3.png)

![](screenshots/4.png)

![](screenshots/5.png)
