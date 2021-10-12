# conference-app

The recent and unprecedented level of innovation in web standards is incredibly exciting. Many features that required frameworks now come standard. You no longer need a proprietary component model, proprietary language extensions, proprietary modules, and so forth. The standardization of the core stack opens the door to a new breed of frameworks: frameworks whose major task is no longer to fill in the gaps in the core stack, but to provide a thin layer of specialized services on top of a standard stack that is now suitable for large scale app development. The benefits are substantial.

Lightning Web Components Open Source is an implementation of that new breed of lightweight frameworks built on web standards. It uses custom elements, templates, shadow DOM, decorators, modules, and other new language constructs available in ECMAScript 6 and beyond.

In this project, you use Lightning Web Components Open Source to create a sample conference management application. This project is the first in a series of three projects that introduce you to Lightning Web Components.

## How to start?

Start simple by running `yarn watch` (or `npm run watch`, if you set up the project with `npm`). This will start the project with a local development server.

The source files are located in the [`src`](./src) folder. All web components are within the [`src/client/modules`](./src/modules) folder. The folder hierarchy also represents the naming structure of the web components. The entry file for the custom Express configuration can be found in the ['src/server'](./src/server) folder.

Find more information on the main repo on [GitHub](https://github.com/muenzpraeger/create-lwc-app).
