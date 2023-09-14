# Учусь оформлять Markdown файл!

## Для этого прохожу курс по Git, как ни с транно.

# Данный репозиторий носит исключительно ***учебный*** характер.

**В нем я чусь как:**
1. Инициализировать репозиторий
2. Сохранять файлы, подготавливать к сохранению
3. Коммитить
4. Смотреть историю коммитов
5. Связывать репозитории локальные и удаленные
6. Пушить

Вот вам [ссылка](https://github.com/IgnatyKhramtsov "Я ссылка)") на мой GitHub!

# А теперь добавим *mermaid*-схему

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
``` 

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  modified  -- "git add" --> staged;
  tracked/comitted -- "изменения" --> modified;
```

ВОТЬ








