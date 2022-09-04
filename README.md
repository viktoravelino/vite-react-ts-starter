# [Vite](https://vitejs.dev/) + [React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/) Starter

### Description

This project is a code template starter using Vite, React and TypeScript.

The template uses eslint and prettier to enforce coding style and best practices. Also, [Husky](https://typicode.github.io/husky/#/) with [lint-staged](https://github.com/okonet/lint-staged) is configured to run prettier and eslint before every commit, ensuring the code follows standards.

#### This setup the includes:

- [husky](https://typicode.github.io/husky/#/), [lint-staged](https://github.com/okonet/lint-staged)
- [eslint](https://eslint.org/), [typescript-eslint](https://typescript-eslint.io/), [eslint-airbnb-config](https://github.com/airbnb/javascript), [prettier](https://prettier.io/)

## Use the template

-> To copy this template run the code below

```bash
npx degit viktoravelino/vite-react-ts-starter your-project-name
```

###### This will use the [degit package](https://www.npmjs.com/package/degit) to grab this repository for your own use. If you wish to make your own version of this configuration, please fork this repo.

-> Navigate to the new folder

```bash
cd your-project-name
```

-> Initialize git inside the project **(this has to be done before installing the dependencies to initialize husky correctly)**

```bash
git init
```

-> Install the dependencies

```bash
yarn
```

or

```bash
npm install
```

-> Run development server

```bash
yarn dev
```

or

```bash
npm run dev
```
