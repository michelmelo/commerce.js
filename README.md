

## Installation

### With NPM

`npm install @michelmelo/commerce.js` or `yarn add @michelmelo/commerce.js`

### TypeScript

You may also install our TypeScript definitions:

`npm install @types/chec__commerce.js` or `yarn add @types/chec__commerce.js`

Note that when using TypeScript, the definitions are always compliant with our latest version of the API. If you specify a custom API version, or your API
key uses an older version, you may get type errors.

## Documentation


Our documentation module source code resides in `commerce.js/docs`

If you would like to make contributions to the Commerce.js documentation source, here is a [guide](https://github.com/michelmelo/commerce.js/blob/master/CONTRIBUTING.md) in doing so.

## Configuration

The following configuration options are available to be defined as the third argument in the Commerce constructor:

* `disableStorage`: Whether to disable persistent storage (e.g. cookies). Enable for use in server-side environments. Default: false.
* `cartLifetime`: Number of days that a cart should be stored for (between 1 and 30). Default: 30.
* `timeoutMs`: The number of milliseconds before a request will time out. Default: 60000.
* `axiosConfig`: An optional object containing configuration options for axios, if used.
  * `headers`: A list of request headers. Defining headers here will override the defaults.
* `allowSecretKey`: Commerce.js will prevent you from using a secret API key for authorization. Use this option to override. Default: false.

## Upgrading



## Contributing
Check out the [contributing guide](CONTRIBUTING.md)

### Get help

### Running the tests

You can run the unit tests for this library from your command line using `npm run test`, or `npm run test:watch`
to watch for changed and re-run the tests automatically.

### Code style

We use the Airbnb JavaScript style guide, and Prettier as our linting tool. To lint your code, use `npm run lint`
or `npm run lint:fix` to automatically fix violations.
