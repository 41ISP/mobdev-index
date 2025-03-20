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

[Интерактивный тренажер по Git](https://ohmygit.org/)

### 2. Терминал

[Интерактивный тренажер по Unix терминалу](https://www.terminaltutor.com/) [en]

или

[Бесплатный курс по терминалу](https://ru.hexlet.io/courses/cli-basics) [ru]

### 3. Введение в верстку

#### 4. HTML

[HTML Academy #1](https://htmlacademy.ru/courses/297/)

[HTML Academy #2](https://htmlacademy.ru/courses/299)

[Лабораторная работа #1](https://github.com/31ISP/mobdev3-lab1)

⬇ Мы здесь

[Лабораторная работа #2](https://github.com/31ISP/mobdev3-lab2)

[CSS Diner (CSS селекторы)](https://flukeout.github.io/)

[Лабораторная работа #3](https://github.com/31ISP/mobdev3-lab3)

### 3. Основы CSS

#### Flexbox

- [Flexbox Froggy](https://flexboxfroggy.com)

- [Лабораторная работа №4](https://github.com/31isp/mobdev3-lab4)

#### Grid

- [Grid Garden](https://cssgridgarden.com/#ru)

⬇ Мы здесь

- [Лабораторная работа №5](https://github.com/31isp/mobdev3-lab5)

- [Лабораторная работа №6](https://github.com/31isp/mobdev3-lab6)

## Как выполнять задания

В каждом репозитории описано как выполнять задание. В случае, если не указано, то работать по следующему принципу:

### Как начать выполнять

1. Создайте fork репозитория в организации [31ISP](https://github.com/31ISP) под названием `mobdev3-lab{N}-{фамилия}`
    - `N` - номер лабораторной работы

2. Переключитель на ветку `dev` или `wip` (левый-верхний угол)

3. Запустите Codespace (Code => Codespace)

_Либо запускайте сразу на нужной ветке, либо переключайтесь в терминале кодспейса_

### Как сохранять работу

Для отправки ветки `dev` или `wip` на репозиторий GitHub необходимо:

- Добавить все измененные файлы в следующий коммит `git add .`

_Обратите внимание, что `.` это текущая папка. Соответственно, если вы находитесь в какой-либо папке внутри репозитория, то будут добавлены изменения только из папки_

- Создайте коммит `git commit -m "{Что делали}"`

_В кавычках постарайтесь описать что вы делали в текущем коммите, особенно если работа у вас заняла больше 1 коммита_

- Отправить коммит на GitHub `git push -u origin dev`

_Обратите внимание на последнее слово - это название вашей ветки_

### Как сдавать

При успешном выполнении задания:

- Делайте коммит
- Захостите работу с помощью [Github Pages](#как-хостить-работу)
- Добавляйте [pull request](#как-делать-pull-request) из `dev` или `wip` в `main` в **вашем репозитории**
- Указывайте меня ([ktkv419](https://github.com/ktkv419)) как reviewer

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

3. Перепроверье, что изменения сливаются из ветки `dev` или `wip` (справа) в ветку `main` (слева) и создайте новый PR

<p align="center">
    <img src="./.repo/images/pr-3.png" width="80%" />
    <img src="./.repo/images/pr-4.png" width="80%" />
</p>

В случае успешной сдачи работы вы увидите мои комментарии по поводу работы, оценку и что реквест был слит с веткой main

### Как хостить работу

_Обратите внимание, что это делается в **вашем** репозитории, где вы работали_

1. Откройте настройки проекта и вкладку `Pages`

<p align="center">
    <img src="./.repo/images/host-1.png" width="80%" />
</p>

<p align="center">
    <img src="./.repo/images/host-2.png" width="80%" />
</p>

2. Укажите ветку в которой вы выполняли работу и нажмите сохранить

_чаще всего это либо `dev`, либо `wip`_

<p align="center">
    <img src="./.repo/images/host-3.png" width="80%" />
</p>

3. Удостоверьтесь, что работа была захосчена успешно

_об этом будет сигнализировать галочки у последнего коммита и в категории `Deployments`, также удостоверьтесь, что работа доступна по ссылке внутри деплоя `github-pages`_

<p align="center">
    <img src="./.repo/images/host-4.png" width="80%" />
</p>

<p align="center">
    <img src="./.repo/images/host-5.png" width="80%" />
</p>


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
