# @subfuzion/create-typescript-app

Get up and running with minimal boilerplate for writing, testing, linting, and
formatting TypeScript for Node.js app, and nothing else. There are no other
assumptions or opinions about what frameworks you need.

```
npx @subfuzion/create-typescript-app [path]
```

> **Note**
>
> - If `path` isn't specified, it defaults to the current working directory (`.`).
> - The directory under `path` must be empty. 

## Details

Configuration boilerplate for jump starting your app development includes:

* [TypeScript]
* [Jest]
* Linting and formatting
  * [EditorConfig]
  * [ESLint]
  * [Prettier]

The linting and formatting tools have been configured to  work together:

* `.editorconfig` has format settings that feed into Prettier
* `.eslintrc.json` uses Prettier for formatting

The generated app includes a number of package scripts for development, including:
- `dev` | `dev:notify`
- `build` | `build:watch`
- `test` | `test:watch`
- `lint` | `lint:fix`

It is also configured with a `pre-commit` hook using [Husky] and
[lint-staged].

## Notes

To use the latest published version, enter:

```
npx @subfuzion/create-typescript-app@latest [path]
```

If you want to use the latest version from the GitHub [repo], enter:

```
npx github:subfuzion/create-typescript-app [path]
```

> **WARNING**
>
> Currently under development. This implementation assumes:
> 
> 1. You're running the latest LTS version (or greater) of [Node.js]
>    (the current implementation might work with earlier versions, but this
     hasn't been verified).
> 2. `node` and `npm` (automatically installed with Node.js) are in the path.
> 3. `git` is in your path and [user.name] and [user.email] are already
>    configured.
> 4. Your system can run a `bash` script (for now).

## Source

The source for the generated app is in the [@subfuzion/typescript-starter-app]
repo.

## License

Licensed under [MIT].

[@subfuzion/typescript-starter-app]: https://github.com/subfuzion/typescript-starter-app/
[EditorConfig]: https://editorconfig.org/
[ESLint]: https://eslint.org/
[Husky]: https://typicode.github.io/husky/
[Jest]: https://jestjs.io/
[lint-staged]: https://github.com/okonet/lint-staged/
[MIT]: ./LICENSE
[Node.js]: https://nodejs.org/en/download/
[Prettier]: https://prettier.io/
[repo]: https://github.com/subfuzion/create-typescript-app/
[TypeScript]: https://typescriptlang.org/
[user.name]: https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git#setting-your-git-username-for-every-repository-on-your-computer/
[user.email]: https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address#setting-your-email-address-for-every-repository-on-your-computer/
