# Конспект по гиту
## Важные команды
* _**git init**_ - команда по инициализации репозитория
* _**git commit**_ - команда сохраняющая изменение файла
* _**git add**_ - команда по добавлению файла 
* _**git diff**_ - просмотр изменений до commit
* _**git checkount**_ - команда для перехода к commit или ветке
+ _**git branch**_ - показывает имеющиеся ветки и позволяет создать новую ветку а так же если добавить -d то позволяет удалить ветку
* _**git merge**_ - позваляет провести слияние разных веток 
### Дополнительное изображение 
![ошибка файла](izobr.jpeg) 
## Начало работы 
1. Для начала работы необходимо сначала инициализировать git через комманду _**git init**_ 
2. после чего добавить файл через комманду _**git add**_
3. и создать первое сохранение через команду _**git commit**_ 
### Дополнительное руководство
так же если нужные команды из Markdown 
их можно прочитать [_*На этом сайте*_](https://gist.github.com/Jekins/2bf2d0638163f1294637#Parag )
# Добавил новую ветку 
Markdown поддерживает два стиля оформления ссылок:

Гиперссылка, с немедленным указанием адреса (внутритекстовая);
Гиперссылка, подобная сноске.
Подразумевается, что помимо URL-адреса существует еще текст ссылки.

Язык разметки Markdown поддерживает 2 стиля обозначения заголовков: подчеркивание и выделение символом («#»). Выделение заголовков с помощью подчеркивания производится знаками равенства («=») в случае, если заголовок первого уровня, и дефисами («-») в случае, если заголовок второго уровня.
## Добавил вторую ветку 
Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат).
## _*Добавил вторую конфликтную строчку*_
## _*Добавил конфликтную строчку*








# Работа с удаленым репозиторием 
* git clone - позволяет перенести удаленый репозиторий
*  1. git remote add origin
    2. git branch -M main
    3. git push -u origin mail
     три команды позволяющие перенести свой репозиторий на удаленный сервис р
* git push - позволяет отправить commit на удаленый репозиторий
* git pull - позволяет обновить файл commit 
 с удаленного репозитория но и так  же производит слияние веток с удаленного сервиса и репозитория на пк 


