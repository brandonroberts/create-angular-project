# create-angular

## Scaffolding Your First Angular Project

With NPM:

```bash
$ npm create ng@latest
```

With Yarn:

```bash
$ yarn create ng
```

With PNPM:

```bash
$ pnpm create ng
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold an Angular, run:

```bash
# npm 6.x
npm create ng@latest my-angular-app --template angular-v14

# npm 7+, extra double-dash is needed:
npm create ng@latest my-angular-app -- --template angular-v14

# yarn
yarn create ng my-angular-app --template angular-v14

# pnpm
pnpm create ng my-angular-app --template angular-v14
```

Currently supported template presets include:

- `angular-v14`
- `angular-v14-standalone`

You can use `.` for the project name to scaffold in the current directory.

## Credits

This project is inspired by `create-vite`.