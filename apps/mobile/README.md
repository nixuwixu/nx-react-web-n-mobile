

# Stableto - Mobile

## Generate an component
Run `npx nx generate @nrwl/react:component HelloWorld --dry-run` to generate an component.

## Generate an application

Run `nx g @nrwl/react:app my-app` to generate an application.

> You can use any of the plugins above to generate applications as well.

When using Nx, you can create multiple applications and libraries in the same workspace.

## Generate a library

Run `nx g @nrwl/react:lib my-lib` to generate a library.

> You can also use any of the plugins above to generate libraries as well.

Libraries are shareable across libraries and applications. They can be imported from `@stableto/mylib`.

## Development server

Run `nx serve mobile`

to serve the application Javascript bundler that communicates with connected devices. This will start the bundler at http://localhost:8081.

Run `npx nx run-android mobile`

to run the applicatoin in development mode on Android simulator/device

Run `npx nx run-ios mobile`

to run the applicatoin in developement mode on iOS simulator/device.

## Code scaffolding

Run `nx g @nrwl/react:component my-component --project=my-app` to generate a new component.

## Build

Run `nx build web` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `nx test mobile` to execute the unit tests via Jest

Run `nx affected:test` to execute the unit tests affected by a change.

## Running end-to-end tests

Run `nx e2e mobile-e2e` to execute the end-to-end tests via Cypress

Run `nx affected:e2e` to execute the end-to-end tests affected by a change.

## Linting
Run `npx nx lint mobile` to

## Format
Run `npx nx format` to format code with Prettier

## ☁ Deploy


Nx Cloud pairs with Nx in order to enable you to build and test code more rapidly, by up to 10 times. Even teams that are new to Nx can connect to Nx Cloud and start saving time instantly.
