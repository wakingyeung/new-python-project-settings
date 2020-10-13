# New Python Project Settings

## Introduction

The first step of a new python project!

## Installation

1. Install [poetry](https://python-poetry.org/docs/) in global environment

    ```sh
    sudo pip3 install poetry
    ```

2. Install [commitizen](https://commitizen-tools.github.io/commitizen/) and [pre-commit](https://pre-commit.com) in project path

    ```sh
    poetry install
    ```

3. Install the git hook scripts

    ```sh
    poetry run pre-commit install
    ```

## Usage

1. Create new commit

    ```sh
    cz c
    ```

2. Bump semantic version and generate changelog based on the git log

    ```sh
    cz bump --changelog --yes
    ```
