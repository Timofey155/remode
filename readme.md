## Основы в Git

Git — это набор консольных утилит, которые отслеживают и фиксируют изменения в файлах.

Чтобы создать новый репозиторий, нам нужно открыть терминал, зайти в папку нашего проекта и выполнить команду ```git init```.

```git status``` — это команда, которая показывает информацию о текущем состоянии репозитория.

```git add```-это команда, которая даёт нам выбор фалов для сохранения проекта.

```git commit -m '......'``` -это команда после ввода которой идёт сохранение написаного выше.

Для просмотра все выполненных фиксаций можно воспользоваться историей коммитов - ```git log```


## *Переключение между ветками*

master — это активная ветка

```git checkout любое название``` чтобы переключиться на другие ветки.

чтобы слить вместе 2 и более веток нам надо написать ```git merge любое название```



 

## *работа с удаленными репозиториями*
1. Создать аккаунт на GitHub
2. Создать локальный репозиторий
3. Создать удфлённый репозиторий 
4. Связать локальный репозиторийй с удалйнным

Получить изменения из  удалённого репозиторил и выполнить слияние с локальной версией:

```
git pull 
```

```C#
while (n < 0)
{
 n++;
}
```

Отправить локальную версию репозитория на внешний `git push`

Для того, чтобы просмотреть список настроенных удалённых репозиториев, вы можете запустить команду `git remote`.
Она выведет названия доступных удалённых репозиториев.
Если вы клонировали репозиторий, то увидите как минимум `origin` — имя по умолчанию,
которое Git даёт серверу, с которого производилось клонирование.

Вы можете также указать ключ `-v`, чтобы просмотреть адреса для чтения и записи, привязанные к репозиторию.

Чтобы добавить удалённый репозиторий и дать ему имя (luboeimia), выполните команду `git remote add <luboeimia> <url>`



 


