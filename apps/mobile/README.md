
# Stableto -  📱Mobile

## Development server

Run `nx serve mobile`

to serve the application Javascript bundler that communicates with connected devices. This will start the bundler at http://localhost:8081.

### Android
Run `npx nx run-android mobile`

to run the applicatoin in development mode on Android simulator/device

Run `emulator  -avd Pixel_4_API_31 & npx nx run-android mobile`

Run `emulator -list-avds` to list virtual devices on your machine

Run `emulator -avd Pixel_4_API_31` start emulator

### iOS
Run `npx nx run-ios mobile`

to run the applicatoin in developement mode on iOS simulator/device.

## 👷 Build

### Android
Run `nx build-android mobile` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### iOS(Mac only)
No CLI support yet. Run in the Xcode project. See: https://reactnative.dev/docs/running-on-device

## 🧪 Running unit tests

Run `nx test mobile` to execute the unit tests via Jest

## 🧩 Running end-to-end tests

### Android
Run `npx nx test-android mobile-e2e` to execute the end-to-end tests via Cypress

### iOS (Mac only)
run `npx nx test-ios mobile-e2e`

## Linting
Run `nx lint mobile` to analyze code.

## Format
Run `npx nx format mobile` to format code with Prettier

## ☁ Deploy

Nx Cloud pairs with Nx in order to enable you to build and test code more rapidly, by up to 10 times. Even teams that are new to Nx can connect to Nx Cloud and start saving time instantly.
