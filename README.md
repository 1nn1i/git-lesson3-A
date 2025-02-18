**git init** - Инициализация репозитория

**git add "file_name"** - Добавить файлу с названием file_name версионность

**git add .** - Добавить всем файлам в папке версионность

**git reset .** - Убрать у всех файлов в папке версионность

**git reset "file_name"** - Удалить у файла с названием file_name версионность

**git commit -m "commit_message"** - Упрощенный вариант ввода коммита 

**git commit** - Обычный вариант коммита

**git commit -am** - Если файл имеет состояние modified (т.е. был tracked ранее и мы его добавили с помощью git add), то можно пропустить этап с командой git add посредством использования данной команды

**git checkout "hash_namber"** - Переместить на коммит с хешем "hash_namber" (для того, чтобы вернуться git checkout master/main) 

**git diff** - Последние изменения (начиная от коммита)

## __Синтаксис языка Markdown__ ## 

**Жирный текст** - чтобы текст был жирным, поставить ** или__

*Курсивный текст* - чтобы текст был курсивом, поставь *или_

 ~~Зачеркнутый текст~~ - чтобы текст был зачеркнутым, поставь ~~ ~~ 

 ## Нумерованные Списки — обозначаются 
обычными цифрами 1, 2, 3

1 элемент списка

2 элемент списка

3 элемент списка

* Строка – ненумерованные списки, символ “*” в начале строки

= или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого 
(“=”) и второго (“-”) уровней

# Заголовок

======================================

--------------------------------------

![Картинка по ссылке](https://i.vimeocdn.com/video/432547040-54ee20f92eacbf809b266dd97a77af4999b3234d4c1b72ace8313a0e22bfad8b-d.jpg)

**_Homework2_** - Домашняя работа 2

**cd** - Переместиться внутрь папки

**mkdir** - Создать новую папку

**ls** - Просмотреть список файлов в папке

**new-item** - Создать новый файл

**git checkout branch_name** - Переместиться на ветку с названием branch_name

**git branch** - Проверить список существующих веток

**git branch branch_name** - Создать ветку с названием branch_name

**git checkout -b branch_name** - Создать ветку с названием branch_name и переместиться в неё

**git merge branch_name** - Слить в текущую ветку изменения из branch_name

**git branch -D branch_name** - Удалить еще не слитую ветку

**git branch -d branch_name** - Удалить уже слитую ветку

**git commit -am "merge conflict resolve"** - Выполнить комит после разрешения конфликта

**git clone <url-адрес репозитория>** – клонирование внешнего репозитория на локальный ПК

**git pull** – получение изменений и слияние с локальной версией

**git push** – отправляет локальную версию репозитория на внешний

![scrin](C:\Users\Ara\Desktop\Anna_gitLesson3\git-lesson3-A\2023-10-19_10-54-51.png)
