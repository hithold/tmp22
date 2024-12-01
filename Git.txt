`gir diff` - увидеть различия между added или commited и modified. 
`git - log` - посмотреть историю коммитов
`git - status` посмотреть статусы файлов в дирректории
`git branch` - показать текущую ветку
`git branch -a` показать все ветки
`git branch alter` - создать ответвление
`git checkout alter` - переключиться на ветку alter
`git checkout commit_id` - встать курсором на какой-то коммит
`git branch -d alter` - удалить ветку alter
`git checkout -b alter` - создать ответвление и сразу переключиться на него
`git checkout -- filename` - откатить изменения в отслеживаемом файле. Только если он ещё не добавлен с помощью add.
`git-rebase master` - находять на ветке dev, заново-ответвиться от изменённого master
если есть конфликт, исправляем файл в ручную, делаем add и rebase --continue
`git commit --amend -m "name"` - исправить имя комита
`git merge alter` - находясь на ветке master, добавить все комиты ветки dev поверх
`git stash` - взять всё что не сохраненно и заныкать, чтобы можно было сменить ветку
`git stash pop` - вернуть всё, что было сныкано


`git remote add name url` - добавить удалённый сервер, обычно используют имя origin
`git push origin master` - запушить на сервер ветку master
`git clone url` -  скопировать себе удалённый репозиторий
`git push` - запушить изменения на сервер( после add, commit)
`git fetch` - обновить информацию с удалённого сервера
`git rebase origin/master` - применить изменения с удалённого сервера
`git pull` - сделать fetch и merge
`git pull --rebase origin master` - сделать fetch и rebase
`git push -u origin master` - запушить, и связать локальный и удалённые репы

SSH-keygen
	
