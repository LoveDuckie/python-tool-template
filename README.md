# Python Tool Template

This repository is a template for creating Python tools with a consistent structure and standard features like linting, testing, and packaging.

## Features

- **Python Package Structure**: Includes a basic Python package setup (`python_tool_template`).
- **Testing Setup**: Example test files (`python_tool_template_tests`) for unit testing.
- **Development Tools**: Shell scripts to automate formatting, linting, testing (`run_format.sh`, `run_lint.sh`, `run_tests.sh`), and renaming (`rename.sh`).
- **Project Configuration**: Uses `pyproject.toml` for dependency management with [Poetry](https://python-poetry.org/).

## Getting Started

### Prerequisites

- Python 3.8+
- [Poetry](https://python-poetry.org/) for dependency management


### Dependencies

The project uses several dependencies defined in `pyproject.toml`. Below is a summary of the main dependencies and their purposes:

- **[Poetry](https://python-poetry.org/)**: Used for dependency management and packaging.
- **Linting and Formatting**: Includes tools like `pylint` and `black` to ensure code quality and consistency.
- **Testing**: Uses `pytest` for unit testing to ensure the functionality of the code.

To install the dependencies, use:

```sh
poetry install
```

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/python-tool-template.git
    cd python-tool-template
    ```

2. Install the dependencies:

    ```sh
    poetry install
    ```

### Running the Tool

To run the main script:

```sh
poetry run python -m python_tool_template
```

### Development

#### Formatting

To format the codebase:

```sh
./run_format.sh
```

#### Linting

To lint the codebase:

```sh
./run_lint.sh
```

#### Testing

To run the tests:

```sh
./run_tests.sh
```

#### Renaming the Project

To rename the project (e.g., change the package name from `python_tool_template` to something else):

```sh
./rename.sh new_project_name
```

### Project Structure

- `python_tool_template/`: The main package containing the tool's source code.
- `python_tool_template_tests/`: Contains unit tests for the package.
- `.gitignore`: Specifies files and folders to be ignored by Git.
- `pyproject.toml`: Project configuration and dependency management file.
- `LICENSE`: The license for this project.

### License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

### Contributing

Feel free to open issues or submit pull requests for new features, bug fixes, or improvements.

## Acknowledgements

This template is inspired by best practices for Python tool development, making it easy to start a new project with a consistent and productive setup.
