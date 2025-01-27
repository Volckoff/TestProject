## Инициализация репозитория



git init (от англ. «инициализировать») — инициализируй репозиторий.<br>

____

## Подготовка файла к коммиту



*git add todo.txt* (от англ.  «добавить») — подготовь файл todo.txt к коммиту; <br>

*git add --all* (от англ.  «добавить» +  «всё») — подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы; <br>

*git add .* — подготовь к коммиту текущую папку и все файлы в ней. <br>

____

## Создание коммита



*git commit -m "Комментарий к коммиту." * (от англ. commit, «совершать», «фиксировать», + «сообщение») — сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены. <br>

____

## Просмотр информации о коммитах



*git log* (от англ. , «журнал [записей]») — выведи подробную историю коммитов.<br>

____

## Просмотр состояния файлов



*git status* (от англ.  «статус», «состояние») — покажи текущее состояние репозитория. <br>


# Git Status


```mermaid
flowchart LR
A[untracked] --git add--> B[staged + tracked]
C[modified] --git add--> B
B --Изменения--> C
B --git commit--> D[tracked]
D -- Изменения--> C
```

