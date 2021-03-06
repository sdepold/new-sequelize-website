# sequelize.org

Sequelize's documentation website

This website is built using [Docusaurus 2](https://docusaurus.io/).

### Installation

```bash
# install local dependencies using yarn
yarn

# download the sequelize repository (used for including tested code snippets & generating jsdoc)
./sync-repositories.sh
```

### Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
