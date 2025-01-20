# Мобильная разработка

## Содержание

1. [Лидерборд](https://docs.google.com/spreadsheets/d/12JIfriB0FJvXmA1DgSoB2L9AfjjwFlfL/edit?gid=1477412952#gid=1477412952)
1. [Roadmap](#roadmap)
1. [Как выполнять задания](#как-выполнять-задания)
1. [Документация](#документация)
1. [Полезное](#полезное)

## Roadmap

Все, что находится выше `Мы здесь` должно быть у вас для успешного получения зачета

### 1. Git

[Презентация по Git](https://ktkv-presentations.github.io/algos-8/)

⬇ Мы здесь

[Интерактивный тренажер по Git](https://ohmygit.org/)

### 2. Терминал

[Интерактивный тренажер по Unix терминалу](https://www.terminaltutor.com/) [en]

или

[Бесплатный курс по терминалу](https://ru.hexlet.io/courses/cli-basics) [ru]

## Как выполнять задания

В каждом репозитории описано как выполнять задание. В случае, если не указано, то работать по следующему принципу:

> [!warning]
> Перед началом работы с git не забудьте заменить ключ `~/.ssh/id_ed25519` на ваш ключ

### Как начать выполнять

1. Создайте fork репозитория в организации [31ISR](https://github.com/31ISR) под названием `up09-lab{N}-{last_name}`
    - `N` - номер лабораторной работы
    - `last_name` - ваша фамилия
2. Склонируйте себе этот форк по протоколу SSH
    - `git clone {SSH_ПУТЬ_ДО_ВАШЕЙ_РЕПЫ}`
3. Переключитель на ветку `dev`
    - `git branch dev` - создать ветку (не надо писать, если ветка уже существует)
    - `git checkout dev` - переключиться на ветку `dev`
4. Выполняйте задания в ветке `dev`

### Как работать

_если на вашей машине нет вашей работы, то незабудьте склонировать репозиторий_

1. Если были изменения в репозитории, то нужно стянуть последние изменения `git pull`
2. Выполняйте задания в ветке `dev`
3. Для отправки ветки `dev` на репозиторий GitHub необходимо:
    - Создать коммит `git add .` и `git commit -m "{Что делали}"`
    - Отправить коммит на GitHub `git push -u origin dev`

### Как сдавать

При успешном выполнении задания:

-   Делайте коммит
-   Добавляйте [pull request](#как-делать-pull-request) из `dev` в `main` в **вашем репозитории**
-   Указывайте меня ([ktkv419](https://github.com/ktkv419)) как reviewer

При успешной сдаче задания pull request будет закрыт и последним сообщением перед закрытием реквеста будут написаны мои комментарии и оценка

### Как делать pull request

_Обратите внимание, что это делается в **вашем** репозитории, где вы работали_

1. Откройте вкладку Pull requests

<p align="center">
    <img src="./.repo/images/pr-1.png" width="80%" />
</p>

2. Создайте новый PR

<p align="center">
    <img src="./.repo/images/pr-2.png" width="80%" />
</p>

3. Перепроверье, что изменения сливаются из ветки `dev` (справа) в ветку `main` (слева) и создайте новый PR

<p align="center">
    <img src="./.repo/images/pr-3.png" width="80%" />
    <img src="./.repo/images/pr-4.png" width="80%" />
</p>

В случае успешной сдачи работы вы увидите мои комментарии по поводу работы, оценку и что реквест был слит с веткой main

## Установка ПО

### Через WinGet

`winget install python.python.3.12 git.git`

### Через бинарные файлы

-   [Git](https://git-scm.com/downloads)
-   [Python](https://www.python.org/downloads/)

## Документация

## Полезное

-   [Git шпаргалка](https://github.com/cyberspacedk/Git-commands)
-   [Как использовать SSH ключ на GitHub](https://docs.github.com/ru/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
