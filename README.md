# BonFHIR Playground

This project is meant to teach you the basics of using the BonFHIR Core library.

It assumes a basic knowledge of [NodeJS](https://nodejs.org/), [Typescript](https://www.typescriptlang.org/) and [FHIR](https://hl7.org/fhir/).

## Getting started

- install [NodeJS](https://nodejs.org/)
- install [Docker](https://www.docker.com/) to run a local FHIR server
- install [Visual Studio Code](https://code.visualstudio.com/)
- install the [Node.js Notebooks (REPL) extension](https://marketplace.visualstudio.com/items?itemName=donjayamanne.typescript-notebook)

Once this is done:
 - open the project in VS Code
 - install the local dependencies using `npm install`
 - launch the local FHIR server by launching the **Command Palette**, choose **Tasks: Run Task**, then **Launch local FHIR Server**.

This should launch a local instance of Medplum to allow you to interact with a real FHIR Server and API.

Then follow the notebooks in the `notebooks` directory.