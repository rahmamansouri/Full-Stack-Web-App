# Full stack app


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## build the Docker container

`docker build --platform=linux/amd64 -t angular-docker .`  

note  that `--platform=linux/amd64` is a requirement from render

## push the Docker container to dockerhub registry

`docker push rahma921/devops`

note that `devops` is the dockerhub repository that hosts the  docker images

## dockerhub
https://hub.docker.com/r/rahma921/devops/tags


## deploy to render
https://devops-2y7t.onrender.com


![Capture d’écran 2025-02-26 191625](https://github.com/user-attachments/assets/6cd53bb6-bf2d-4e7e-bfd7-60c978a0c93a)


![Capture d’écran 2025-02-26 192149](https://github.com/user-attachments/assets/8882f089-eceb-44e0-af56-53631ef355bb)
