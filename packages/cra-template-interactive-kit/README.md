# Interactive template

<p align="left">
  <a aria-label="ZEIT logo" href="https://github.com/koshelevsergey/cra-templates/releases">
    <img src="https://img.shields.io/badge/version-1.2.3-green?style=for-the-badge&logo=appveyor&labelColor=000000">
  </a>
  <a aria-label="ZEIT logo" href="https://nodejs.org">
    <img src="https://img.shields.io/badge/node->=%2010-green?style=for-the-badge&logo=Node.js&labelColor=000000">
  </a>
    <a aria-label="License" href="https://github.com/koshelevsergey/cra-templates/blob/master/packages/cra-template-interactive-kit/LICENSE.md">
    <img alt="" src="https://img.shields.io/npm/l/next.svg?style=for-the-badge&labelColor=000000">
  </a>
</p>

This is a basic template based on the official typescript template for **Create React App**.
Official template with typescript [cra-template-typescript](https://www.npmjs.com/package/cra-template-typescript).

The template itself includes 4 small additions:
- **TypeScript** - His key responsibility is to introduce strong typing into the project. [More details](https://www.typescriptlang.org);
- **ESLint** - Keeps your code clean and tidy. [More details](https://eslint.org);
- **Prettier** - Engaged in code formatting. [More details](https://prettier.io);
- **Environment** - Additional development environment files. [More details](https://create-react-app.dev/docs/adding-custom-environment-variables/).

All these add-ons are configured and do not require any changes. If you need to supplement them with your settings, you can do it without any problems.

This template is designed to facilitate the deployment of a new application. With the introduction of code formatting tools, cleanliness and rigorous.

## Installation

To use this template, add `--template interactive-kit` when creating a new app.

For example:

```sh
npx create-react-app my-app --template interactive-kit

# or

yarn create react-app my-app --template interactive-kit
```

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.


## Usage

**Recommendation for use.**

Unfortunately, it is not possible to make some dependencies in dev. Therefore, we recommend that after installing the application template, transfer some dependencies to dev by hand.

List of dependencies that need to be transferred from **dependencies** to **devDependencies** in *package.json* file:
- @testing-library/jest-dom
- @testing-library/react
- @testing-library/user-event
- @types/jest
- @typescript-eslint/eslint-plugin;
- @typescript-eslint/parser;
- eslint;
- eslint-config-prettier;
- eslint-plugin-prettier;
- prettier.

After, update the applications of one of the commands:

```sh
npm update

# or

yarn upgrade
```

## Support

For problems, you can contact the [issue](https://github.com/koshelevsergey/cra-templates/issues) section.
For a quick reply, please indicate the `label`.

## Contributing

If you want to contribute to the project, please read **README.md** or **CONTRIBUTING.md** on the [main page](https://github.com/koshelevsergey/cra-templates) of the repository.

## License

This project is licensed under the [licensed as MIT](https://github.com/koshelevsergey/cra-templates/blob/master/packages/cra-template-interactive-kit/LICENSE.md).