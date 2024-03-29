# Руководство по работе с GIT

## Инициализация нового репозитория

Для инициализации нового репозитория введите команду:
```
   git init
```

## Добавление файла в репозиторий

Для добавления файла в репозиторий введите команду:
```
   git add <имя_файла>
```

## Другие команды

Показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.):
```
   git status
```

Сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ):
```
   git diff
```

Убрать из индекса все добавленные в него изменения (в рабочей директории все изменения сохранятся), антипод git add:
```
   git reset
```

## Коммит версии

Для фиксации изменений введите команду:
```
   git commit -m <сообщение>
```
## Создание новой ветки

Для создания новой ветки введите команду:
```
   git branch <имя_ветки>
```

## Перенос основания ветки

Для переноса основания текущей ветки на последний комит другой ветки необходимо выполнить команду:
```
   git rebase <имя_ветки>
```

## Вливание одной ветки в другую

Чтобы влить одну из существующих веток в другую нужно выполнить команду
```
   git merge <имя_вливаемой_ветки>
```

## Клонирование репозитория

Чтобы клонировать на свой компьютер репозиторий с git-хостинга, нужно получить ссылку на данный репозиторий и выполнить команду:
```
   git clone <ссылка_на_репозиторий>
```

## Отправка изменений на git-хостинг

Для отправки текущей ветки ужно ввести команду:
```
   git push
```
   
## Очистка от незафиксированных изменений

Для отмены незафиксированных изменений в файлах проекта введите команду:
```
   git reset --hard
```
