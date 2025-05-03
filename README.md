# Tom's Personal BG3 Modding Wiki

Source code for my Baldur's Gate 3 Modding Toolkit docs site.

[Built Site](https://tom-project-strahd.github.io/project-strahd-modding-guides/wiki/index.html)

## Development Installation

1. Install [Antora](https://docs.antora.org/antora/latest/install-and-run-quickstart/).
2. Build the UI
    1. `cd ui`
    2. `npm install`
    3. `npx gulp bundle`
    4. `cd ..`

3. Build the Local Site:
    ```
    npx antora antora-playbook.yml
    ```
