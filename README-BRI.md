# BRI DEV STUDIO

Welcome to BRI Dev Studio! This repository contains the code and instructions for setting up and running the BRI DEX server and client.

## How-Tos

### Custom DEX

To customize the DEX server, follow these steps:

1. Clone the repository from [https://github.com/feedloop/dex](https://github.com/feedloop/dex).
2. Use the following command in the terminal to create a tarzip file:
    ```shell
    # BEGIN: Create tarzip file
    tar -czvf dex.tar.gz dex/
    # END: Create tarzip file
    ```
3. Replace the tarzip file in this folder with the newly created one.

4. To clean, build, and run the DEX server, use the following command:
    ```shell
    make clean && make build && ./bin/dex serve examples/config-dev.yaml
    ```

5. Use `make examples && ./bin/example-app` to run the DEX client.
6. Use the minified `encode.min.js` for static functions.
7. Replace the static link on the web template with the domain.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

Instructions on how to install and set up the project.

## Usage

Examples and instructions on how to use the project.

## Contributing

Guidelines for contributing to the project.

## License

This project is licensed under the [MIT License](LICENSE).

# Project Name

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

A brief description of the project.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

Instructions on how to install and set up the project.

## Usage

Examples and instructions on how to use the project.

## Contributing

Guidelines for contributing to the project.

## License

This project is licensed under the [MIT License](LICENSE).
