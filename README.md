# Demo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0-beta.32.3.

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).



##如何上傳到GitHub 2017/02/26

1.透過cmd創建一個新的ng2專案，指令為 `ng new 檔案名稱 --skip-tests`，後面帶的指令是省略測試用的(真正的用處還不確定)。

2.到GitHub上創建一個新的Repository，不要勾選`Initialize this repository with a README`，這是直接創建一個新的，但我們是要用我們創建好的ng2專案作為我們的初始master。

3.之後往下找找到`git remote add origin https://github.com/mich1001120/Angular2-Lab.git`和`git push -u origin master`，這兩個指令分別是指定遠端的儲存庫和把本機的ng2推上去作為master。

4.大功告成!
