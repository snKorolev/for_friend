# Шпаргалка по гиту

#### Команды

###### git statut 

посмотреть статус репозитория

###### git add 

git add <имя файла без взяких скобок и кавычек> - добавить файл для коммита

git add --all будут добавлены все файлы

###### git commit -m "текст комментария"

закоммитить

## Хэш

###### Ид коммита = хэш

Находится в каталоге HEAD. <br>
Можно просто писать HEAD вместо указания самого хэша.

## Попытка использовать Mermaid


HEAD -- это голова.
Коммит -- это всему голова.
Статусы файлов:


```mermaid
%% описание схемы
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
  A --> C;
  B --> D;
  C --> E;
```
