# choo-event-order-example
repro for https://github.com/choojs/choo/issues/619

## Routes
Route              | File               | Description                     |
-------------------|--------------------|---------------------------------|
`/`              | `views/main.js`  | The main view
`/*`             | `views/404.js`   | Display unhandled routes

## Commands
Command                | Description                                      |
-----------------------|--------------------------------------------------|
`$ npm start`        | Start the development server
`$ npm test`         | Lint, validate deps & run tests
`$ npm run build`    | Compile all files into `dist/`
`$ npm run create`   | Generate a scaffold file
`$ npm run inspect`  | Inspect the bundle's dependencies
