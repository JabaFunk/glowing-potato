# инструкция по командам гит

## git add

Команда **git add** добавляет содержимое рабочей директории в индекс (*staging area*) для последующего коммита. По умолчанию **git commit** использует лишь этот индекс, так что вы можете использовать **git add** для сборки слепка вашего следующего коммита.

## git status

Команда **git status** показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.

## git diff

Команда **git diff** используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей директорией и индексом (*собственно git diff*), разница между индексом и последним коммитом (*git diff --staged*), или между любыми двумя коммитами (*git diff master branchB*).

## git commit

Команда **git commit** берёт все данные, добавленные в индекс с помощью **git add**, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.

## git branch

Команда **git branch** — это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.

## git checkout

Команда **git checkout** используется для переключения веток и выгрузки их содержимого в рабочую директорию.

