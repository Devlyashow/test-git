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