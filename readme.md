## About

[![Build Status](https://travis-ci.org/mgechev/javascript-algorithms.svg?branch=Jakehp-patch-1)](https://travis-ci.org/mgechev/javascript-algorithms)

This repository contains JavaScript implementations of different famous Computer Science algorithms.

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

and all `*.spec.js` files will be executed.

**To deploy documentation site**

```bash
npm run deploy
```

This requires you to have commit access to your Git remote.

## Contributions

Fork the repo and make required changes. After that push your changes in branch, which is named according to the changes
you did. Initiate the PR.

Make sure you're editor makes validations according to the `.jshintrc` in the root directory of the repository.

Before pushing to the repository run:

```bash
npm run build
```

If the build is not successful fix your code in order the tests and jshint validation to run successfully and after that
create a pull request.



The code in this repository is distributed under the terms of the MIT license.
