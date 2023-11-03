# Welcome to Snapgram! [Visit Snapgram](https://snapgram-sigma.vercel.app/)
Snapgram is a full-stack social media app, inspired by Instagram, with a responsive
UI for mobile and desktop. It utilizes a modern tech stack (React JS, Appwrite,
Tailwind CSS, and React Query) with TypeScript for code quality. The app includes
advanced features like complex routing, conditional rendering, and infinite scrolling.
Users can interact with posts through likes, saves, and content management,
providing a comprehensive social media experience. This project highlights my skills
in front-end and back-end development, UX design, and tech stack utilization.

## Screenshots

### Desktop Interface
![login](Screenshots/Desktop view/1.login.png)
![signup](Screenshots/Desktop view/2.signup.png)
![home](Screenshots/Desktop view/3.home.png)
![explore](Screenshots/Desktop view/4.explore.png)
![relatedposts](Screenshots/Desktop view/5.related posts.png)
![createpost](Screenshots/Desktop view/6.create post.png)

### Mobile Interface
![login](Screenshots/Mobile view/1.login.jpg)
![signup](Screenshots/Mobile view/2.signup.jpg)
![home](Screenshots/Mobile view/3.home.jpg)
![explore](Screenshots/Mobile view/4.explore.jpg)
![createpost](Screenshots/Mobile view/5.create post.PNG)


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
