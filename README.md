# Proof of concept for web components

An experimentation on building web components using:
* the `customElements` browser API
* single-file components
* HTML imports
  * requires _polymer-bundler_
* HTML templates

## Run the project

Build bundle:

```bash
npm run build
```

Run development server:

```bash
npm run start
```

Finally browse http://localhost:8080

## TODO

* use [npm-watch](https://www.npmjs.com/package/npm-watch) to rebuild bundle when code changes
* example of data binding
* example of calling a backend service

## Code Pen

A _ligther_ version of the experimentation (no bundler) is available on my [Codepen](https://codepen.io/yvzn/pen/VwmJgJV)