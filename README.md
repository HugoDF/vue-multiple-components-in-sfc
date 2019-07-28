# Writing multiple components in a single Vue SFC file

Examples of writing multiple components in a single `.vue` file.

All 4 examples leverage `vue-cli`.

This repository leverages [Yarn Workspaces](https://yarnpkg.com/lang/en/docs/workspaces/).

Requirements:
- Node 10+
- Yarn 1+

To start working with the examples, run:
- `yarn`, to install dependencies required to run all the projects

To run commands in every example  package, you can use `yarn workspaces <command>` eg. `yarn workspaces build`.

To run commands in a single package, you can use `yarn workspace <workspace_name> run server`, eg. `yarn workspace 01-render-functions run server`
