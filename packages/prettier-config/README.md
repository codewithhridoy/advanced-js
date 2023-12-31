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