# Kolektivo TT Subgraph

The Subgraph for the Kolektivo TT Installation.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains the subgraph for the Kolektivo TT installation. A subgraph defines the data structure and the way data is indexed from the blockchain, making it easy to query.

The contracts and documentaiton of the badges of the platform can be found [here](https://github.com/Kolektivo-Labs/Kolektivo-network-badges)

## Prerequisites

Before you begin, ensure you have Node.js and npm installed, Docker (for running a local Graph Node), and Yarn.

## Installation

To install the project, clone and isntall repository dependencies with: 

```bash
git clone https://github.com/Kolektivo/kolektivo-tt-subgraph.git
cd kolektivo-tt-subgraph
yarn install
```

## Configuration

Update the `networks.json` file to match the network configurations.

## Usage

Generate the types for the GraphQL schema using `yarn codegen`. Deploy the subgraph with `yarn deploy`.

## Testing

To run tests, execute `yarn test`.

## Contributing

Contributions are welcome. Please read the contributing guidelines for details on the process for submitting pull requests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.