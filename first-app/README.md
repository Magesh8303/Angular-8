# FirstApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.5.

In this application customized root app added in app.compoent.html.

When we try to creating new application in angular,It must included an root component in every application.
Once Application initilization compeletion,There is lot file in application folder and there is one html file called index.html.
In this index.html is a top of root html file for every angular application.I want customize this root html file.There is 2 options to customizing the html file.

1.We can modified the app.component.html file.
2.We can modified the @selector in app.component.html file and add newly added compoent name in this.

For example:

@Component({
  selector: 'app-myfirst',
  templateUrl: './myfirst.component.html',
  styleUrls: ['./myfirst.component.css']
})

"app-myfirst" name added in index.html file instead of "app-root".

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
