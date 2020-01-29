# Vedomost

Однажды меня попросил один парень с ИВТ за короткий срок написать сайт напоминающий по функционалу электронную ведомость, куда преподователи ставят оценки. Требование было соблюдении 1-ой и 2-ой нормальных форм в БД, а также операции для выставления оценок студентам за экзмены в зависимости от допуска и групппы. Была просьба код писать по проще, поэтому работы над ошибками здесь немного. 

Так уж вышло, что [проект на Symfony][NewsCrudPanel] был написан раньше, поэтому черпал вдохновение оттуда и из [первого сайта][FirstSite].

## Установка
<details>
    <summary>Инструкция</summary>
 
1. Проверить настройки сервера. Для Apache OpenServer могут быть такими

```
<VirtualHost *:%httpport%>

    DocumentRoot    "%hostdir%"
    ServerName      "%host%"
    ServerAlias     "%host%" %aliases%
    ScriptAlias     /cgi-bin/ "%hostdir%/cgi-bin/"

</VirtualHost>
```

2. Проверить данные для подключения к БД в файле db/Db.php с 7 строки идёт массив с параметрами
3. Импортировать sql dump из db/univer.sql
</details>

## Демо

<details>
    <summary>Демо работы</summary>
 
 ![work demo][WorkDemo]
</details>

<details>
    <summary>Демо страниц ошибок и прочего</summary>
 
 ![error demo][ErrorDemo]
</details>

<details>
    <summary>Демо адаптивности макета</summary>
 
 ![adaptive demo][AdaptiveDemo]
</details>

<details>
    <summary>Скриншоты</summary>
 
 ![screen 1][Screen1]
 ![screen 2][Screen2]
 ![screen 3][Screen3]
 ![screen 4][Screen4]
 ![screen 5][Screen5]
 ![screen 6][Screen6]
 ![screen 7][Screen7]
 ![screen 8][Screen8]
 ![screen 9][Screen9]
 ![screen 10][Screen10]
</details>

## [Список всех моих проектов][ListAllMyProject]


[NewsCrudPanel]:<https://github.com/iebrosalin/public_web/tree/backend/symphony/news_crud_panel>
[FirstSite]:<https://github.com/iebrosalin/public_web/tree/backend/pure_php/first_site>


[ListAllMyProject]:<https://github.com/iebrosalin/all_public_projects>

[WorkDemo]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/gif/work_demo.gif>
[ErrorDemo]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/gif/error_demo.gif>
[AdaptiveDemo]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/gif/adaptive_demo.gif>



[Screen1]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/1.png>
[Screen2]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/2.png>
[Screen3]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/3.png>
[Screen4]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/4.png>
[Screen5]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/5.png>
[Screen6]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/6.png>
[Screen7]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/7.png>
[Screen8]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/8.png>
[Screen9]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/9.png>
[Screen10]:<https://github.com/iebrosalin/public_web/blob/backend/pure_php/vedomost/descriptions/screens/10.png>
