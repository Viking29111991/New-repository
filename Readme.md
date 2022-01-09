# Инструкция по работе с git 

## Что такое git?

Git - одна из реализаций распределенных систем контроля версий, имеющая как локальную версионность, так и версионность на сервере. Git является самой популярной системой котроля версий на сегодняшний день. 

## Подготовка репозитория

Для того, чтобы создать репозиторий в указанной папке используется команда "git init". Для этого достаточно написать команду "git init" в папке с будущем репозиторием.
## Создание "сохранений"

## Создание фиксаций

### Создание коммитов

Для создания новой фиксации необходимо использовать команду *git commit*. Используется она следующим образом: в папке с репозиторием пишется команда *git commit -m "<соббщение к коммиту>"*. Все файлы коммита должны быть предварительно добавлены с помощью команды *git add*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

### Добавление файла к коммиту
Для того, чтобы добавить файл к новому коммиту ("сохранение") необходимо использовать команду "git add"/ Используется она следующим образом: в папке с репозиторием пишем команду *git add <имя файла>*  
### Просмотр информации о изменениях

Для того, чтобы посмотреть информацию об изменениях, сделанных в текущей ветки, необходимо использовать команду *git status*. Для этого достаточно использовать *git status* в папке с репозиторием.   

## Перемещение между сохранениями 

## Журнал изменений

## Ветки в Git

Для того, чтобы посотреть информацию об изменениях, сделанных в текущей ветки, необходимо использовать команду *git status*. Для этого достаточно использовать *git status* в папке с репозиторием.   
## Слияние веток и разрешение конфликтов
Конфликты регулярно возникают при слиянии ветвей или при отправке чужого кода. Иногда конфликты исправляются автоматически, но обычно с этим приходится разбираться вручную — решать, какой код остается, а какой нужно удалить.
Чтобы слить ветки используется команда *git merge*.
## Удалеие веток
Чтобы удалить не нужную ветку вводится команда git branch -d name_branch.
