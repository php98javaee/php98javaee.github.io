# Sesam

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.27.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Service workers

Because ng serve does not work with service workers, you must use a separate HTTP server to test your project locally. You can use any HTTP server. The example below uses the http-server package from npm. To reduce the possibility of conflicts and avoid serving stale content, test on a dedicated port and disable caching.

`npm install http-server -g`

cors problems:

for windows

1-Open the start menu

2-Type windows+R or open "Run"

3-Execute the following command:

chrome.exe --user-data-dir="C://Chrome dev session" --disable-web-security

and

`npm run start:prod`
