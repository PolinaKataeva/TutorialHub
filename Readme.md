# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория 
Для создания репозитория необходимо выполнить команду "git init" в папке с репозиторием и у вас создастся репозиторий (появится скрытая папка .git)

### Git add
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория 
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и вы увидите были ли изменения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit". Выполняется она так: *git commit -m"<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Журнал изменений 
Для того, чтобы посмотреть все сделенные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется комманда *git checkout". Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*.

## Ветки в Git

## Создание ветки

Для того, чтобы создать ветку, испоьзуется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*.

## Слияние веток

Для того, чтобы добавить ветку в текущую ветку испльзуется команда *git branch <name branch>*.
