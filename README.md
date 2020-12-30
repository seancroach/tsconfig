# `@seancroach/tsconfig`

<p align="left">
  <a href="https://github.com/seancroach/tsconfig/actions?query=workflow%3ACI">
    <img alt="build status" src="https://img.shields.io/github/workflow/status/seancroach/tsconfig/CI?logo=GitHub">
  </a>
  <a href="https://www.npmjs.com/package/@seancroach/tsconfig">
    <img alt="downloads" src="https://img.shields.io/npm/dt/@seancroach/tsconfig?logo=npm">
  </a>
</p>

_A robust shared TypeScript configuration I use across my projects._

## Highlights

- Enables strict options which enforce type safety
- Enables linting options which enforce a higher quality of code
- Enables importing `.json` files directly within TypeScript
- Targets Node v10 to ensure compatibility with all active LTS Node versions

Of course, you could write all the configurations yourself, but why do that when
it's already right here to use!

## Installation

Install `@seancroach/tsconfig` through `npm`:

```
$ npm install --save-dev @seancroach/tsconfig
```

## Usage

In your `tsconfig.json` file, extend `@seancroach/tsconfig` using the `extends` field:

```jsonc
{
  "extends": "@seancroach/tsconfig"
  // ...
}
```

## License

This package is available as open source under the terms of the [MIT License](https://github.com/seancroach/tsconfig/blob/latest/LICENSE.md).
