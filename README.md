# Prettier Config used by teambits

## Goals

Goal: Minimal changed lines for versioning e.g. when more properties are added to an object or more parameters to an arrow function

* trailingComma: "es5"
* arrowParens: "always"

Goal: Reduce number of necessary characters (and I like it much better without all those semicolons ...)

* semi: false

Goal: Shrink file length (in terms of lines)

* printWidth: 120

## Usage

Reference this config in the project's `package.json`:

```
{
  "name": "my-cool-project",
  "version": "0.0.1",
  "prettier": "@teambits/prettier-config"
}
```

Or put this string to `.prettierrc.json`:

```
"@teambits/prettier-config"
```


See https://prettier.io/docs/en/configuration.html#sharing-configurations
