
# Cypress Practice



<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    <li>
        <a href="#practice">Practice</a>
        <ul>
            <li><a href="#opening-cypress">E2E Testing</a></li>
            <li><a href="#testing-structure">E2E Testing</a></li>
        </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


### Built With

This project was build with the following technologies:

* [![Cypress][cypress]][cypress-url]
* [![Node][node]][node-url]
* [![NPM][npm]][npm-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started

Before anything else, you need to follow some instructions on setting up your project locally.

### Prerequisites

To execute next steps, you need to ensure npm is installed in your environment.
```bash
npm install npm@latest -g
```

### Installation

1. Initialize node package manager (npm)

```bash
npm init -y
```

2. Install Cypress package.

```bash
npm install cypress --save-dev
```

3. Access package.json.

```json
  "scripts": {
    "cy:open": "cypress open"
  }
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Cypress Practice

### Opening Cypress

1. Run the following command on terminal.

```bash
npm run cy:open
```

2. A window must have been opened. So, you'll need to click in 'E2E Testing' for now.
3. Select your favorite development browser and click in 'Start E2E Testing in Chrome'.

### Testing Structure

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

To found more information about Cypress, visit: [docs.cypres.io](https://docs.cypress.io).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[cypress]: https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e
[cypress-url]: https://www.cypress.io/
[node]: https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white
[node-url]: https://nodejs.org/
[npm]: https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white
[npm-url]: https://www.npmjs.com/
