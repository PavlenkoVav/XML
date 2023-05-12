XML
 21. Создать внешний репозиторий c названием XML.
 22. Клонировать репозиторий XML на локальный компьютер.
 23. Внутри локального XML создать файл “new.xml”. touch new.xml
 24. Добавить файл под гит.  git add . 
 25. Закоммитить файл. git commit -a ( i +  comment +esc :wq + enter )
 26. Отправить файл на внешний GitHub репозиторий. git push 
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. : cat > new.xml
<secondname> Pavlenko </secondname>
<name> Valeriia </firstname>
<lastname> Igorevna </lastname>
<age> 24 </age>
<countofpets> 0 </countofpets>
<salary> 500$ </salary>
Ctrl C


 28. Отправить изменения на внешний репозиторий. git commit -a (i + comment + esc +:wq + enter ) + git push 
 29. Создать файл preferences.xml : touch preferences.xml 
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. cat > preferences.xml 
<movie> Hannibal </movie> 
<food> eggs </food>
<country> Norway </country>
Ctrl C

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML cat > skills.xml 
<first> Test Documentation </first>
<second> API </second>
<third> SQL </third>
Ctrl C

 32. Сделать коммит в одну строку. git add && git commit (i + comment + esc +:wq + enter ) 

 33. Отправить сразу 2 файла на внешний репозиторий. git push 
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML git pull
