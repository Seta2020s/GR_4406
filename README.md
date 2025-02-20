# GR_4406
## Инструкция по работе с удаленными репозиториями

1. **git clone <URL>** : Клонирует удаленный репозиторий Git на локальную машину. Клонирование позволяет получить полную копию удаленного репозитория с историей коммитов и ветками.

2. **git push**: Отправляет коммиты из локального репозитория в удаленный репозиторий на GitHub. Это позволяет вам делиться своими изменениями с другими разработчиками.

3. **git pull**: Получает и объединяет изменения из удаленного репозитория в ваш локальный репозиторий. Используется, когда вы хотите обновить свою локальную версию проекта до последней версии на GitHub.

4. **git remote add <name> <URL>**: Добавляет удаленный репозиторий GitHub под указанным именем. Это позволяет вам связать ваш локальный репозиторий с удаленным репозиторием на GitHub.

5. **git remote -v**: Показывает список удаленных репозиториев, связанных с вашим локальным репозиторием. Вы можете видеть URL-адреса удаленных репозиториев и их имена.

6. **git push -u <remote> <branch>**: Устанавливает отслеживание для указанной ветки в удаленном репозитории. Это позволяет вам в дальнейшем использовать git push без указания удаленного репозитория и ветки

7. **git remote show <remote>**: Показывает дополнительную информацию о указанном удаленном репозитории, включая URL-адрес, отслеживаемые ветки и другие детали.

8. **git remote rename <old-name> <new-name>**: Переименовывает удаленный репозиторий с указанным старым именем на новое имя.

9. **git remote remove <name>**: Удаляет удаленный репозиторий с указанным именем из списка удаленных репозиториев

10. **git remote set-url <name> <new-url>**: Изменяет URL-адрес указанного удаленного репозитория.

11. **git fetch <remote>**: Получает все изменения с указанного удаленного репозитория без объединения с локальными изменениями. Эта команда обновляет информацию о ветках и коммитах в удаленном репозитории

12. **git pull <remote> <branch>**: Вытягивает изменения из указанной ветки удаленного репозитория и объединяет их с локальными изменениями. Это сочетание команд git fetch и git merge

13. **git push <remote> --delete <branch>**: Удаляет указанную удаленную ветку из удаленного репозитория.

14. **git push --tags**: Отправляет все теги (аннотированные и легковесные) в удаленный репозиторий.

15. **git remote prune <remote>**: Удаляет удаленные ветки из локального репозитория, которые были удалены в удаленном репозитории

16. **git submodule add <URL>**: Добавляет *подмодуль* из указанного URL-адреса в ваш репозиторий. Подмодули позволяют включать другие репозитории внутри вашего репозитория.

17. **git submodule init**: Инициализирует *подмодули* , указанные в вашем репозитории.

18. **git submodule update**: Обновляет *подмодули* в вашем репозитории до последних коммитов.