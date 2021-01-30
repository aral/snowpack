<h1>Snowflake</h1>

This is a lightweight fork of [Snowpack](https://snowpack.dev) that I’m evaluating for use in [Place](https://github.com/small-tech/place).

Unless you’re using Snowpack as middleware and need to following niche functionality, you probably want to use the [original upstream](github.com/snowpackjs/snowpack/).

__Again, you probably want [Snowpack](https://github.com/snowpackjs/snowpack), not this.__

## Added

  - Support for custom TLS certificate file paths. [Discussion](https://github.com/snowpackjs/snowpack/discussions/2325). [Pull request](https://github.com/snowpackjs/snowpack/discussions/2325)
  - Extensible resolve paths (multiple roots). [Discussion](https://github.com/snowpackjs/snowpack/discussions/2327). [Pull request](https://github.com/snowpackjs/snowpack/pull/2432)
  - Svelte plugin support for `.interface` files. [Discussion](https://github.com/snowpackjs/snowpack/discussions/2360). [Pull request](https://github.com/snowpackjs/snowpack/pull/2380)

## Removed

  - Removed Skypack
  - Removed create-snowpack-app
  - Removed release scripts
  - Removed examples
  - Removed the Snowpack web site
  - Removed some plugins we won’t be using

## TODO

  - __FIX:__ `loadConfigurationFile()` uses require; fails with snowpack configuration in type="module" Node projects. [Discussion](https://github.com/snowpackjs/snowpack/discussions/2510)
  - __HMR:__ check if [setting the websocket port manually in the client](https://github.com/snowpackjs/snowpack/discussions/2288#discussioncomment-284878) still required with Fred’s PR [#2312](https://github.com/snowpackjs/snowpack/pull/2312). [Discussion](https://github.com/snowpackjs/snowpack/discussions/2288)

## License

Same as the original Snowpack license:

[MIT](https://github.com/small-tech/snowflake/blob/main/LICENSE)
