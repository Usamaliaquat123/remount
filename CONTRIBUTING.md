# Developer notes

- `yarn watch` will continuously build files into `dist/`.
- `open browser_test/index.html` to open the tests in your browser.

Doing `yarn test` (or `npm test`) will spawn a headless browser in your CLI to check if the browser tests pass or fail. Custom Elements aren't supported by JSDOM, so this (at the moment) is the most practical option IMHO :\