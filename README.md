# GitDemo
git help

git status - индексация изменений и файлы, которые не отслеживаются Git.

git commit -m “комментарий“

git checkout {COMMIT_ID} - просмотр определенного коммита

git checkout {master||main} - вернуться к основной ветке (последней версии проекта)

git revert {COMMIT_ID} - отменить коммит (отменяет изменения) → :we - выйти с gin редактора

git reset {COMMIT_ID} —hard - удалить все коммиты после указанного, вместе со всеми изменениями

git init

git add {file} - добавить файл в локальный гит

## Ветки

git branch {branch_name} - создать новую ветку

git checkout -b {branch_name} - создать ветку и перейти на неё

git checkout {branch_name} - перейти на ветку

git branch -a - вывести все ветки

git merge {branch_name} - объеденить текущую ветку с указанной

## Удаленный репозиторий

git remote add origin {repository_url} - подключение к репе

git remote - показывает что подключен к ремот репе

git push -u origin master - выгрузка на ремот репу ориджин файлов в мастер ветку

git clone {repo url} - клонировать репозиторий

git pull - скачать обновленные данные с репы
