# Pairwise Testing, Cyclomatic Complexity, and Whitebox Testing

This repository contains three distinct projects, each demonstrating important
concepts in software testing and analysis. These projects are structured as Git
submodules, and each focuses on a specific testing or analysis technique.

## Projects Overview

### 1. **Pairwise Testing**

This project showcases the use of pairwise testing for validating functions
with multiple parameters. Pairwise testing ensures that all possible pairs of
input values are covered by test cases, optimizing test coverage while reducing
the number of tests.

- **Location**: `pairwise_testing/`
- **Key Concepts**: Pairwise testing, test optimization, combinatorial testing.

### 2. **Cyclomatic Complexity Analyzer**

This project focuses on calculating and analyzing the cyclomatic complexity of
Python functions. Cyclomatic complexity is a software metric used to measure the
complexity of a program's control flow. The analysis is done through Python’s
`ast` module, and the results are displayed in the console.

- **Location**: `cyclomatic_complexity_analyzer/`
- **Key Concepts**: Cyclomatic complexity, code analysis, static code metrics.

### 3. **Whitebox Testing**

This project demonstrates whitebox testing principles using Python's `pytest`
framework. The goal is to perform unit testing on functions with various
complexities, covering different code paths, conditions, and edge cases.

- **Location**: `whitebox_testing/`
- **Key Concepts**: Whitebox testing, code coverage, branch testing.

## Project Structure

```css
main_repo
├── pairwise_testing/                # Pairwise testing project
├── cyclomatic_complexity_analyzer/  # Cyclomatic complexity analysis project
├── whitebox_testing/                # Whitebox testing project
└── README.md                        # This README file
```

Each of these submodules is an independent project, and you can explore them
individually by navigating to their respective directories.

## Requirements

Each project in this repository has its own set of dependencies, listed in their
respective `requirements.txt` files. Make sure to set up a virtual environment
and install the required dependencies for the specific project you want to work
with.

## Cloning the Repository

To clone this repository along with the submodules:

```scss
git clone --recurse-submodules https://github.com/paulo-grathon/fatec_lab_bd_5_presentation
```

If you have already cloned the repository and need to initialize the submodules,
run:

```scss
git submodule update --init --recursive
```

## Running the Projects

For each of the submodules, refer to their respective README files for detailed
instructions on setting up and running the projects.

- **Whitebox Testing**: Located in `whitebox_testing/README.md`
- **Pairwise Testing**: Located in `pairwise_testing/README.md`
- **Cyclomatic Complexity Analyzer**: Located in `cyclomatic_complexity_analyzer/README.md`
