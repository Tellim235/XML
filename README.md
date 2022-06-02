# XML
 21. Создать внешний репозиторий c названием XML.
>**https://github.com/Tellim235/XML**
 22. Клонировать репозиторий XML на локальный компьютер.
>**git clone https://github.com/Tellim235/XML**
 23. Внутри локального XML создать файл “new.xml”.
>**touch new.xml**
 24. Добавить файл под гит.
>**git add new.xml**
 25. Закоммитить файл.
>**git commit -m "add new.xml"**
 26. Отправить файл на внешний GitHub репозиторий.
>**git push**
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
>**vim new.xml**

>**i**
```XML
<About_Me>
   <Name>Kseniya</Name>  
   <Age>35</Age>  
   <Pets>1</Pets>  
   <Salary>300000</Salary>  
</About_Me>
```
>**Esc**

>**:wq**
 28. Отправить изменения на внешний репозиторий.
>**git add new.xml**

>**git commit -m "cange new.xml"**

>**git push**
 29. Создать файл preferences.xml
>**touch preferences.xml**
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
>**vim preferences.xml**

>**i**
```XML
<Preferences>
   <Film>Spider man</Film>  
   <Series>Friends</Series>  
   <Food>Meat</Food>  
   <Season>Summer</Season>
   <Counrty>Korea</Counrty>
</Preferences>
```
>**Esc**

>**:wq**
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
>**touch sklls.xml**

>**vim sklls.xml**

>**i**
```XML
<Preferences>
   <Base theory>1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.</Base theory>  
   <Client-Server>2. Что такое клиент-серверная архитектура.</Client-Server>  
   <HTTP methods>3. HTTP Методы запросов на сервер.</HTTP methods>  
   <HTTP codes>4. Коды ответов HTTP сервера.</HTTP codes>
   <HTTP structures>5. Структуры HTTP запросов и ответов.</HTTP structures>
   <JSON>6. Что такое JSON, XML. Их структура.</JSON>
   <API>7. Тестирование API через Postman (JS, автотесты API).</API>
   <Other_skills>и другие навыки</Other_skills>
</Preferences>  
```
>**Esc**

>**:wq**
 32. Сделать коммит в одну строку.
>**git add preferences.xml sklls.xml**

>**git commit -m "add preferences.xml sklls.xml"**
 33. Отправить сразу 2 файла на внешний репозиторий.
>**git push**
 34. На веб интерфейсе создать файл bug_report.xml.
>**Нажать Add file => Create new file , указываем имя файла bug_report.xml**
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>**В нижней части страницы нажимаем Commit new file**
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
>**Выбрать файл bug_report.xls и нажать "Edit this file"**
```XML
<Bug_report>
        <ID> "A1"</ID>
        <Title>Нажатие кнопки 'Поиск' на главной странице не предоставляет результат поиска</Title>
        <Steps>
                1. Зайти на главную страницу сайта (ссылка на сайт)
                2. Ввести текст поиска
		3. Нажать кнопку Поиск
        </Steps>
        <Enviroment>
                <OS>Windows 10 x64</OS>
                <Browser>Google Chrome v 100.0.4896.127</Browser>
        <Expected_result>Нажатие кнопки Поиск выдает результат поиска</Expected_result>
        <Actual_result>При нажатии кнопки Поиск ничего не происходит</Actual_result>
        <Severity>Critical</Severity>
        <Priority>High</Priority>
        <Status>Open</Status>
        <Attachments>ссылка на картинку или видео</Attachments>
</Bug_report>
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 >**В нижней части страницы нажать Commit changes**
 39. Синхронизировать внешний и локальный репозиторий XML
 >**git pull**
