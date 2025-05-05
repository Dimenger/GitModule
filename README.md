# GitModule

GitModule

1. git init --- Если создаёте новый проект с нуля и хотите начать работу с контролем версий прямо здесь и сейчас.
2. git clone url --- Если вам нужен доступ к существующему проекту на сервере (например, к репозиторию на GitHub).
   2.1. cd yourdir --- переход в нужную директорию.
3. ls -a --- отобразает все файлы.
4. git remote -v --- отображает привязку к репозиторию.
5. git remote add origin url --- привязывает папку с компа к папке репозитория если еще не привязана, работает в связке с git init

$ git config user.name
Dmitry Seregin
$ git config user.email
dimenerDS@gmail.com

6. git status
7. git add . --- все файлы (git add index.css) добавляет файлы в stage
8. git commit -m "fdafoafopafpas"
9. git log / git log --oneline
10. git push [rep_link] [branch_name]
