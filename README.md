# Крадкое руководство по работе с Git & GitHUB

## Настройка git

git config  - -global user.name “user-name”
git config  - -global user.email “user-email”

## Просмотр конфига

git config --list

## Инициализация репозитория

git init

## Добавление файлов в репозиторий

git add file-name  
git add  --all  
git add .  
 
## Коммит изменений

git commit -s ‘description commit’

## Просмотр истории коммитов

git log           // вывод полного лога  
git log --oneline // вывод сокращенной записи  

## Генерация ssh ключа для github

ssh-keygen -t rsa -b 4096 -C 'email-address'

## Подключение удаленного репозитория

**git remote add origin git@github.com:%ИМЯАККАУНТА%/first-project.git**
**git remote -v // просмотр информации о удалённом репозитории**

## Запушить изменения в удаленный репозиторий

** git push -u origin master  // при первом push нужно указать флаг -u**  
**git push**  
