# An Angular 19 starter blueprint project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli). Additionally, tools, config and VS Code Settings have been added to ensure a high coding quality.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Coding rules

Strict null checks are enabled for Typescript, e.g. `const myConst: MyType = null` results in a compiler error.

The App is not using Angular modules but standalone by default. You should opt-in for using modules as soon as the app gets bigger.

## Linting and Formatting

This project uses `eslint` and `prettier` for linting and formatting. Formatting via prettier is part of the linting for html and typescript files.

For VS Code, there are already settings included to run linting and formatting on save. For Intellj, you have to enable it in the settings. Make sure to have the extensions/plugins installed in your IDE.

`Husky` is used together with `lint-staged` to format and lint staged files on commit. If linting fails and can not be fixed automatically, the commit will fail.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

Note that code scafolding will not create test files on default.
