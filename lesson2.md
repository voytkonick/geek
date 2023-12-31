## При работе с ветками в Git важно знать следующие вещи:

1. **Создание** ветки: Вы можете создать новую ветку с помощью команды
* _git branch <имя ветки>_
. Например,
_git branch feature_.

2. **Переключение** на другую ветку: Для переключения на другую ветку используйте команду
* _git checkout <имя ветки>_
. Например,
_git checkout feature_.

3. **Просмотр** существующих веток: Чтобы увидеть список всех существующих веток, выполните команду
* _git branch_.

![branch](image-6.png)

4. **Создание и переключение** на новую ветку: Если вы хотите создать новую ветку и сразу переключиться на нее, используйте команду
* _git checkout -b <имя ветки>_
. Например,
_git checkout -b feature_.

5. **Слияние** веток: Для слияния одной ветки с другой используйте команду
* _git merge <имя ветки>_
. Например,
_git merge feature_.

        Комментарий на случай конфликтов:

* **Красным** - принять текущее изменение
* **Желтым** - принять входящее изменение
* **Зеленым** - принять оба изменения
* **Голубым** - сравнить изменения
![merge conflict](image-7.png)

        В случае отсутствия конфликтов, слияние веток проходит так:

![merge no conflict](image-8.png)


6. **Удаление** ветки: Чтобы удалить ветку, используйте команду
* _git branch -d <имя ветки>_
. Например,
_git branch -d feature_