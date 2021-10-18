# Система контроля версий Git и GitHub

## Что такое Git?
Git - одна из распределенных систем контроля версий. Позволяет управлять версионностью файлов, откатываться до версий, создавать ветки и их сливать.
## Подготовка репозитория

**Реозиторий** = Это хранилище файлов, поддерживающих версионность.
Создать репозиторий можно с помощью команды *git init*, примененной в папке с будующим репозиторием.
Для добавления версионности к фалу используется команда *git add <имя файла>*.

## Создание "сохранений 
Для создания "сохранения" необходимо выполнить фиксацию, она же коммит. Это можно сделать с помощью команды *git commit* следующим образом: *git commit -m "<Сообщение>"* Сообщение к коммиту писать **Обязательно**.
Для всех измененных файлов необходимо использовать *git add* или использовать ключ "-a" при коммите.

## Журнал изменений

## Перемещение между сохранениями 
 Перемещаться на тот или иной коммит мы можем с помощью команды *git checkout*. Для этого нужно написать *git checkout <номер коммита из истории>*. Для возврата к самому последнием коммиту нужно написать *git checkout <Название ветки>*. по умолчанию ветка *master*.

 Отменять изменения можно с помощью команд *git revert* и *git reset*. Для этого нужно написать команду *git revert(reset) <номер коммита>* Комнада git revert перейдет к указанному коммиту, создав новый коммит. А Git reset перейдет к указанному состоянию и затрет историю изменений.


## Ветки в git

## Скачивание удаленного репозитория
Скачивание удаленного репозитория происходит  с поисковые команды "git clone". Они применяется в удобной вам папке и пишется *git clone*<адресс репозитория>. после чего в вашей папке создастся папка, название которой точно совпадает с названием репозитория, а ее содержимым является содержимое репозитория.
