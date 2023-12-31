# Инструкция для работы с Git и удаленными репозиториями

## Что такое Git ?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Являются самой опулярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий. (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла›*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для• того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "имя файла"*

### Просмотр всех коммитов
Для того что бы посмотреть все созданые коммиты (сохранение) необхдимо выполнит команду *git log* напишите *git log*

### Переход на ранее созданный коммит
Для того что бы перейти на ранее созданый коммит (для его изменение или поправки) используем команду *git checkout*. Выполняется она так: *git checkout* <первый 4 символа уникального кода>. Что бы вернуться к основному коммиту нужна команда *git checkout master*.
# Конец. Спасибо за внимание !

git add - сохранение

## 2 Семинара

git status - показывает состояние репоз.
git branch - вывод всех веток
git - контроль версий 
git branch name - создать ветку

### Создание новой ветки
Для создания новой ветки используем команду *git branch <имя>*.

### Просмотр всех веток
Для просмотра всех веток созданых нами мы используем команду *git branch*, эта команда так же покажет на какой ветке мы сейчас, знаком "*".

### Переход на ранее созданную ветку
Для перехода на ранее созданную ветку нам понадобится ранее упомянутая команда *git checkout*. Выполняется она так: *git checkout<имя ветки>*.

### Слияние двух веток
Для слияния двух веток используется комманда *git merge*, она позволяет нам слить определенную ветку с той на которой мы сейчас находимся. Напишите: *git merge<имя ветки>*(которую хотим слить с той где находимся).

### Вывод коммитов с ветками
Для просмотра всех коммитов (сохранений) с видемостью всех ветвей используется команда *git log --graph*.
Эта команда позваляет нам увидеть где создавались и объединялись все ветви.

Локальный репозиторий
Удаленный репозиторий
