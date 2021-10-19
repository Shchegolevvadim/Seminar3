# Инструкция по работе с Git

## Что такое Git?
**Git - одна из реализаций распределнных систем контроля версий. Позволяет контролировать версионность файлов как локально, так и на удалённом сервере. Самая популярная система контроля версий

## Подготовка репозитория
**Репозиторий** - это хранилище файлов, поддерживающее версионность. Создать репозиторий в папке можно с помощью команды *git init*, приенив эту команду в папке с будущим репозиторием.
## Создание сохранений

## Создание "сохранений"
Создать "сохранения" они же фиксации или коммиты, мы можем с помощью команды *git commit*. Для этого необходимо написать команду *git commit -m <сообщение к коммиту>* сообщение к коммиту писать обязательно. Все файлы должны быть добавлены в коммит с помощью команды *git add*. Если файлы не добавлены, то можно использовать флаг *-а* и команда приобретёт вид *git commit -a -m "<сообщение к коммиту>*.

## Журнал изменений

## Перемещение между "сохранениями"
Для переключения между "сохранениями"(коммитами), необходимо использовать команду *git checkout* следующим образом: *git checkout <номер коммита для переключения>*. Номер икоммита берётся из истории коммитов и на него произойдёт переключение.

Команды *git reset* и *git revert* позволяет отменять изменения. Команда *git revert* возвращает к указанному коммиту, создавая новый коммит, а команда *git reset* возвращает к указанному коммиту и затирает историю изменений до указанного каммита. Применяется это следующим образом: *git revert <номер коммита>* или *git reset --hard <номер коммита>*

## Ветки в Git

## Слияние веток и решение конфликтов

## Удаление веток
Для того чтобы удалить уже слитую ветку используется команда git branch -d <имя ветки>

## Скачивание удаленного репозитория

## Отправка изменений в удаленный репозиторий



