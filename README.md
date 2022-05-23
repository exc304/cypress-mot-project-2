# cypress-mot-project

My imperfect cypress test automation repo. Brought to you by the tutorial from Marie Drake available on The Ministry of Testing website.

## Getting Started

These instructions assume you're using a recent macOSX. If you're using Windows, you may want to look into using Windows Subsytem for Linux 2 as the basis for your work. 

#### Pre-requisites

- Install Node.js and NPM
- Install [Visual Studio Code](https://github.com/mdcruz/cypress-mot-project#:~:text=NPM%20and%20Node-,Visual%20Studio%20Code,-Install%20Project%20Dependencies)

<details>
  <summary><em>Install Project Dependencies</em></summary>
Creates .zshrc file if one is not already present
  
```sh
touch ~/.zshrc
```
Download and install [Node.js](https://nodejs.org/en/download/)
  
Install Cypress version 8.4.0

```sh
npm i -D cypress@8.4.0
```
  
</details>

#### Cypress Test Runner

To open up the Cypress Test Runner and run the example test, execute `npx cypress open` on the project root. This will load up the Cypress Test Runner and add directory dependencies. 

#### Running Tests Headlessly

To run the tests on the command line, execute `npx cypress run`

\\Adding this line to ignore later.