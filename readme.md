<p align="center">
  <a href="https://ci.appveyor.com/api/projects/status/v562l6v4h098dvtf?svg=true">
    <img src="https://ci.appveyor.com/api/projects/status/v562l6v4h098dvtf?svg=true"
         alt="build status">
  </a>
  <a href="https://david-dm.org/tplss/node">
    <img src="https://david-dm.org/aladdin-add/eslint-plugin-autofix/status.svg"
         alt="dependency status">
  </a>
</p>

# eslint-plugin-autofix

## Install & usage

```bash
$ npm i eslint-plugin-autofix -D
```

add prefix "autofix" to the rulename in eslintrc:
```js
{
  "plugins": ["autofix"],
  "rules": {
    "autofix/no-debugger": "error"
  }
}
```

## Supported rules

✔️ indicates that a rule is recommended for all users.
🛠 indicates that a rule is fixable.

<!-- __BEGIN AUTOGENERATED TABLE__ -->
Name | ✔️ | 🛠 | Description
----- | ----- | ----- | -----
[no-alert](https://eslint.org/docs/rules/no-alert) |  | 🛠 | disallow the use of `alert`, `confirm`, and `prompt`
[no-console](https://eslint.org/docs/rules/no-console) | ✔️ | 🛠 | disallow the use of `console`
[no-debugger](https://eslint.org/docs/rules/no-debugger) | ✔️ | 🛠 | disallow the use of `debugger`
[no-plusplus](https://eslint.org/docs/rules/no-plusplus) | ✔️ | 🛠 | disallow the unary operators `++` and `--`
[prefer-spread](https://eslint.org/docs/rules/prefer-spread) |  | 🛠 | require spread operators instead of `.apply()`
[valid-typeof](https://eslint.org/docs/rules/valid-typeof) |  | 🛠 | enforce comparing `typeof` expressions against valid strings
<!-- __END AUTOGENERATED TABLE__ -->

## Contributing

+ to add a new rule:
```bash
npm run new ${ruleName}
```

## Acknowledgement
+ [ESLint](https://eslint.org)
+ [eslint-rule-composer](https://github.com/not-an-aardvark/eslint-rule-composer)