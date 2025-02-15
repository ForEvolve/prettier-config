# @forevolve/prettier-config

My shared [Prettier](https://prettier.io/) configuration.

![Deploy npm package](https://github.com/ForEvolve/prettier-config/workflows/Deploy%20npm%20package/badge.svg)

## How to use

Using `package.json` and `npm`:

1.  Install the package

    ```bash
    npm i --save-dev @forevolve/prettier-config
    ```

2.  Edit `package.json`:

    ```json
    {
      // ...
      "prettier": "@forevolve/prettier-config"
    }
    ```

> Note that you can create a `package.json` file and use it even if your project is not using [Node.js](https://nodejs.org/) by running `npm init` and following the instructions.

For more information, or other ways to load the package, please see the official Prettier documentation: [Configuration File](https://prettier.io/docs/en/configuration.html).

## Change log

### 2.0.1

- Update a keyword to test the paths filter of the GitHub action

### 2.0.0

- Change the entry point from `index.js` to `index.json`

### 1.0.0

- Initial release
