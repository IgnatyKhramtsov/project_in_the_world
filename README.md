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

# А теперь добавим *mermaid*-схему статусов файлов

```mermaid
flowchart LR

U(Untracked) -->|git add| S(Staged)
S -->|git restore --staged <file> or <.>| U
S -->|git restore --staged <file> or <.>| M
M(Modified) -->|git add| S
S -->|изменения| M
S -->|git commit| T(Tracked)
T -->|изменения| M
```

# Как откатиться назад если всё сломалось

Лекго и просто, вам всего лишь нужно ...

```mermaid
flowchart LR
S(Staged) -->|git restore --staged <file> or <.>| U(Untracked)
S -->|git restore --staged <file> or <.>| M(Modified)
U -->|git add| S
M -->|git add| S
```

А так работает **git reset --hard <commit hash>**

```mermaid
flowchart LR
H(HEAD) --> C1[COM1] --> C2[COM2] --> C3[COM3]
title
```








