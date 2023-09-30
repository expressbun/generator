
[![Bun Logo](https://seeklogo.com/images/B/bun-logo-A876328A1F-seeklogo.com.png)](https://bun.sh/)
[![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)

[Express](https://www.npmjs.com/package/express) application generator for Bun. Based on express generator with tweaks to support bun run time and hot reload.

## Installation

```sh
$ bunx @expressbun/generator
```

## Quick Start

The quickest way to get started with express is to utilize the executable `express(1)` to generate an application as shown below:

Create the app:

```bash
$ bunx @expressbun/generator --ejs

```

Install dependencies:

```bash
$ bun install
```

Start your Express.js app at `http://localhost:3000/`:

```bash
$ bun dev or bun start
```

## Command Line Options

This generator can also be further configured with the following command line flags.

        --version        output the version number
    -e, --ejs            add ejs engine support
        --pug            add pug engine support
        --hbs            add handlebars engine support
    -H, --hogan          add hogan.js engine support
    -v, --view <engine>  add view <engine> support (dust|ejs|hbs|hjs|jade|pug|twig|vash) (defaults to ejs)
        --no-view        use static html instead of view engine
    -c, --css <engine>   add stylesheet <engine> support (less|stylus|compass) (defaults to plain css)
        --git            add .gitignore
    -f, --force          force on non-empty directory
    -h, --help           output usage information

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/express-generator.svg
[npm-url]: https://npmjs.org/package/express-generator
[appveyor-image]: https://img.shields.io/appveyor/ci/dougwilson/generator/master.svg?label=windows
[appveyor-url]: https://ci.appveyor.com/project/dougwilson/generator
[downloads-image]: https://img.shields.io/npm/dm/express-generator.svg
[downloads-url]: https://npmjs.org/package/express-generator
[github-actions-ci-image]: https://img.shields.io/github/workflow/status/expressjs/generator/ci/master?label=linux
[github-actions-ci-url]: https://github.com/expressjs/generator/actions/workflows/ci.yml
