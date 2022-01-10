# Инструкция по работе с git и удаленными репозиториями

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
Для премещения между коммитами следует использовать команду *git checkout*. Используется она следующим образом в папке с репозиторием: *git checkout <номер коммита>*.
## Журнал изменений
Для просмотра изменений следует использовать команду *git log*. Для этого нужно в папке с репозиторием написать *git log*.
## Ветки в Git
### Создане веток в git
Для того, чтобы создать новую ветку следует использовать команду *git branch*. Используется она слудующим образом в папке с репозиторием *git branch* <название ветки>.
### Просмотр списка веток 
Для того, чтобы просмомтреть список веток следует использовать команду *git branch*. для этого в папке с репозиторием следует набрать команду *git branch*.
### Переход между ветками
Для того, чтобы перейти на другую ветку следует использовать команду *git checkout*. Используется она в папке с репозиторием следующим образом *git checkout <название ветки>*.

 
## Слияние веток и разрешение конфликтов
### Слияние веток
Для сшлияния веток следует исмпользовать команду *git merge*. Используется она следующим образом: для начала ***ОБЯЗАТЕЛЬНО*** перейти на ветку, куда мы сливаем изменения, после чего следует команда *git merge <название сливаемой ветки>*. Слияние может произойти автоматически, а может возникнуть конфликт. Про разрешение конфликтов смотри дальше.

## Удалеие веток
Чтобы удалить не нужную ветку вводится команда git branch -d name_branch.
