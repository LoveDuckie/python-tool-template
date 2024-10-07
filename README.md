# Python Tool Template

This repository is a template for creating Python tools with a consistent structure and standard features like linting, testing, and packaging.

## Features

- **Python Package Structure**: Includes a basic Python package setup (`python_tool_template`).
- **Testing Setup**: Example test files (`python_tool_template_tests`) for unit testing.
- **Development Tools**: Shell scripts to automate formatting, linting, and testing (`run_format.sh`, `run_lint.sh`, `run_tests.sh`).
- **Project Configuration**: Uses `pyproject.toml` for dependency management with [Poetry](https://python-poetry.org/).

## Getting Started

### Prerequisites

- Python 3.8+
- [Poetry](https://python-poetry.org/) for dependency management

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

Find below the various shell scripts that were created for maintaining projects created from this project.

#### Rename

To rename the project from `python_project_template` to something of your choosing, run the following script.

```sh
./rename.sh <YOUR PROJECT NAME GOES HERE>
```

**Example:**

```sh
./rename.sh my_fancy_new_tool
```

**NOTE:** This will change both files that are in the generated project _and_ update the `pyproject.toml` file to reflect the name change.

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
