# create-typescript-app

Creates a starter app with configurations for

* [TypeScript](https://typescriptlang.org/)
* [Jest](https://jestjs.io/)
* Linting and formatting
  * [EditorConfig](https://editorconfig.org/)
  * [ESLint](https://eslint.org/)
  * [Prettier](https://prettier.io/)

The linting and formatting tools have been configured to  work together:

* `.editorconfig` has settings that feed into Prettier
* `.eslintrc.json` uses Prettier for formatting

The app is created with a number of package scripts for development. See
[typescript-starter-app
](https://github.com/subfuzion/typescript-starter-app#development)
for details.

## Using create-typescript-app

Enter:

```
npx github:subfuzion/create-typescript-app [path]
```

> Note:
> - If path isn't specified, it defaults to the current working directory (`.`).
> - The destination path must be empty. 

## Source

The source for the generated app is [typescript-starter-app](https://github.com/subfuzion/typescript-starter-app).

## License

Licensed under [MIT](./LICENSE).
