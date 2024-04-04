# Analog App

This project was generated with [Analog](https://analogjs.org), the fullstack meta-framework for Angular.

## Setup

Run `npm install` to install the application dependencies.

## Development

Run `npm start` for a dev server. Navigate to `http://localhost:5173/`. The application automatically reloads if you change any of the source files.

## Build

Run `npm run build` to build the client/server project. The client build artifacts are located in the `dist/analog/public` directory. The server for the API build artifacts are located in the `dist/analog/server` directory.

## Test

Run `npm run test` to run unit tests with [Vitest](https://vitest.dev).

## Community

- Visit and Star the [GitHub Repo](https://github.com/analogjs/analog)
- Join the [Discord](https://chat.analogjs.org)
- Follow us on [Twitter](https://twitter.com/analogjs)
- Become a [Sponsor](https://github.com/sponsors/brandonroberts)


## Installation

Run:
```bash
npm create analog@latest
```
Choose:
 - Project name:  **my-habitica-clone**
 - Select a template? **Analog**
 - Select a variant? **angular-v17**
 - Would you like to add Tailwind to your project? **Yes**

Run:
```bash
cd my-habitica-clone
```

In *package.json* edit:
```json
"scripts": {
  "ng": "npx -p @angular/cli@17 ng",
}
```

Run:
```bash
npm run ng add @ionic/angular
```

Run:
```bash
ionic init
```
Choose:
 - Project name:  **my-habitica-clone**

```bash
[OK] Your Ionic project has been initialized!
```

Run:
```bash
ionic integrations enable capacitor
```




