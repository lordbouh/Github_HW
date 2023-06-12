# Github_HW  1

JSON  
 4. Создать внешний репозиторий c названием JSON.  
via UI Github.com -> create repository  

5. Клонировать репозиторий JSON на локальный компьютер.  
git clone  https://github.com/lordbouh/JSON.git    

6. Внутри локального JSON создать файл “new.json”.  
touch JSON/new.json  

7. Добавить файл под гит.  
 git add new.json  

8. Закоммитить файл.  
git commit -m "created file"  

9. Отправить файл на внешний GitHub репозиторий.  
git push

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
 cat > new.json  
{  
"name": "Pavel",  
"surname": "Turov",  
"age": 37,  
"count of pets": 0,  
"future desired salary": 2000  
}  

11. Отправить изменения на внешний репозиторий.  
git commit -m "changes"  
git push  

12. Создать файл preferences.json  
touch preferences.json  

13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
 cat > preferences.json  
{  
"favorite film": "Pirates of the Carribean sea",  
"favorite serial": "Beverly Hills 90210",  
"favorite food": "Healthy food",  
"favorite time of year": "Summer",  
"Country would like to visit": "United States of America"  
}  

14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
cat > skill.json  
{  
"skill_1": "Terminal knowledge",  
"skill_2": "Git",  
"skill_3": "SQL",  
"skill_4": "Postman",  
"skill_5": "Charles",  
"skill_6": "Fiddler",  
"skill_7": "Client-Server Architecture",  
"skill_8": "DevTools"  
}  

15. Отправить сразу 2 файла на внешний репозиторий.  
git add skill.json  
git add preferences.json  
git commit skill.json -m "created"  
git commit preferences.json -m "created"  
git push  
Enumerating objects: 7, done.  
Counting objects: 100% (7/7), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (6/6), done.  
Writing objects: 100% (6/6), 770 bytes | 770.00 KiB/s, done.  
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0  
remote: Resolving deltas: 100% (1/1), done.  
To https://github.com/lordbouh/JSON.git  
   e36c89e..1080958  main -> main  

16. На веб интерфейсе создать файл bug_report.json.  
done  

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
done  

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
-> edit  
{  
  "id": 1,  
  "severity": "low",  
  "title": "link [apply] doesn't send the form",  
  "STR": "1.Open link below the main page, 2. Fill in form data: Name, e-mail, 3.Click [Apply] button"  
  "ER": "Form sent",  
  "AR": "Nothing goes after click",  
  "Environment": "Windows 10 Pro, Google Chrome 114.0",  
  "Attachments": "Screencast_1",  
  "Comments": "Null"  
}  

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
comment "added bug_report # 1"  

20. Синхронизировать внешний и локальный репозиторий JSON  
git pull  

XML  
 21. Создать внешний репозиторий c названием XML.  
repositories -> new XML  
https://github.com/lordbouh/XML.git  

22. Клонировать репозиторий XML на локальный компьютер.  
git clone https://github.com/lordbouh/XML.git  

23. Внутри локального XML создать файл “new.xml”.  
touch new.xml  

24. Добавить файл под гит.  
git add new.xml  

25. Закоммитить файл.  
git commit -m "created new"  

26. Отправить файл на внешний GitHub репозиторий.  
git push
Enumerating objects: 3, done.  
Counting objects: 100% (3/3), done.  
Writing objects: 100% (3/3), 204 bytes | 204.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/lordbouh/XML.git  
\* [new branch]      main -> main  

27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
cat > new.xml  
\<?xml version="1.0" encoding="windows-1251"?>  
\<list>  
\<name>Pavel\</name>  
\<surname>Turov\</surname>  
\<age>37\</age>  
\<count_of_pets>0</count_of_pets>  
\<future_desired_salary>2000</future_desired_salary>  
\</list>  

28. Отправить изменения на внешний репозиторий.  
 git commit -am "created new"  
warning: in the working copy of 'new.xml', LF will be replaced by CRLF the next time Git touches it  
[main 8240b03] created new  
 1 file changed, 9 insertions(+)  
  
 git push  
Enumerating objects: 5, done.  
Counting objects: 100% (5/5), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (2/2), done.  
Writing objects: 100% (3/3), 472 bytes | 472.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/lordbouh/XML.git  
   0663b07..8240b03  main -> main  

29. Создать файл preferences.xml  
touch preferences.xml  

30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
\<?xml version="1.0" encoding="windows-1251"?>  
\<preferences>  
\<favorite_film>Pirates of the Carribean sea\</favorite_film>  
\<favorite_serial>Beverly Hills 90210\</favorite_serial>  
\<favorite_food>Healthy food\</favorite_food>  
\<favorite_time_of_year>Summer\</favorite_time_of_year>  
\<Country_would_like_to_visit>United States of America\</Country_would_like_to_visit>  
\</preferences>  

31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
\<?xml version="1.0" encoding="windows-1251"?>  
\<skills>  
\<skill_1>Terminal knowledge\</skill_1>  
\<skill_2>Git\</skill_2>  
\<skill_3>SQL\</skill_3>  
\<skill_4>Postman\</skill_4>  
\<skill_5>Charles\</skill_5>  
\<skill_6>Fiddler\</skill_6>  
\<skill_7>Client-Server Architecture\</skill_7>  
\<skill_8>DevTools\</skill_8>  
\</skills>  

32. Сделать коммит в одну строку.  
git commit -am "created"  

33. Отправить сразу 2 файла на внешний репозиторий.    
git add *  
git commit -m "created"  
git push  
Enumerating objects: 7, done.  
Counting objects: 100% (7/7), done.  
Delta compression using up to 4 threads  
Compressing objects: 100% (5/5), done.  
Writing objects: 100% (5/5), 694 bytes | 694.00 KiB/s, done.  
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0  
remote: Resolving deltas: 100% (1/1), completed with 1 local object.  
To https://github.com/lordbouh/XML.git  
8240b03..ba4e312  main -> main  

34. На веб интерфейсе создать файл bug_report.xml.  
create bug_report.xml  

35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
done  
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
\<?xml version="1.0" encoding="windows-1251"?>  
\<bug_report>  
\<id>\1</id>  
\<severity>low\</severity>  
\<title>link [apply] doesn't send the form\</title>  
\<STR>1.Open link below the main page, 2. Fill in form data: Name, e-mail, 3.Click [Apply] button\</STR>  
\<ER>Form sent\</ER>  
\<AR>Nothing goes after click\</AR>  
\<Environment>Windows 10 Pro, Google Chrome 114.0\</Environment>  
\<Attachments>Screencast_1\</Attachments>  
\<Comment>Null\</Comment>  
\</bug_report>  

37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
done  

38. Синхронизировать внешний и локальный репозиторий XML  
git pull  
