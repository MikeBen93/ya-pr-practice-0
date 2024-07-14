# Основные команды git для старта работы в нём 

## Инициализация репозитория:

```bash git init``` (от англ. initialize, «инициализировать») — инициализируй репозиторий.

## Подготовка файла к коммиту

```bash git add todo.txt``` (от англ. add, «добавить») — подготовь файл todo.txt к коммиту;

```bash git add --all``` (от англ. add, «добавить» + all, «всё») — подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы;

```bash git add .``` — подготовь к коммиту текущую папку и все файлы в ней.

## Создание коммита

```bash git commit -m "Комментарий к коммиту."``` (от англ. commit, «совершать», «фиксировать» + message, «сообщение») — сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены. 

## Просмотр информации о коммитах

```bash git log``` (от англ. log, «журнал [записей]») — выведи подробную историю коммитов.

## Просмотр состояния файлов

```bash git status``` (от англ. status, «статус», «состояние») — покажи текущее состояние репозитория.