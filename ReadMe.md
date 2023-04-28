# Основы работы с GIT репозитариями

GIT это терминальное приложение для разных разработчиков, оно нужно для версионирования и совместной работы с другими людьми.
Перед началом работы с GIT его нужно установить на ваш компьютер. Информация есть в интернет.

## Инициализация и авторизация

Перед началом работы необходимо создать папку для проекта и инициализировать в ней, с помощью терминала GIT, набрав в терминале **git init**. Для первого раза необходимо представится, ввести свое имя и пароль. Для этого необходимо ввести сначала комманду **git config --global user.name ''ваше имя''**, а потом **git config --global user.email ''ваша почта''**. В дальнейшем на том же компьютере это делать не обязательно, если конечно он только ваш.

## Добавление документов в репозирарий

После создания документа в инициализированном репозитарии необходимо начинать его отслеживать - его изменения и, возможно варианты редактирования. Для добавления воспользуетесь командой **git add ''name.type''** или **git add .** в первом случае добавится только один файл, причем надо обязательно указать тип файла, во втором добавится все, что есть в репозитарии.

## Команда commit 

Создание конфликта

## Команды log и status

## Переходы между коммитами

## Ветвление, работа с ветками