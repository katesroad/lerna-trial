# README

- [Lerna](https://lerna.js.org/)

## Tutorials

- Create a project under packages

  -[create a react app using cra](https://create-react-app.dev/docs/getting-started)

  - under packages, run

  ```bash
  lerna clean -y # clean all the current dependencies under the app
  ```

  - install dependencies under the root level node_module

  ```bash
  lerna bootstrap --hoist
  yarn
  ```
