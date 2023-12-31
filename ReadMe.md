# Знакомство с GIT.

---

## Знакомтсво с командной строкой

### Список команд для перемещения

1. Команда pwd - позволяет вывести ваше текущее местоположение.
2. Команда cd - позволяет переместиться в указанную папку.
3. Команада ls - позволяет вывести содержимое текущей папки.

### Список команд для работы с файлами 

1. Команда touch - позволяет создать файл в текущей папке.
2. Команда mkdir - позволяеь создать папку в текущей папке.
3. Команда cp - позволяет скопировать файл.папку в указанное место.
4. Команда mv - позволяет переместить файл/папку в указанное место.
5. Команда cat - позволяет распечатать содержимое файла.
6. Команда rm - позволяет удалить файл.
7. Команда rmdir - позволяет удалить папку.
8. Команда rm -r - позволяет удалить папку со всем содержимым.

--- 

## Инициализация репозитория и создание коммитов

### Инициализация репозитория 

Инициализация репозитория производится с помощью команды git init.
git init выведет сообщение вида Initialized empty Git repository in <*ваша папка с проектом*>/.git/ (англ. «инициализирован пустой Git-репозиторий в <*ваша папка*>/.git/»). 
В подпапке .git Git будет хранить всю служебную информацию.

### Создание коммита.


Для проверки состояния репозитория используется команда git status.
Команда git status выведет:
*название текущей ветки: On branch master или On branch main;
*сообщение о том, что в репозитории ещё нет коммитов: No commits yet;
*сообщение, которое говорит: «чтобы что-нибудь закоммитить (то есть зафиксировать), нужно сначала это создать» — nothing to commit (create/copy files and use "git add" to track).

Для подготовки к сохранению используется команда git add.
Для подготовки к сохранению всех файлов репозитория команда git add используется с ключем --all.

Выполнение коммита производится с помощью команды git commit.
При необходимости добавить сообщение к коммиту нужно использовать ключ -m и набарть сообщение в ковычках после данного ключа.

Для просмотра истории коммитов используется команда git log.

---

## Создание связи между локадьным и удаленным репозиториями.

Для привязки локального репозитория с удаленным используется команда git remove add.
Команде необходимо передать два параметра: имя удалённого репозитория и его URL.
В качестве имени используйте слово origin.

Чтобы убедиться, что репозитории связаны используется команда git remove -v.

Отправка изменений на удаленный репозиторий производится с помощью git push после создания коммита. 
 
