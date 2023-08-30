# Kreyalogic Framework

Kreyalogic is a cutting-edge PHP framework designed to offer a comprehensive set of features for modern web application development. It aims to be fast, flexible, and developer-friendly, providing a unique set of tools for building scalable and maintainable applications.

## Features

- **Modular Architecture**
- **Powerful Routing System**
- **Extensible Plugin System**
- **Built-in ORM and Database Abstraction**
- **Custom Console Tool for Code Generation and Project Setup**
- **AI Integration**
- **And much more...**

## Requirements

- PHP 8.2 or higher
- Composer for dependency management
- MySQL, PostgreSQL, or SQLite for database

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/kreyalogicphp/Kreyalogic.git
cd Kreyalogic
```

Install dependencies using Composer:

```bash
composer install
```

## Usage

### Web Application

To start the development server, run:

```bash
php -S localhost:8000 -t public
```

Visit http://localhost:8000 in your web browser.

### Console Tool

Kreyalogic comes with a custom console tool to help you manage your project. You can generate entities, set up new projects, and more.

To generate a new entity:

```bash
./kreyalogic-cli.php generate:entity
```

To set up a new project:

```bash
./kreyalogic-cli.php setup:project
```

## Documentation

For detailed documentation, please visit [our documentation site](#).

## Contributing

We welcome contributions! Please see our [contributing guidelines](CONTRIBUTING.md) for more details.

## License

Kreyalogic is open-source software licensed under the [MIT license](LICENSE).
