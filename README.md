<p align="center"><img src="https://cdn.jsdelivr.net/gh/tagproject/art/packages/sophty-ui/icons-shared-config/banner.svg" alt="Package logo"></p>

<p align="center">
    <a href="https://github.com/sophty-ui/icons-shared-config/actions"><img src="https://github.com/sophty-ui/icons-shared-config/actions/workflows/build.yml/badge.svg" alt="Build Status"></a>
    <a href="https://www.npmjs.com/package/@sophty-ui/icons-shared-config"><img alt="npm" src="https://img.shields.io/npm/v/@sophty-ui/icons-shared-config.svg"></a>
    <a href="https://github.com/keindev/standard-shared-config"><img src="https://img.shields.io/badge/standard--shared--config-+-green?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAfCAYAAACh+E5kAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAJQSURBVHgB1VftUcMwDFU4/tMNyAZ0A7IBbBA2CExAmIBjApcJChO0TFA2SJkgMIGRyDNV3TSt26RN353OX/LHUyTZIdoB1tqMZcaS0imBDzxkeWaJWR51SX0HrJ6pdsJyifpdb4loq3v9A+1CaBuWMR0Q502DzuJRFD34Y9z3DXIRNy/QPWKZY27COlM6BtZZHWMJ3CkVa28KZMTJkDpCVLOhs/oL2gMuEhYpxeenPPah9EdczLkvpwZgnQHWnlNLiNQGYiWx5gu6Ehz4m+WNN/2i9Yd75CJmeRDXogbIFxECrqQ2wIvlLBOXaViuYbGQNSQLFSGZyOnulb2wadaGnyoSSeC8GBJkNDf5kloESAhy2gFIIPG2+ufUMtivn/gAEi+Gy4u6FLxh/qer8/xbLq7QlNh6X4mbtr+A3pylDI0Lb43YrmLmXP5v3a4I4ABDRSI4xjB/ghveoj4BCVm37JQADhGDgOA+YJ48TSaoOwKpt27aOQG1WRES3La65WPU3dysTjE8de0Aj8SsKS5sdS9lqCeYI08bU6d8EALYS5OoDW4c3qi2gf7f+4yODfj2DIcqdVzYKnMtEUO7RP2gT/W1AImxXSC3i7R7rfRuMT5G2xzSYzaCDzOyyzDeuNHZx1a3fOdJJwh28fRwwT1QY6Xzf7TvWG6ob/BIGPQ59ymUngRyRn2El6Fy5T7G0zl+JmoC3KRQXyT1xpfiJKIeAemzqBl6U3V5ocZNf4hHg61u223wn4nOqF8IzvF9IxCMkyfQ+i/lnnhlmW6h9+Mqv1SmQhehji4JAAAAAElFTkSuQmCC" alt="Standard Shared Config"></a>
</p>

[Standard Shared Config](https://github.com/keindev/standard-shared-config) for [Sophty UI icons](https://github.com/sophty-ui/sophty-icons)

## Install

```console
npm install @sophty-ui/icons-shared-config --save-dev
```

## Usage

- Add `"prepare:config": "icons-shared-config"` to `scripts` property in your `package.json`
- Rename your `prepare` scripts to `prepare:[NAME]`
- Add `"prepare": "npm-run-all prepare:*"`
- Run `npm run prepare`

## Configs

## include shared configs:

- [@tagproject/docs-shared-config](https://www.npmjs.com/package/@tagproject/docs-shared-config): `1.x`
- [@tagproject/vscode-shared-config](https://www.npmjs.com/package/@tagproject/vscode-shared-config): `2.x`

### extract actions, hooks and configs:

- `.github/*`
- `.husky/*`
- `.eslintrc`
- `tsconfig.json`

### merge files:

- `.gitignore`
- `.npmignore`

### append to `package.json`:

#### scripts:

- `build` - build shared config
- `build:ts` - transpile `TS` files
- `build:generate` - generate Icon components from svg images
- `generate` - run all `generate:*`
- `generate:changelog` - generate changelog
- `generate:ghinfo` - generate `.ghinfo` file
- `lint` - run all linters
- `lint:eslint` - run `eslint` TS files linting
- `prepare` - run all prepare scripts
- `prepare:config` - rebuild local configs
- `prepare:husky` - install husky hooks
- `release` - build, lint, generate changelog and bump package version

#### dependencies:

- [@tagproject/docs-shared-config](https://www.npmjs.com/package/@tagproject/docs-shared-config): `1.x`
- [@tagproject/vscode-shared-config](https://www.npmjs.com/package/@tagproject/vscode-shared-config): `2.x`
- [@types/react](https://www.npmjs.com/package/@types/react): `18.x`
- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin): `5.x`
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser): `5.x`
- [changelog-guru](https://www.npmjs.com/package/changelog-guru): `latest`
- [eslint](https://www.npmjs.com/package/eslint): `8.x`
- [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier): `8.x`
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import): `2.x`
- [eslint-plugin-jest](https://www.npmjs.com/package/eslint-plugin-jest): `27.x`
- [eslint-plugin-node](https://www.npmjs.com/package/eslint-plugin-node): `11.x`
- [eslint-plugin-optimize-regex](https://www.npmjs.com/package/eslint-plugin-optimize-regex): `1.x`
- [eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react): `7.x`
- [eslint-plugin-react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks): `4.x`
- [ghinfo](https://www.npmjs.com/package/ghinfo): `latest`
- [husky](https://www.npmjs.com/package/husky): `8.x`
- [rimraf](https://www.npmjs.com/package/rimraf): `latest`
- [ts-node](https://www.npmjs.com/package/ts-node): `10.x`
- [typescript](https://www.npmjs.com/package/typescript): `4.x`

#### configure:

```json
{
  "type": "module",
  "peerDependencies": {
    "react": "18.x"
    "react-dom": "18.x"
  }
}
```
