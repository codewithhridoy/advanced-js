> This repository combines all the best practises of Javascript & TypeScript with your desired configs which will make the development more easier.
> It's a monorepo managed by [TurboRepo by Vercel](https://turbo.build/repo).

## ♻️ Advanced JavaScript & TypeScript

| **Package**                                                                                         | **Documentation**                                     |
|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| 📦 [`@codewithhridoy/eslint-config`](https://npmjs.com/package/@codewithhridoy/eslint-config)       | [Documentation](/packages/eslint-config/README.md)    |
| 📦 [`@codewithhridoy/prettier-config`](https://npmjs.com/package/@codewithhridoy/prettier-config)   | [Documentation](/packages/prettier-config/README.md)  |
| 📦 [`@codewithhridoy/tailwind-browser`](https://npmjs.com/package/@codewithhridoy/tailwind-browser) | [Documentation](/packages/tailwind-browser/README.md) | |

> **Legend**:
> 📦: Package **|** 📝: Configuration file

---

## 📦 [`@codewithhridoy/eslint-config`](https://www.npmjs.com/package/@codewithhridoy/eslint-config)

### 📥 Installation

```bash
#If you use npm
npm install --save-dev @codewithhridoy/eslint-config

#If you use yarn
yarn add -D @codewithhridoy/eslint-config

#If you use pnpm (preferred)
pnpm add -D @codewithhridoy/eslint-config
```

### 🔩 Usage

```js
// .eslintrc.js
module.exports = {
  extends: ['@codewithhridoy/eslint-config'],
};
```

### ⚙️ Rules overview

<!--START_SECTION:eslint-config-->
| Rule                          | Style                                                                      | Type          | Documentation                                                              |
| ----------------------------- | -------------------------------------------------------------------------- | ------------- | -------------------------------------------------------------------------- |
| `linebreak-style`             | Unix                                                                       | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/linebreak-style)             |
| `prettier/prettier`           | Warn                                                                       | ⚠️ `Warning`  | External rule                                                              |
| `quotes`                      | Single                                                                     | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/quotes)                      |
| `semi`                        | Never                                                                      | ⚠️ `Warning`  | [Documentation](https://eslint.org/docs/rules/semi)                        |
| `newline-before-return`       | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/newline-before-return)       |
| `import/newline-after-import` | -                                                                          | 🚫 `Error`    | External rule                                                              |
| `comma-dangle`                | [Documentation](https://eslint.org/docs/rules/comma-dangle)                | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/comma-dangle)                |
| `no-eval`                     | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-eval)                     |
| `func-names`                  | As-needed                                                                  | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/func-names)                  |
| `camelcase`                   | [Documentation](https://eslint.org/docs/rules/camelcase)                   | ⚠️ `Warning`  | [Documentation](https://eslint.org/docs/rules/camelcase)                   |
| `no-unused-vars`              | [Documentation](https://eslint.org/docs/rules/no-unused-vars)              | ⚠️ `Warning`  | [Documentation](https://eslint.org/docs/rules/no-unused-vars)              |
| `import/order`                | -                                                                          | ⚠️ `Warning`  | External rule                                                              |
| `prefer-arrow-callback`       | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/prefer-arrow-callback)       |
| `block-spacing`               | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/block-spacing)               |
| `comma-spacing`               | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/comma-spacing)               |
| `keyword-spacing`             | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/keyword-spacing)             |
| `space-infix-ops`             | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/space-infix-ops)             |
| `space-unary-ops`             | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/space-unary-ops)             |
| `brace-style`                 | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/brace-style)                 |
| `object-curly-spacing`        | Always                                                                     | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/object-curly-spacing)        |
| `space-before-function-paren` | [Documentation](https://eslint.org/docs/rules/space-before-function-paren) | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/space-before-function-paren) |
| `space-in-parens`             | Never                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/space-in-parens)             |
| `array-bracket-spacing`       | Never                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/array-bracket-spacing)       |
| `template-curly-spacing`      | Never                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/template-curly-spacing)      |
| `computed-property-spacing`   | Never                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/computed-property-spacing)   |
| `no-use-before-define`        | [Documentation](https://eslint.org/docs/rules/no-use-before-define)        | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-use-before-define)        |
| `no-label-var`                | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-label-var)                |
| `no-undef`                    | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-undef)                    |
| `no-undefined`                | Off                                                                        | 💡 `Disabled` | [Documentation](https://eslint.org/docs/rules/no-undefined)                |
| `complexity`                  | 20                                                                         | ⚠️ `Warning`  | [Documentation](https://eslint.org/docs/rules/complexity)                  |
| `no-alert`                    | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-alert)                    |
| `require-await`               | Off                                                                        | 💡 `Disabled` | [Documentation](https://eslint.org/docs/rules/require-await)               |
| `yoda`                        | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/yoda)                        |
| `no-empty`                    | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-empty)                    |
| `no-extra-semi`               | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/no-extra-semi)               |
| `valid-typeof`                | [Documentation](https://eslint.org/docs/rules/valid-typeof)                | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/valid-typeof)                |
| `jsx-quotes`                  | Prefer-double                                                              | 💡 `Disabled` | [Documentation](https://eslint.org/docs/rules/jsx-quotes)                  |
| `unicode-bom`                 | Never                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/unicode-bom)                 |
| `no-process-env`              | Off                                                                        | 💡 `Disabled` | [Documentation](https://eslint.org/docs/rules/no-process-env)              |
| `no-process-exit`             | Off                                                                        | 💡 `Disabled` | [Documentation](https://eslint.org/docs/rules/no-process-exit)             |
| `global-require`              | Error                                                                      | 🚫 `Error`    | [Documentation](https://eslint.org/docs/rules/global-require)              |
<!--END_SECTION:eslint-config-->

---

## 📦 [`@codewithhridoy/prettier-config`](https://www.npmjs.com/package/@codewithhridoy/prettier-config)

### 📥 Installation

```bash
#If you use npm
npm install --save-dev @codewithhridoy/prettier-config

#If you use yarn
yarn add -D @codewithhridoy/prettier-config

#If you use pnpm (preferred)
pnpm add -D @codewithhridoy/prettier-config
```

### 🔩 Usage

```js
// .prettierrc.js
module.exports = {
  ...require('@codewithhridoy/prettier-config'),
};
```

```js
// prettier-config.js
import prettierConfig from "@codewithhridoy/prettier-config";

export default {
  ...prettierConfig,
};
```

```json
{
  "extends": "@codewithhridoy/prettier-config"
}
```

### ⚙️ Rules overview

<!--START_SECTION:prettier-config-->
| Rule                         | Style       | Documentation                                                                          |
| ---------------------------- | ----------- | -------------------------------------------------------------------------------------- |
| `arrowParens`                | `always`    | [Documentation](https://prettier.io/docs/en/options.html#arrow-parens)                 |
| `bracketSpacing`             | `true`      | [Documentation](https://prettier.io/docs/en/options.html#bracket-spacing)              |
| `embeddedLanguageFormatting` | `auto`      | [Documentation](https://prettier.io/docs/en/options.html#embedded-language-formatting) |
| `htmlWhitespaceSensitivity`  | `css`       | [Documentation](https://prettier.io/docs/en/options.html#html-whitespace-sensitivity)  |
| `jsxSingleQuote`             | `true`      | [Documentation](https://prettier.io/docs/en/options.html#jsx-single-quote)             |
| `printWidth`                 | `120`       | [Documentation](https://prettier.io/docs/en/options.html#print-width)                  |
| `proseWrap`                  | `preserve`  | [Documentation](https://prettier.io/docs/en/options.html#prose-wrap)                   |
| `quoteProps`                 | `as-needed` | [Documentation](https://prettier.io/docs/en/options.html#quote-props)                  |
| `requirePragma`              | `false`     | [Documentation](https://prettier.io/docs/en/options.html#require-pragma)               |
| `semi`                       | `false`     | [Documentation](https://prettier.io/docs/en/options.html#semi)                         |
| `singleQuote`                | `true`      | [Documentation](https://prettier.io/docs/en/options.html#single-quote)                 |
| `tabWidth`                   | `2`         | [Documentation](https://prettier.io/docs/en/options.html#tab-width)                    |
| `trailingComma`              | `es5`       | [Documentation](https://prettier.io/docs/en/options.html#trailing-comma)               |
| `useTabs`                    | `false`     | [Documentation](https://prettier.io/docs/en/options.html#use-tabs)                     |
<!--END_SECTION:prettier-config-->

<!--START_SECTION:tailwind-browser-->
<img width="170" height="170" style="float: left; margin: 0 10px 0 0; border-radius: 50%;" alt="Tailwindcss logo" src="https://raw.githubusercontent.com/IgorKowalczyk/is-browser/main/src/images/logo.svg">

# TailwindCSS `:browser`

Tailwind browser helps you to develop efficiently for cross-browser platform

[![GitHub License](https://img.shields.io/github/license/codewithhridoy/advanced-js?color=%2334D058&logo=github&style=flat-square&label=License)](https://github.com/codewithhridoy/advanced-js/blob/master/LICENSE)
[![NPM Version](https://img.shields.io/npm/v/codewithhridoy/advanced-js/latest.svg?logo=npm&logoColor=fff&style=flat-square&color=%2334D058)](https://npmjs.com/package/@codewithhridoy/tailwind-browser) [![NPM Downloads](https://img.shields.io/npm/dw/@codewithhridoy/tailwind-browser?logo=npm&logoColor=fff&style=flat-square&color=%2334D058&label=Downloads)](https://npmjs.com/package/@codewithhridoy/tailwind-browser)

---

## 📥 Installation

**Tailwind.css v3 or newer is required**.

```
#If you use npm
npm install --save-dev @codewithhridoy/tailwind-browser

#If you use yarn
yarn add -D @codewithhridoy/tailwind-browser

#If you use pnpm (preferred)
pnpm add -D @codewithhridoy/tailwind-browser
```

## 📦 Usage

Add to `plugins` in your **tailwind.config.js**:

```js
module.exports = {
 // ...
 plugins: [
  require("@codewithhridoy/tailwind-browser"),
  // ...other plugins.
 ],
};
```

Style your components using `{browser_name}:{class}`, e.g. `firefox:bg-red-100`, `chrome:bg-blue-100`, etc.

```jsx
<div className="firefox:bg-red-400 chrome:bg-blue-400 bg-yellow-400">
 <p>On firefox background should be red, on chrome should be blue and on other browsers it should be yellow</p>
</div>
```

## 🔐 Supported browsers

| Browser | Variant    | CSS Property                         | Example                 |
| ------- | ---------- | ------------------------------------ | ----------------------- |
| Firefox | `firefox:` | `-moz-appearance: none`              | `firefox:bg-yellow-400` |
| Chrome  | `chrome:`  | `background: -webkit-named-image(i)` | `chrome:bg-red-400`     |
| Safari  | `safari:`  | `-webkit-app-region: inherit`        | `safari:bg-blue-400`    |

## ⁉️ Issues

If you have any issues with the page please create [new issue here](https://github.com/codewithhridoy/advanced-js/issues)

## 📥 Pull Requests

When submitting a pull request:

- Clone the repo.
- Create a branch off of `master` and give it a meaningful name (e.g. `my-awesome-new-feature`).
- Open a [pull request](https://github.com/codewithhridoy/advanced-js/pulls) on [GitHub](https://github.com) and describe the feature or fix.

## 📋 License

This project is licensed under the MIT. See the [LICENSE](https://github.com/codewithhridoy/advanced-js/blob/master/LICENSE) file for details

<!--END_SECTION:tailwind-browser-->