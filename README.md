# The Agent · Landing Page

The source code of The Agent's landing page.

## How to run locally

  * First, ensure that NodeJS & Node Package Manager (npm) are both installed. If they're not installed, choose your OS and installation method from [this page](https://nodejs.org/en/download/package-manager) and follow the installation instructions.
  * This page requires Node 14 to work. You can handle multiple node versions with [NVM](https://github.com/nvm-sh/nvm), for example.
  * Next, use your command line to enter your project directory.
  * Run `npm install` to install all of the dependencies into your project. This should automatically clean, build, inspect and serve the page.

In case you get a dependency conflict, feel free to run the installation command with `--force` applied.

#### _Important_

> Don't forget to copy `git` hooks from `/hooks` to `.git/hooks` before starting your work!

And now you're ready to go!

#### _Pro tip_

> Run any of the available task by typing `npm run <task>` (where "task" is the name of the task in the `"scripts"` object in `package.json`). The most useful task for rapid development is `watch`. It will start a new server, open up a browser and watch for any SCSS or JS changes in the `src` directory; once it compiles those changes, the browser will automatically inject the changed file(s) into your distribution.
