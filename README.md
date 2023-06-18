Використовуй цей
[шаблон React-проекту](https://github.com/goitacademy/react-homework-template#readme)
як стартову точку своєї програми.

# Критерії приймання

- Створений репозиторій `goit-react-hw-06-phonebook`
- При здачі домашньої роботи є посилання: на вихідні файли та робочу сторінку
  проекту на `GitHub Pages` або `Netlify`
- В Redux-стані зберігається мінімально необхідний набір даних
- Під час запуску коду завдання в консолі відсутні помилки та попередження.
- Для кожного компонента є окрема папка з файлом React-компонента та файлом
  стилів
- Для компонентів описані `propTypes`
- Використана бібліотека `Redux Toolkit`

## Книга контактів

Виконай рефакторинг коду застосунку «Книга контактів», додавши управління станом
за допомогою бібліотеки [Redux Toolkit](https://redux-toolkit.js.org/).

Нехай Redux-стан виглядає наступним чином.

```bash
{
  contacts: [],
  filter: ""
}
```

- Створи сховище з `configureStore()`
- Використовуй функцію `createSlice()`
- Створи дії збереження та видалення контакту, а також оновлення фільтра
- Зв'яжи React-компоненти з Redux-логікою за допомогою хуків бібліотеки
  [react-redux](https://react-redux.js.org/).
- Використай бібліотеку Redux Persist для збереження масиву контактів у
  локальному сховищі

---

npm install styled-components@5.3.10

import styled from 'styled-components';

---

npm i react-redux

import { Provider } from 'react-redux'

---

npm i redux-persist

import { PersistGate } from 'redux-persist/es/integration/react'

---

npm i @reduxjs/toolkit
