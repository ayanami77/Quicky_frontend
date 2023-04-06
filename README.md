# Simple Memo (ver1.2)

You can check out the app on [github pages](https://seiya-tagami.github.io/Simple-Memo/)!

## Preview
### pc layout (light theme)

<img src="https://user-images.githubusercontent.com/107479598/230277754-545249c9-bfd7-440d-9e40-f8084e0b7622.png"/>

### mobile layout (dark theme)

<img src="https://user-images.githubusercontent.com/107479598/230278520-f92cc6ff-f46d-4298-8c25-04cb2ce52a5d.png" height="600"/>

1. [About](#About)
1. [Getting started](#Getting%20started)
1. [Languages and Tools](#Languages%20and%20Tools)
1. [Dev history](#Dev%20history)
1. [License](#License)

## About

Simple memo makes your life better, more intuitive and productive.  
With Simple Memo, you can create, update, read and delete a memo (what is called "CRUD" Operations).  
Also, this product has a no database and instead, I use a localStorage to accumulate memo data.

## Getting started

```
npm install
```

```
npm run dev
```

## Languages and Tools

This product uses the following things:

- Vue.js
- TypeScript
- Pinia
- Tailwind CSS
- Vite
- Font Awesome
- flaticon

## Dev history

- **version1.0, released on 2023/03/30**  
  In the first version, I built basic functions of Simple Memo, such as CRUD Operations. Also, it does not connect to any Databases and instead, I used the localStorage.

- **version1.1, released on 2023/04/04**  
  In the version 1.1, I improved whole of the application UI, but specifically, I worked hard to review MemoItem's UI and made it better. Also, I introduced "dark-theme-mode", which would let your experience more exciting!

- **version1.2, released on 2023/04/06**  
  In the version1.2, I introduced Pinia, which is a store library for Vue and made the code clear. Also, I conducted code refactoring.

## License

[MIT](https://choosealicense.com/licenses/mit/)
