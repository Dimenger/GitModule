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
   7.1. git reset --- убрать файл из stage
   7.2. git reset --hard --- все отменить, все вернуть
8. git commit -m "fdafoafopafpas"
9. git log / git log --oneline
10. git push [rep_link] [branch_name] --- git push origen main --- сохранит изменение в основную ветку.
11. q выход из log
12. git branch
13. git diff --- посмотреть измения git diff [имя файла]

Ветки Branches

main
develop
feature/main-page
feature/about us

1. git branch
2. git branch develop
3. git checkout develop --- переход на нужную ветку. далее все обновляем и сохраняем
   3.1. git checkout -b develop --- создает новую ветку и переходит на нее
4. git push origin develop --- сохранение ветки в GitHub
5. pull requests --- слияние веток через GitHub
6. git checkout main --- переходим на мастер
7. git pull origin main --- подгружаем изменения из Git Hub в код на ПК.
8. git branch -d develop --- удаление ветки через терминал.
9. git merge --- слияние через терминал. gпереходим на main потом git merge [branch name]

конфликты

1. git merge --- при слиянии будет выведено меню с подсказками и действиями что делать.

окончателное удаление
Посмотрите список удалённых веток, чтобы убедиться, что ваша ветка действительно существует на удаленном сервере:

1. git branch -r
   origin/develop
   origin/main

Это покажет вам, что ветка develop всё ещё присутствует на удалённом сервере.
Чтобы окончательно избавиться от неё, выполните команду удаления удалённой ветки: 2. git push origin --delete develop
