# devops-netology
first line
**/.terraform/* Игнорировать все каталоги и файлы внутри каталогов .terraform

Для всех типов файлов и файлов ниже, правила применяются внутри каталога, в котором будет лежать файл .gitignore. В данном случае это - devops-netology/terraform/

*.tfstate игнорировать файлы с расширением .tfstate
*.tfstate.* игнорировать файлы, имеющие в названии *.tfstate.*, например repo.tfstate.log
crash.log игнорировать этот файл
crash.*.log игнорировать файлы начинающиейся на crash. с расширениями .log
*.tfvars игнорировать файлы с расширением .tfvars
override.tf игнорировать этот файл
override.tf.json игнорировать этот файл
*_override.tf игнорировать файлы с расширением .tf, имена файлов которых заканчиваются на _override
*_override.tf.json игнорировать файлы с расширением .json, имена файлов которых заканчиваются на _override.tf
.terraformrc игнорировать этот файл
terraform.rc игнорировать этот файл
new line
