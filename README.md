## slozno sosredotochitsya

```
"scripts": {
  "test": "echo 'Привет!'",
  "check": "prettier --check './src/**/*.{html,css,js}'",
  "format": "prettier --write './src/**/*.{html,css,js}'",
  "lint": "stylelint './src/**/*.css'",
  "lintfix": "stylelint './src/**/*.css' --fix",
  "checkAll": "npm run check && npm run lint",
  "fixAll": "npm run format && npm run lintfix"
}
```
