# Welcome to Mongo2Postman

## What's in the folder

* This folder contains all of the files necessary for your Mongo2Postman VS Code extension.
* `package.json` - the manifest file where your extension, commands, and metadata are declared.
  * This registers the command "Convert to Postman Raw" so VS Code can show it in the command palette.
* `src/extension.ts` - main implementation file.
  * Exports `activate`, which is called the first time your extension runs. Inside `activate`, the command is registered.
  * The command implementation converts Mongoose schemas to Postman-ready JSON using Google's Generative AI.

## Get up and running

* Press `F5` to open a new VS Code window with your extension loaded.
* Run the command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) by typing **Convert to Postman Raw**.
* Set breakpoints in `src/extension.ts` to debug your code.
* Check output in the Debug Console.

## Make changes

* After editing `src/extension.ts`, relaunch your extension from the debug toolbar.
* Reload the VS Code window (`Ctrl+R` or `Cmd+R`) to see your changes.

## Explore the API

* Check the full VS Code API in `node_modules/@types/vscode/index.d.ts`.

## Run tests

* Install [Extension Test Runner](https://marketplace.visualstudio.com/items?itemName=ms-vscode.extension-test-runner).
* Run the "watch" task via **Tasks: Run Task** to discover tests.
* Open the Testing view and click **Run Test**, or use `Ctrl/Cmd + ; A`.
* Modify `src/test/extension.test.ts` or add new `.test.ts` files inside `test/` to create tests.

## Go further

* Follow [UX guidelines](https://code.visualstudio.com/api/ux-guidelines/overview) for smooth VS Code integration.
* Improve performance by [bundling your extension](https://code.visualstudio.com/api/working-with-extensions/bundling-extension).
* [Publish your extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) to the Marketplace.
* Automate builds with [Continuous Integration](https://code.visualstudio.com/api/working-with-extensions/continuous-integration).
