# GIT 

Task 2: XML
-

**1. Создать внешний репозиторий c названием XML:**
```bash
[Repositories] > [New] > [Create repository]
```
**2. Клонировать репозиторий XML на локальный компьютер:**
```bash
git clone "link"
```
**3. Внутри локального XML создать файл “new.xml”:**
```bash
cd xml
touch new.xml
```
**4. Добавить файл под гит:**
```bash
git add new.xml
```
**5. Закоммитить файл:**
```bash
git commit -m "new.xml"
```
**6. Отправить файл на внешний GitHub репозиторий:**
```bash
git push
```
**7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате xml:**
```bash
cat > new.xml
[Enter]
<?xml version="1.0" encoding="windows-1251"?>
<user>
    <name>Vladimir Semenovich</name>
    <age>39</age>
    <pets>1</pets>
    <salary>150000</salary>
</user>
[Enter]
[Ctrl + C]
```
**8. Отправить изменения на внешний репозиторий:**
```bash
git commit -am "edit new.xml"
git push
```
**9. Создать файл preferences.xml:**
```bash
touch preferences.xml
```
**10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате xml:**
```bash
cat > preferences.xml
[Enter]
<?xml version="1.0" encoding="windows-1251"?>
<preferences>
    <favoriteMovie>As Good as It Gets</favoriteMovie>
    <favoriteTVSeries>Friends</favoriteTVSeries>
    <favoriteFood>Barbecue</favoriteFood>
    <favoriteSeason>Spring</favoriteSeason>
    <dreamDestination>Argentina</dreamDestination>
</preferences>
[Enter]
[Ctrl + C]
```
**11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате xml:**
```bash
cat > sklls.xml
[Enter]
<?xml version="1.0" encoding="windows-1251"?>
<skills>
    <ol>
        <li>Postman</li>
        <li>Charles</li>
        <li>Fiddler</li>
        <li>DevTools</li>
        <li>Android studio</li>
        <li>ADB</li>
        <li>Terminal Linux</li>
        <li>SQL</li>
        <li>Postgres</li>
        <li>Redis</li>
        <li>Jmeter</li>
        <li>Python</li>
    </ol>
</skills>
[Enter]
[Ctrl + C]
```
**12. Отправить сразу 2 файла на внешний репозиторий:**
```bash
git add .
git commit -m "preferences.xml, sklls.xml"
git push
```
**13. На веб интерфейсе создать файл bug_report.xml:**
```bash
[Add file] > [Create new file]
```
**14. Сделать Commit changes (сохранить) изменения на веб интерфейсе:**
```bash
[Commit changes] > [Commit changes]
```
**15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате xml:**
```bash
[Edit this file]
<?xml version="1.0" encoding="windows-1251"?>
<bugReport>
 <number>DL_01</number>
 <title>White screen is displayed after tapping 'Free chest' icon in the store</title>
 <environment>Huawei P30 Pro, Android 10</environment>
 <precondition>The app is lounched</precondition>
 <inputs>Login 1 Pass 123</inputs>
 <STR>
   <ol>
    <li>Tap 'Store' icon</li>
    <li>Tap 'Free chest' icon</li>
   </ol> </STR>
  <ER>The screen with the number of diamonds received is opened</ER>
  <AR>White screen is displayed</AR>
  <severity>Major</severity>
  <priority>Medium</priority>
  <attachments>None</attachments> 
</bugReport>
```
**16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:**
```bash
[Commit changes] > [Commit changes]
```
**17. Синхронизировать внешний и локальный репозиторий xml:**
```bash
git fetch
git merge
```
```bash
git pull
```
---
