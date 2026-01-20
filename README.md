# AXEL Marketplace

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Axel](https://img.shields.io/badge/Axel-Core-orange)](https://github.com/apiksdev/axel-core)
[![Support](https://img.shields.io/badge/Support-Development-3fb950)](https://github.com/apiksdev/axel-core/blob/master/FUNDING.md)

AXEL (AI XML Execution Language) plugin marketplace - a powerful framework that extends Claude Code with workflows, skills, agents, and commands. Discover and install plugins to enhance your AI-assisted development experience.

## Installation

```bash
claude plugin marketplace add apiksdev/axel-marketplace
```

## Available Plugins

| Plugin                                                       | Description                                                                          |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| [**axel-core**](https://github.com/apiksdev/axel-core)       | Core framework providing workflows, skills, agents, and commands for AXEL ecosystem. |
| [**axel-bundler**](https://github.com/apiksdev/axel-bundler) | Bundle multiple reference files into single documents for streamlined context management. |
| [**axel-todos**](https://github.com/apiksdev/axel-todos)     | Todo and backlog management with workflows and commands for task tracking. |

## Usage

After installing the marketplace, you can install individual plugins:

```bash
claude plugin install axel-core@axel-marketplace
claude plugin install axel-bundler@axel-marketplace
claude plugin install axel-todos@axel-marketplace
```



## License

[Apache 2.0](LICENSE)
