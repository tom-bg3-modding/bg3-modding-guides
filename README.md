# Project Strahd Modding Guides

Source code for my Project Strahd docs site.

[Built Site](https://tom-project-strahd.github.io/project-strahd-modding-guides/devlogs/index.html)

## Development Installation

1. Install [Antora](https://docs.antora.org/antora/latest/install-and-run-quickstart/).
2. Build the UI
    1. `cd ui`
    2. `npm install`
    3. `npx gulp bundle`

3. Build the Local Site:
    ```
    cd ..
    npx antora antora-playbook.yml
    ```
