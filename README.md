GIT Task 1

Все шаги сценария выполняйте в терминале GitBush, Terminal, в папке под гитом.

Как отправить ДЗ на проверку.
 1. Создайте текстоовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash

Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.

JSON
 4. Создать внешний репозиторий c названием JSON. - done
 5. Клонировать репозиторий JSON на локальный компьютер. – git clone https://github.com/SergeiPrenko/JSON.git
 6. Внутри локального JSON создать файл “new.json”. – cat > new.json
 7. Добавить файл под гит. – git add new.json
 8. Закоммитить файл. – git commit –m “Json file”
 9. Отправить файл на внешний GitHub репозиторий. – git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. – vim new.json
{
"Surname"    : "Prenko",
"Name"       : "Sergei",
"Patronymic" : "Viktorovich",
"Pets"       : 0,
"Salary"     : 700
}


 11. Отправить изменения на внешний репозиторий. - git add new.json, git commit –m “add info to new.json”, git push
 12. Создать файл preferences.json cat > preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

Vim preferences.json
{
"Favorite film"   : ["Inception", "Independens day", "Green book"],
"Favorite series" : "Sherlock",
"Favorite food"   : "Pasta",
"Favorite season" : "Summer",
"Side"        : "Light"
}

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON – cat > skils.json
vim skils.json
{
    "Subject1" : "Terminal Linux",
    "Subject2" : "SQL",
    "Subject3" : "Git",
    "Subject4" : "Postman",
    "Subject5" : "Client-server architecture",
    "Subject6" : "Mobile testing"
}

 15. Отправить сразу 2 файла на внешний репозиторий. - git add preferences.json skils.json, git commit –m “2 new files”, git push
 16. На веб интерфейсе создать файл bug_report.json. - +
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - +

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. – 
{
  "id"    : 1001,
  "heder" : "heder",
  "environment" : "environment",
  "severity" : "high",
  "status" : "status",
  "author" : "author",
  "steps reproduce" : "steps reproduce",
  "result" : "result",
  "expected result" : "expected result",
  "additions" : "additions"
 }

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - +
 20. Синхронизировать внешний и локальный репозиторий JSON – git pull


XML
 21. Создать внешний репозиторий c названием XML. - +
 22. Клонировать репозиторий XML на локальный компьютер. – git clone 
 23. Внутри локального XML создать файл “new.xml”. – cat > new.xml
 24. Добавить файл под гит. – git add new.xml
 25. Закоммитить файл. - git commit –m “new.xml”
 26. Отправить файл на внешний GitHub репозиторий. – git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. – 
vim new.xml
<?xml version="1.0"?>
<User>
	<name>Sergei<name>
	<surname>Prenko<surname>
	<patronymic>Viktorovich<patronymic>
	<age>35<age>
	<pets>0<pets>
	<salery>700<salery>
<User>

 28. Отправить изменения на внешний репозиторий. – git add new.xml, git commit –m “add info to new.xml”, git push
 29. Создать файл preferences.xml - cat > preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. - vim preferences.xml
<user>
	<favoriteFilm> inception <favoriteFilm>
	<fovoriteSeries> sherlok <favoriteSeries>
	<favoriteFood> Pasta <favoriteFood>
	<favoriteSeason> Summer <favoriteSeason>
	<side> Light <side>
<user>

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML - cat > skils.xml
{
    "Subject1" : "Terminal Linux",
    "Subject2" : "SQL",
    "Subject3" : "Git",
    "Subject4" : "Postman",
    "Subject5" : "Client-server architecture",
    "Subject6" : "Mobile testing"
}


 32. Сделать коммит в одну строку. - git add skils.xml preferences.xml && git commit -m "two new files"

 33. Отправить сразу 2 файла на внешний репозиторий. – git push
 34. На веб интерфейсе создать файл bug_report.xml. - +
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - +
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. - +
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - +
 38. Синхронизировать внешний и локальный репозиторий XML – git pull
