# Athanor - AI Workbench Website

This repo contains the source code and files of the website of [Athanor - AI Workbench](https://github.com/lacerbi/athanor), built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
yarn
```

## Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## License

Athanor's website code is released under the [MIT license](./LICENSE).

Athanor's documentation, including tutorials and blog posts (e.g., `.md` files in the `/docs` and `/blog` folders) is licensed under [Creative Commons CC-BY 4.0](./LICENSE-docs).
