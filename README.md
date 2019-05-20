# Snowflake

Snowflake is --Medium's-- Jebbit's tool for planning and supporting our engineers' career development. You can read more
about how Medium uses this tool in their [growth framework documentation](https://medium.com/s/engineering-growth-framework).
Jebbit's growth tool is hosted [publicly](https://snowflake.jebbit.io).

## Contributions

You are free to use, change and build on this work to make it useful for your organisation. We will happily consider
unencumbered code contributions to improve functionality, but as this is the actual tool they use within Medium, acceptance is likely to be intentional, and deliberate. Meaning, slow. As such, you may prefer to fork the codebase for your own needs. We will not accept any contributions that modify the text of the application (but, thank you in advance for pointing out any typos).

## Installation

Get yarn if you don’t have it already:

`npm install -g yarn`

Install dependencies:

`yarn`

### Running the dev server

`yarn dev`

### Building

`yarn export`

This will put a static version of the site in `out/`.

## Future work

* Load initial data from a file, to improve flexibility.
* Add restricted job title selection and validation.
