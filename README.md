# TXT
 1. Создать внешний репозиторий c названием TXT.  
  `Github - Repositories - New - Repository name: TXT - поставить галочку у Add Readme file - Cteate repository`  
 2. Клонировать репозиторий TXT на локальный компьютер.  
 `git clone https://github.com/irinalwnk/TXT.git`  
 1. Внутри локального TXT создать файл “new.txt”.  
 `touch new.txt`  
 4. Добавить файл под гит.  
 `touch new.txt`  
 5. Закоммитить файл.  
 `git commit -m 'create new.txt'`  
 6. Отправить файл на внешний GitHub репозиторий.  
 `git push`  
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
 `vim new.txt`   
 Нажать "i" для ввода данных. 
 	`name: Leshenko Irina;`   
	`age: 31;`  
	`cats: 1;`  
	`expected salaty: 800$`  
Нажать "Esc" и ввести для выхода из редактора   
	`:wq`  
 8. Отправить изменения на внешний репозиторий.  
 `git add . ; git commit -am 'add information in to new.txt' ;git push`  
 9. Создать файл preferences.txt  
 `touch preferences.txt`
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.  
 `vim preferences.txt`  
 Нажать "i" для ввода данных.   
 `film: Lord of the rings;`  
`series: Friends;`  
`food: Orange;`  
`season: Spring;`  
`country to visit: Ireland`  
Нажать "Esc" и ввести для выхода из редактора  
`:wq` 
 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT  
 `vim skills.txt`  
 Нажать "i" для ввода данных. 
 ``` 
	Skill_1: QA Testing   
	Skill_2: Terminal   
	Skill_3: Postman    
	Skill_4: Jmeter   
	Skill_5: SQL    
	Skill_6: Android Studio    
```
Нажать "Esc" и ввести для выхода из редактора   
	`:wq`   
	
12. Сделать коммит в одну строку.  
 `git add . ; git commit -m 'add information in to the files'  `    
 
 13. Отправить сразу 2 файла на внешний репозиторий.  
 `git push`
 14. На веб интерфейсе создать файл bug_report.txt.  
 `File - Cteate New File - bug_report.txt`
 
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "Cteate New File - bug_report.txt" - Нажать "Commit new file"`
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.  
`Edit this file - внести информацию в файл`

В формате TXT:  

`Description: Не работает кнопка отправки заказа.`

`Steps to reproduce:`

`1.Открыть сайт *.`

`2. Нажать по ссылке *.`

`3. Пролистать до поля *.`

`4. Ввести значение в поле *.`

`5. Попытаться нажать кнопку отправки заказа.`

`ar: кнопка неактивна.`

`er: кнопка нажимается можно сделать заказ.`

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "add information" - Нажать "Commit new file"`  
 18. Синхронизировать внешний и локальный репозиторий TXT  
`git pull` 
