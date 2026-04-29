# Словарь: ИИ · Код · Вайбкодинг

Живой сайт: [ai-coding-digital-terms.netlify.app](https://ai-coding-digital-terms.netlify.app/)

## Файлы

- `index.html` — сам сайт словаря (его публикует Netlify)
- `словарь.md` — те же термины в виде markdown-документа

## Как добавить новый термин

1. Открыть `index.html` в редакторе
2. Найти массив `const T = [` и добавить новый объект:
   ```js
   {t:'Название', c:'env',
    d:'Определение простыми словами.',
    e:'Пример из жизни.'},
   ```
3. Категории (`c`): `ai`, `agents`, `code`, `env`, `deploy`, `product`, `vibe`, `claude`
4. Сохранить, сделать commit и push — Netlify обновит сайт автоматически

