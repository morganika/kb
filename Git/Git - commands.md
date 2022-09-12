<h1>Git, основные команды</h1>
Инструкция по установке Git: https://git-scm.com/book/ru/v2/Введение-Установка-Git 
 
<h2>Помощь:</h2>
git help <команда> – выведет руководство команды <br>
git <команда> -h – выведет краткую инструкцию по использованию опций

 
 
<h2>Базовые операции git</h2>
git unit – создать пустой репозиторий (предварительно переходим в нужное место через консоль) <br>
git clone – создать копию удалённого репозитория<br>
git pull – выгрузить изменения с удалённого репозитория<br>
git status – статус проекта (видим какие файлы изменены)<br>
git add – добавить содержимое файла в индекс<br>
git add . – внести в индекс ВСЕ изменения<br>
git commit – добавить файл в репозиторий<br>
git commit -m «комментарий» – добавить файл в репозиторий вместе с комментарием<br>
git push – отправить изменения в удалённый репозиторий<br>
 

 
<h2>Показать изменения </h2>
git log – вывести информацию о коммитах (история коммитов; коммиты, изменившие отдельный файл; коммиты за определенный отрезок времени и т.д.)<br>
git diff – показать изменения, не внесенные в индекс<br>
git diff --cached – показать изменения, внесенные в индекс<br>
git show — показать изменения, внесенные отдельным коммитом<br>

 
 
<h2>Операции отмены </h2>
git rm – удалить одновременно из индекса и дерева проекта<br> 
git reset – сбросить весь индекс<br>
git reset <файл> – удалить из индекса конкретный файл<br>
git revert – Отменить некоторые существующие коммиты<br>


 
<h2> Получение изменений из удалённого репозитория — Fetch и Pull </h2>
git fetch – загрузить объекты из другого репозитория<br>
git fetch <название репозитория> <название ветки> – забрать изменения из определённого репозитория и определённой ветки<br>
git pull – выгрузить изменения с удалённого репозитория (Грубо говоря это git fetch + git merge)
 

 
<h2>Ветвление и слияние (Branching and Merging)</h2>
git branch – перечислить существующие ветки, отметив активную<br>
git branch new-branch – создать новую ветку new-branch<br>
git branch -D new-branch – удалить ветку<br>
git checkout – переключиться на другую ветку<br>
git merge <ветка2> – объединить текущую ветку и ветку 2<br>
git-rebase <ветка1> <ветка2> – берет коммиты из ветки 1 и накладывает их на последний коммит ветки 2<br>
git-rebase <ветка1> – накладывается активная в настоящий момент ветка<br>
git cherry-pick – перенос коммита в другую ветку<br>
<br>
<файл>.gitignore — игнорировать файл
 
 

<h2>Дополнительная информация:</h2>
https://learngitbranching.js.org/?locale=ru_RU - интерактивный учебник git в игровой форме<br>
https://git-scm.com/book/ru/v2 - приятный довольно подробный учебник<br>
https://git-scm.com/docs - документация 