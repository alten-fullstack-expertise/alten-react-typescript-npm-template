# Boilerplate for creating React npm packages with Typescript

This is a boilerplate project that can be used to create npm packages with Typescript.

It supports a minimum react version from 16.8 onwards.

Run the following commands to start developing + testing.

1. First, install the dependencies: ``npm install``
2. Now we'll set up our test environment: ``cd example``, then ``npm install``
3. Now that we're in the "example" directory we can run the example project with `npm start`.

### Publish

To publish your new react package, follow the steps below.

1. In the project root, change the following data in the `package.json`: name, version, description. Make sure the name field is unique. No other NPM package can have that name.
2. If you are not logged in to npm, run the command ``npm login`` and enter your NPM credentials. If you have none, create an npm account on https://www.npmjs.com/
3. Finally, run `npm publish`

Congrats, your package has been published!