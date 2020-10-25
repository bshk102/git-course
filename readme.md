#Git and Github Course for beginners
https://www.youtube.com/watch?v=zZBiln_2FhM

1. Создаём пустую папку с проектом
Инициализируем репозиторий при помощи git init

2. Узнать о состоянии проекта git status

3. Начать отслеживать изменения за файлом git add <file>
Отслеживать изменения за всеми фалами git add .

4. Перестать отслеживать файл git rm --cached <file>

5. Сделать коммит git commit -m "<commit>" (-m = message)

6. Создать файл .gitignore, в него записать названия файлов и папок, которые не надо отслеживать

7. Узнать, в какой ветке сейчас находишься git branch

8. Создать новую ветку git branch <branch>
Удалить ветку git branch -D <branch>
Переключиться на ветку git checkout <branch>

Создать новую ветку и сразу же на неё переключиться git checkout -b <branch>

9. Совместить ветки git merge <branch>

10. Посмотреть какой стоит юзернейм git config --global user.name
Поменять юзернейм git config --global user.name <name>

Посмотреть какая электронная почта git config --global user.email
Поменять почту git config --global user.email <email>

11. git remote add origin <url>
Связать проект с репозиторием на github
git push -u origin master
Залить на репозиторий

12. Залить изменения на сервер git push

13. Склонировать готовый проект с репозитория на комп git clone <url>

14. Забрать последние изменения с сервера git pull