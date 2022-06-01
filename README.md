# TXTTXT
 1. Создать внешний репозиторий c названием TXT. create a new repository
 2. Клонировать репозиторий TXT на локальный компьютер. git clone git@github.com:valeriia888/TXT.git

 3. Внутри локального TXT создать файл “new.txt”. touch new.txt
 4. Добавить файл под гит.  git add new.txt
 5. Закоммитить файл. git commit -m "added new file in txt format"
 6. Отправить файл на внешний GitHub репозиторий. git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 cat >> new.txt
name: Lanchinskaia Valeriia
age: 25 years
number of pets: two
future desired salary: 2000$
good day!
ctrl+c

8. Отправить изменения на внешний репозиторий.git add new.txt && git commit && git push
 9. Создать файл preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
  cat >> preferences.txt
my favorite movie : The intern
    my favorite series: The friends
    my favorite season: autumn
    country I would like to visit: Norway
ctrl+c
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT touch sklls.txt && cat >> sklls.txt

Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC
 What is a client-server architecture
 HTTP Methods of requests to the server
 Structures of HTTP requests and responses
What is JSON, XML. Their structure
API testing via Postman (JS, API autotests)
Removing and reading logs from an external server
Sniffing http web traffic via Charles and Fiddler
Dev Tools of web browsers (Google Chrome, FireFox)
ctrl+c
 12. Сделать коммит в одну строку. git add preferences.txt sklls.txt && git commit -m "added information"
 13. Отправить сразу 2 файла на внешний репозиторий. git push

 14. На веб интерфейсе создать файл bug_report.txt. add file button
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. commite 
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.   edit
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. commite new file 
ID: 1
Reporter:Valeriia Lanchinskaia
Severity: tweak
Priority: normal
Status": accepted
Product Build: 2.1.1
Reproducibility: always
Platform: Google Chrome 91.0.4472.124
OS: Windows
OS Version: 10*64
Resolution: open
Summary: The 404 error is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer
Description: The 404 error is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer
Steps To Reproduce: 1. Open the site https://prom.ua/ua/ 
   2. Scroll down the page to the footer.
   3. Click the "Про prom.ua" link.
   4. Click the "Микола Палієнко" link.
   5. Pay attention to the 404 error
Actual result: The 404 error is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer
Expected result:: The information about selected person is displayed in the new browser tab after clicking on the "Микола Палієнко" link in the footer
Additional Information: Video https://drive.google.com/file/d/1SNhHpTTgxswxR6CtnqGxYQRTIJ0X0Waa/view?usp=drivesdk
Attached Files: https://drive.google.com/file/d/16rH-U0oI1kh_vhvnuM18WsmwPFCctaRx/view?usp=sharing"
 18. Синхронизировать внешний и локальный репозиторий TXT  git pull

