# Chatbot for Package Documentations

This repository is an experimental work to create a chatbot that can be trained on package documentations. The aim is to create tailored solutions for convoluted or complex documentations, making it easier for users to understand and implement the package functionalities.

## Repository Structure

```
.
├── README.md          # This documentation
├── data               # Data files, likely training data for the chatbot
├── notebooks          # Jupyter notebooks, potentially for exploratory analysis or model prototyping
├── poetry.lock        # Lock file for poetry dependencies, ensuring consistent package versions
├── pyproject.toml     # Poetry configuration file, listing package dependencies and metadata
├── src                # Source code for the chatbot application
│   └── __init__.py
└── tests              # Unit and integration tests
    └── __init__.py
```

## Getting Started

### Prerequisites

- Python >= 3.7
- [Poetry](https://python-poetry.org/) for dependency management

### Installation

1. Clone this repository:
```bash
git clone https://github.com/llctrautmann/DocGPT.git
cd DocGPT
```

2. Install the required dependencies using Poetry:
```bash
poetry install
```

### Usage

*Additional information on how to use the chatbot, train on new data, or integrate with other applications should be added here as the project progresses.*

## Development

### Source Code

The main application code can be found under the `src` directory.

### Testing

Unit tests are placed under the `tests` directory. To run all tests, execute:

### Notebooks

For any exploratory data analysis, model prototyping, or other experiments, use the provided Jupyter notebooks found in the `notebooks` directory.

## Contributing

We welcome contributions! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) guide for details on how to submit patches and the contribution workflow.

## License

*MIT*
