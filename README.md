# Azure DevOps extension generator

Generates a basic Azure DevOps extension with support for hot reload and debugging in VS Code

## Installation

First, install [Yeoman](http://yeoman.io) and generator-azure-devops-extension using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```shell
npm install -g yo
npm install -g @microsoft/generator-azure-devops-extension
```

Then generate your new project:

```shell
yo @microsoft/azure-devops-extension
```

## Output

Running the generator will result in the following file structure:

```text
.
├── .eslintrc.js
├── .gitignore
├── .vscode
│   └── launch.json
├── README.md
├── configs
│   ├── dev.json
│   └── release.json
├── img
│   └── world.png
├── package.json
├── src
│   └── hub
│       ├── hub.html
│       ├── hub.scss
│       └── hub.tsx
├── tsconfig.json
├── vss-extension.json
└── webpack.config.js
```

Refer to the generated `README.md` file to learn more about how the project works.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
