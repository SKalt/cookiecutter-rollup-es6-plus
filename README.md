cookiecutter-rollup-es6-plus
============================

A cookiecutter for authoring es6+ libraries with Rollup.js.  This cookiecutter
doesn't provide a transpiler such as buble or babel for es6/7, since most notable features are now
natively supported in the last two or three versions of the major browsers.

Installation
------------
If you haven't already, install the `cookiecutter` command line interface: `pip install cookiecutter`.

Usage
-----
Generate a new Cookiecutter template layout: `cookiecutter gh:SKalt/cookiecutter-rollup-es6-plus` and answer the questions provided. The cookiecutter will create a filestructure as follows:
```
bootstrap/
├── dist/
├── src/
│   └── index.js
├── test/
├── .editorconfig
├── .eslintrc
├── .gitignore
├── README.md
└── rollup.config.js
```

License
-------
This project is licensed under the terms of the [MIT License](/LICENSE)
