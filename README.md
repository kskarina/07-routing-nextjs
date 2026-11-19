# 07-routing-nextjs

NoteHub — застосунок для створення та перегляду нотаток на Next.js (App Router).

**Демо:** https://07-routing-nextjs-dusky-tau.vercel.app/

## Можливості

- Фільтрація нотаток за тегами (`/notes/filter/all`, `/notes/filter/Work` тощо)
- Бічна панель з тегами (паралельний маршрут `@sidebar`)
- Перегляд нотатки в модальному вікні (паралельний маршрут `@modal` + intercepting route)
- Пошук, пагінація, створення та видалення нотаток
- Сторінка 404

## Технології

Next.js, TypeScript, TanStack Query, Axios, Formik, Yup, CSS Modules

## Запуск

1. Створіть файл `.env.local`:

   ```
   NEXT_PUBLIC_NOTEHUB_TOKEN=ваш_токен
   ```

2. Встановіть залежності та запустіть:

   ```bash
   npm install
   npm run dev
   ```
