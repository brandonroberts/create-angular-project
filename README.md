# create-angular

## Scaffolding Your First Angular Project

With NPM:

```bash
$ npm create angular@latest
```

With Yarn:

```bash
$ yarn create angular
```

With PNPM:

```bash
$ pnpm create angular
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold an Angular, run:

```bash
# npm 6.x
npm create angular@latest my-angular-app --template angular-v14

# npm 7+, extra double-dash is needed:
npm create angular@latest my-angular-app -- --template angular-v14

# yarn
yarn create angular my-angular-app --template angular-v14

# pnpm
pnpm create angular my-angular-app --template angular-v14
```

Currently supported template presets include:

- `angular-v14`
- `angular-v14-standalone`

You can use `.` for the project name to scaffold in the current directory.

## Credits

This project is inspired by `create-vite`.