# Самый краткий гайд по GIT

## Локальный GIT

1. Устанавливаем себе локальной GIT
* Linux: https://git-scm.com/download/linux
* Windows: https://git-scm.com/download/win

2. Создание локального репозитория

* Создаем папку проекта и инициализируем отслеживание:

```
mkdir new-project
cd new-project
git init

```

## Удаленный GIT

1. Создаем учетную запись, например, на GitHub: https://github.com/
2. Создаем новый репозиторий 
3. Связываем локальный GIT с удаленным репозиторием:

```
git remote add origin {Полный путь до удаленного репозитория}

```

## Основные команды GIT

* **git version**    - Номер версии
* **git status**     - Узнать статус, состояние 
* **git add --all**  - Добавить все файлы, подготовка к отправке

* **git commit -m 'Сообщение коммита'**  - Зафиксировать файлы (коммит)

* **git push -u origin master** - Отправить файлы в удаленный репозиторий (первая отправка)
* **git push** - Отправить файлы в удаленный репозиторий (последующие отправки)

