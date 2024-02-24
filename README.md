# npm-package-json-lint-config-package

Shareable [npm-package-json-lint](https://npmpackagejsonlint.org/) configuration for packages.

- [Source code](https://github.com/joaopalmeiro/npm-package-json-lint-config-package)
- [npm package](https://www.npmjs.com/package/npm-package-json-lint-config-package)
- [Licenses](https://licenses.dev/npm/npm-package-json-lint-config-package/0.0.0)

## Getting Started

### Installation

```bash
npm install --save-dev npm-package-json-lint-config-package
```

or

```bash
yarn add --dev npm-package-json-lint-config-package
```

or

```bash
pnpm add --save-dev npm-package-json-lint-config-package
```

or

```bash
bun add --dev npm-package-json-lint-config-package
```

### Usage

To use this configuration, choose one of the options below.

#### Edit the `package.json` file

```json
{
  "npmpackagejsonlint": {
    "extends": "npm-package-json-lint-config-package"
  }
}
```

#### Create a `.npmpackagejsonlintrc.json` file

```json
{
  "extends": "npm-package-json-lint-config-package"
}
```

Check the [npm-package-json-lint documentation](https://npmpackagejsonlint.org/docs/configuration#configuration-override) to learn how to override this configuration.

## Development

Install [fnm](https://github.com/Schniz/fnm) (if necessary).

```bash
fnm install && fnm use && node --version && npm --version
```

```bash
npm install
```

```bash
npm run lint
```

```bash
npm run format
```

## Deployment

```bash
npm pack --dry-run
```

```bash
npm version patch
```

```bash
npm version minor
```

```bash
npm version major
```

- Update the version in the `Licenses` link at the top.
- Commit and push changes.
- Create a tag on [GitHub Desktop](https://github.blog/2020-05-12-create-and-push-tags-in-the-latest-github-desktop-2-5-release/).
- Check [GitHub](https://github.com/joaopalmeiro/npm-package-json-lint-config-package/tags).

```bash
npm login
```

```bash
npm publish
```

- Check [npm](https://www.npmjs.com/package/npm-package-json-lint-config-package).
