# Инструкция по работе с git

## Инициализация репозитория

Для инициализации репозитория в текущей директории нужно ввести команду
```
git init
```

## Добавление файлов в коммит

Для добавления файлов в коммит нужно ввести команду
```
git add "Имя файла"
```

## Проверка версии git

Для проверки установленной версии git нужно ввести оманду
```
git version
```

## Просмотр истории изменений (Журнал изменений)

Для просмотра изменений в файле нужно ввести команду
```
git log
```

## Откат до нужной версии файла (Нужного коммита)

Для отката до нужной версии файла необходимо ввести команду
```
git checkout "номер коммита без ковычек"
```

## Создание новой ветки

Для создания новой ветки, введите команду:
```
git branche "Название ветки" без ковычек
```

## Перенос информации из ветки в ветку

Для переноса информации из ветки в ветку, введите команды:
```
git merge "Название ветки" без ковычек, из которой переносится информация
```
## Просмотр местонахождения (на какой ветки сейчас)

Для просмотра местонахождения, введите коменду:
```
git branch
```

## Удаление ненужной ветки

Для удаления ненужной ветки, введите команду:
```
git branch -d "Название ветки" без ковычек
```

## Просмотр лога комита

Для просмотра лога комита, введите команду:
```
git log --graph --all
```

## Переход из одной ветки в другую

Для перехода из одной ветки в другую, введите команду:
```
git checkout "Название ветки" без ковычек
```

## Клонирование репозитария

Для клонирования репозитария, введите команду:
```
git clone "repository_url"

```

## Обновление текущей ветки

Для обновления теущей ветки, введите команду:
```
git pull
```

## Отправка изменений в удаленный репозиторий

Для отправки текущей ветки в удаленный репозиторий, введите команду
```
git push
```

## Просмотр лога репозитория 

Введите команду:
```
git log --graph --all
```
