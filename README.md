# code-sample-description
This sample repo will show you how to easily do X with Nylas.

## Setup

### System dependencies

- Add System dependencies

### Gather environment variables

You'll need the following values from the Nylas Dashboard:

```text
ACCESS_TOKEN = ""
CLIENT_ID = ""
CLIENT_SECRET = ""
```

Add the above values to a `.env` file.

The `.env` file is added to `.gitignore`. Ensure to store these values securely.

### Install dependencies

[replace with install steps]
```bash
$ npm i
```

## Usage

The recommended way to use this sample is ...

You can also clone the repository ...

You'll find more detailed instructions ...

## Get support

If you found a bug or want to suggest a new [feature/use case/sample], please file an issue.

## Learn more

Visit our [Nylas documentation](https://developer.nylas.com/) to learn more.
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
