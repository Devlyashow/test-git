1. git status
2. git add [file] [file] [file] | если хотим добавить все файлы, то пишем: git add . - добавляет файлы в stage  (промежуточная область)
3. git commit -m "comment" 
4. git log посмотреть подробную запись изменения | git log --oneline - краткая запись о коммитах
5. git push [rep_link] [branch_name] - отправить изменения на удаленный репозиторий

get remote -v - узнаем ссылку и ее название
git push origin - Название ссылки можно вставлять вместо самой ссылки
git branch - узнаем название ветки (master)
то есть, чтоб добавить на гитхаб файлы, нужно прописать:
git push origin master

git branch [название новой ветки] - создать новую ветку
git checkout [название ветки] - переключиться на другую ветку
git branch -d [название ветки] - удалить ветку с локального репозитория

Перенос кода из ветки в ветку через терминал:
1. Переключаемся на ветку, в которую надо перенести код
2. git merge [название ветки, чей код хотим перенести]
3. Пушим дополненную ветку на github, т.к. изменения были проделаны локально
4. Удалить ветку на github и удалить ветку локально (локально - git branch -d [название ветки])


Дополнительные команды

1. git reset [file] - убирает файл, добавленный в stage (промежуточная область перед сохранением)
2. git diff - просмотр тех строк, которые изменяли или добавляли/удаляли
3. git reset --hard - уберет все изменения и вернет изменения, которые были до этого и очещает статус
