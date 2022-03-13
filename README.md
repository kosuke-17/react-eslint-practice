## プロジェクト立ち上げ

npx create-react-app --template=typescript

## eslint 設定

npm init @eslint/config

```
? How would you like to use ESLint? …
  To check syntax only
  To check syntax and find problems
> To check syntax, find problems, and enforce code style
```

```
? What type of modules does your project use? …
❯ JavaScript modules (import/export)
  CommonJS (require/exports)
  None of these
```

```
? Which framework does your project use? …
❯ React
  Vue.js
  None of these
```

```
? Does your project use TypeScript?  No /> Yes
```

```
? Where does your code run? …  (Press <space> to select, <a> to toggle all, <i> to invert selection)
✔ Browser ←
✔ Node
```

```
? How would you like to define a style for your project? …
❯ Use a popular style guide
  Answer questions about your style
```

```
? Which style guide do you want to follow? …
❯ Airbnb: https://github.com/airbnb/javascript
  Standard: https://github.com/standard/standard
  Google: https://github.com/google/eslint-config-google
  XO: https://github.com/xojs/eslint-config-xo
```

```
? What format do you want your config file to be in? …
 JavaScript
  YAML
> JSON
```

```
? Would you like to install them now with npm? No /> Yes
```

## airbnb の eslint リンとプラグインをインストール

npm i -D eslint-config-airbnb-typescript
