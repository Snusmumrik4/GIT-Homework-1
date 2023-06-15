# GIT-Homework-1
JSON
 1. Создать внешний репозиторий c названием JSON
new repository
 2. Клонировать репозиторий JSON на локальный компьютер
git clone https://github.com/Snusmumrik4/JSON.git
 3. Внутри локального JSON создать файл “new.json”
touch new.json
 4. Добавить файл под гит
git add new.json
 5. Закоммитить файл
git commit -m "new"
 6. Отправить файл на внешний GitHub репозиторий
git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
vim new.json
 8. Отправить изменения на внешний репозиторий
git commit -am "change_new"
git push
 9. Создать файл preferences.json
touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON
vim preferences.json
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat >skills.json
 12. Отправить сразу 2 файла на внешний репозиторий
git add .
git commit -m "preferences"
git push
 13. На веб интерфейсе создать файл bug_report.json
add file / create new file bug_report.json
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
commit changes 
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
commit changes 
 20. Синхронизировать внешний и локальный репозиторий JSON
git pull
