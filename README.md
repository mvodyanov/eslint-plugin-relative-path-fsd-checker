# eslint-plugin-relative-path-fsd-checker

This plugin provides several rules for enforcing consistent import and export syntax and behavior in JavaScript\Typescript code. 


## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-relative-path-fsd-checker`:

```sh
npm install eslint-plugin-relative-path-fsd-checker --save-dev
```

## Usage

Add `relative-path-fsd-checker` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "relative-path-fsd-checker"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "relative-path-fsd-checker/rule-name": 2
    }
}
```

## Rules

Feature-Sliced Design (FSD) is an architectural methodology for scaffolding front-end applications. Simply put, it's a compilation of rules and conventions on organizing code. The main purpose of this methodology is to make the project more understandable and structured in the face of ever-changing business requirements.



