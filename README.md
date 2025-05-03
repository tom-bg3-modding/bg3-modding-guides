# Tom's Personal BG3 Modding Wiki

Source code for my Baldur's Gate 3 Modding Toolkit docs site.

[Built Site](https://tom-project-strahd.github.io/project-strahd-modding-guides/wiki/index.html)

## Development Installation

1. Install [Antora](https://docs.antora.org/antora/latest/install-and-run-quickstart/).
2. Build the UI
    ```
    cd ui
    npm install
    npx gulp bundle
    cd ..
    ```

3. Build the Local Site:
    ```
    npx antora antora-playbook.yml
    ```

Updates to the GitHub Pages site are handed automatically by a GitHub workflow.
