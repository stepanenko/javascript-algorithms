## About

This repository contains JavaScript implementations of famous computer science algorithms.

API reference with usage examples available
<a href="https://mgechev.github.io/javascript-algorithms/" target="_blank">here</a>.

## Development

**To install all dev dependencies**

Call:

```bash
npm install
```

**To setup repository with documentation**

```bash
npm run doc
```

This will build the documentation and open it in your browser.

**To update .html files with documentation**

Just run `npm run doc` again.

**To run tests**

Call:

```bash
npm run test
```

This will execute all `*.spec.js` files.

**To deploy documentation site**

```bash
npm run deploy
```

This requires you to have commit access to your Git remote.

## Contributions

Fork the repo and make required changes. Afterwards, push your changes in branch. The name will be according to the changes you did. Initiate the pull request.

Make sure your editor makes validations according to the `.jshintrc` in the root directory of the repository.

Before pushing to the repository, run:

```bash
npm run build
```

If the build is not successful, fix your code in order for the tests and jshint validation to run successfully. Then create a pull request.

## Contributors

[<img alt="mgechev" src="https://avatars1.githubusercontent.com/u/455023?v=4&s=117" width="117">](https://github.com/mgechev)

## License

The code in this repository is distributed under the terms of the MIT license.

