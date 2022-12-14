# Инструкция для работы с Git и удалёнными           репозиториями

## Что такое Git?
**Git** - это одна из *реализаций* распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
Подготовка репозитория
***Для создание*** репозитория необходимо выполнить команду git init  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

**Git add**
Для добавления измений в коммит используется команда git add. Чтобы использовать команду git add напишите git add <имя файла>

> Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда git status. Для этого необходимо в папке с репозиторием написать **git status**, и Вы увидите были ли измения в файлах, или их не было.

>Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду git commit. Выполняется она так: ***git commit -m "<сообщение к коммиту>.*** Все файлы для коммита должны быть ДОБАВЛЕНЫ и сообщение к коммиту писать ОБЯЗАТЕЛЬНО.

Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда git checkout. Используется она в папке с пепозиторием следующим образом: git checkout <номер коммита>

Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда git log. Для этого достаточно выполнить команду git log в папке с репозиторием

## Ветки в Git

**Создание ветки**

1. Для того, чтобы создать ветку, используется команда git branch. Делается это следующим образом в папке с репозиторием: git branch <название новой ветки>

Слияние веток

2. Для того чтобы дабавить ветку в текущую ветку используется команда git merge <name branch>

3. Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"






# **Спасибо за уделенное время.** 
![Картинка](data:image/jpeg;base64,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)

## Списки

1. список
2. список
3. список

* список
* список
* список

# git pull
Эта команда позволяет **скачать* все из текущего репозитория и автоматически сделать merge с нашей версией

# git push
При первом её использовании нужна авторизация.
Эта команда позволяет *отправить нашу версию репозитория на внешний репозиторий*. **ТРЕБУЕТ АВТОРИЗАЦИИ** на внешнем репозитории.

# Как настроить совместную работу

>1. Создать аккаунт на GitHub.com
>2. Создать локальный репозиторий
>3. “Подружить” ваш локальный и удалённый репозитории. 
    
**GitHub** при создании нового репозитория подскажет, как это можно сделать
    
>4. Отправить **(push)** ваш локальный репозиторий в удалённый (на **GitHub**), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории
>5. Провести изменения “с удаленного репозитория”
>6. Выкачать **(pull)** актуальное состояние из удалённого репозитория

### pull request

- команда для предложения изменений 

- запрос на вливание изменений в репозиторий

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изменения на ***GitHub*** нужно в отдельной ветке. 
Сначала пользователь копирует репозиторий на свой компьютер, делает **fork** репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на **GitHub** и даёт команду *pull request*.
    
    **Как сделать pull request (по шагам)**:

- Делаем fork (ответвление) репозитория
- Делаем git clone СВОЕЙ версии репозитория
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request
