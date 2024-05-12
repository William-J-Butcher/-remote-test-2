# remote-test-1
Задание №1 (Тайминг 15 минут)
📌 Создайте удалённый репозиторий remote-test-1 с файлом README.md

📌 Склонируйте его на свой рабочий стол командой git clone

📌 Посмотрите связи с удалённым репозиторием командой git remote -v

📌 Создайте новый пустой удалённый репозиторий remote-test-2

📌 Удалите связь с текущим репозиторием: git remote remove origin

📌 Подключите свой локальный репозиторий к новому удалённому:
git remote add origin path

📌 Отправьте изменения в новый удалённый репозиторий:
git push -u origin master



Задание №2 (Тайминг 15 минут)
Работа с удалёнными репозиториями

📌 Создаём связь с исходным репозиторием: git remote add source path

📌 Просматриваем связи и убеждаемся, что все установились: git remote -v

📌 Вносим изменения в локальный код и отправляем в оба репозитория:

git push -u origin master
git push -u source master

📌 Просматриваем изменения в удалённых репозиториях

📌 Вносим в удалённых репозиториях изменения в разные файлы

📌 Затягиваем изменения: git fetch --all

📌 Просматриваем их:

git log origin/master ^master
git log source/master ^master

📌 Вливаем их:

git merge origin/master
git merge source/master


Задание №3 (Тайминг 15 минут)

📌 Удалите связь с репозиторием source: git remote remove source

📌 Создайте ветку в локальном репозитории: git checkout -b 24-issue

📌 Создайте в интерфейсе GitHub такую же ветку в удалённом репозитории

📌 Внесите изменения в один из файлов в локальном репозитории и в какой-нибудь
другой файл в удалённом репозитории (origin) в этих ветках

📌 Выполните команду git push -u origin 24-issue

📌 Ознакомьтесь с возникшей ошибкой, выполните git pull 24-issue

📌 Сохраните сообщение коммита и выйдите из редактора Vim (<ESC> + :wq)

📌 Убедитесь, что автоматическое слияние произошло: git status

📌 Отправьте изменения в удалённый репозиторий

📌 Просмотрите изменения в удалённом репозитории
