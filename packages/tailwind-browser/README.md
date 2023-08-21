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
