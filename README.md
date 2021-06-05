# Node CLI Template

Personal template repo for writing Node CLI programs with Typescript. Includes:

- [execa](https://github.com/sindresorhus/execa)
- [ink](https://github.com/vadimdemedes/ink)
- [meow](https://github.com/sindresorhus/meow)
- [ava](https://github.com/avajs/ava)
- [eslint-config-airbnb-typescript](https://github.com/iamturns/eslint-config-airbnb-typescript)
- [prettier](https://github.com/prettier/prettier)
- [import-sort](https://github.com/renke/import-sort)

## Usage

1. ["Use this template"](https://github.com/nictar/node-cli-template/generate) to generate a new GitHub repo based on this one
2. Clone the new repo
3. `yarn install`
4. Update the binary name field in `package.json` (or any other fields) to match the new project
5. `yarn build` to transpile TS code in `src/` to JS code in `dist/`
6. `yarn test` to lint all TS files in `src/` and to run tests in `tests/`

## Inspirations

- https://github.com/justinneff/typescript-cli-template
- https://github.com/sindresorhus/fast-cli
