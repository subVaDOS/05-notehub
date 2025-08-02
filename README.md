# 📘 NoteHub App

Застосунок для зберігання, створення, видалення та пошуку нотатків з використанням **React**, **TypeScript**, **TanStack Query**, **Formik**, **Yup**, та **Axios**.

## 🔗 Демо

➡️ Демо-відео доступне у завданні (GoIT)

## 🧩 Стек технологій

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [TanStack Query (React Query)](https://tanstack.com/query/latest)
- [Axios](https://axios-http.com/)
- [Formik](https://formik.org/)
- [Yup](https://github.com/jquense/yup)
- [React Paginate](https://github.com/AdeleD/react-paginate)
- [use-debounce](https://www.npmjs.com/package/use-debounce)
- [createPortal (ReactDOM)](https://reactjs.org/docs/portals.html)

## 📦 Функціонал

- Перегляд списку нотатків (із пагінацією)
- Створення нової нотатки у модальному вікні
- Видалення нотатки
- Пошук нотаток по ключовому слову
- Валідація форми створення нотатки
- Візуальні повідомлення про помилки/статуси

## ⚙️ API

Використовується публічний бекенд від GoIT:

Структура:
src/
│

├── components/ # Всі UI-компоненти

│ ├── App/

│ ├── NoteList/

│ ├── NoteForm/

│ ├── Modal/

│ ├── Pagination/

│ └── SearchBox/

│

├── services/ # HTTP-запити до API
│ └── noteService.ts

│
├── types/ # Типізація
│ └── note.ts

│
├── styles/ # Стилі (із репозиторію GoIT)

│
└── main.tsx # Точка входу
