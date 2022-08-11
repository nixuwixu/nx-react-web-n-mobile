

# Stableto

This project was generated using [Nx](https://nx.dev).


🔎 **Smart, Fast and Extensible Build System**


## Adding capabilities to your workspace

Nx supports many plugins which add capabilities for developing different types of applications and different tools.

These capabilities include generating applications, libraries, etc as well as the devtools to test, and build projects as well.

Run `npx nx list` to list installed plugins as well as other available plugins that can be installed

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

Run `nx serve web` for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `nx g @nrwl/react:component my-component --project=my-app` to generate a new component.

## Build

Run `nx build web` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `nx test web` to execute the unit tests via [Jest](https://jestjs.io).

`--watch` for interactive mode

`--testFile="apps/happynrwl/src/app/hello-world/hello-world.spectsx`

to run a specific file

Run `nx affected:test` to execute the unit tests affected by a change.

## Running end-to-end tests

Run `nx e2e web-e2e` to execute the end-to-end tests via [Cypress](https://www.cypress.io).

`--watch` to run it interactively

Run `nx affected:e2e` to execute the end-to-end tests affected by a change.

## Understand your workspace

Run `nx graph` to see a diagram of the dependencies of your projects.

## Linting
Run `npx nx lint web` to

## Format
Run `npx nx format` to format code with Prettier

## ☁ Deploy


Nx Cloud pairs with Nx in order to enable you to build and test code more rapidly, by up to 10 times. Even teams that are new to Nx can connect to Nx Cloud and start saving time instantly.
