<div align="center">

# Git Homework 2 "JSON"

</div>

 1.  Создать внешний репозиторий c названием JSON.  
 `https://github.com/mranolegprivate/JSON`
 
 2. Клонировать репозиторий JSON на локальный компьютер.  
 `git clone git@github.com:mranolegprivate/JSON.git `
 
 3. Внутри локального JSON создать файл “new.json”.  
 `touch new.json`
 
 4. Добавить файлы под гит.  
 `git add .`
 
 5. Закоммитить файл.  
 `git commit -m "json first commit"`
 
 6. Отправить файл на внешний GitHub репозиторий.  
 `git push`
 
 7. <b>Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.</b>  
  `vim new.json`
  
```json
{
  "name" : "An Oleg Romanovich",
  "age" : 35,
  "animals" : 2,
  "salary" : "5000$"
} 
```
 8. Отправить изменения на внешний репозиторий. 
 ` git push`
 
 9. Создать файл preferences.json  
 `touch preferences.json`
 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
 `vim preferences.json`  
 
 ```json
 {
   "favorite_movie": "Avatar",
   "favorite_series": "The Mandalorian",
   "favorite_food": "Sangepsal",
   "favorite_season": "summer",
   "country_to_travel": "Singapore"
 }
```
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.  
 `vim skills.json`
 ```json
   {
   "skills":[
   "Git Linux Terminal",
   "Testing Theory", 
   "Client server", 
   "SQL", 
   "Postman", 
   "Charles Fiddler Sniffing", 
   "Web Services",     
   "DevTools", 
   "Mobile Testing", 
   "Web Testing", 
   "Load testing"
   ]
 }
 ```
 
 12. Отправить сразу 2 файла на внешний репозиторий.  
 `git add .`
 `git commit -m "second commit json"`
 `git push`
 
 13. На веб интерфейсе создать файл bug_report.json. 
 ``
 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 ``
 
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 
 ``
 
 26. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 ``
 
 27. Синхронизировать внешний и локальный репозиторий JSON.  
 ``
