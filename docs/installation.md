# Installation Guide

## Installing via pip

To install the project using pip, run the following command:

```sh
pip install weather_provider_libraries
```

## Installing via Poetry

To install the project using Poetry, run the following commands:

1. Install Poetry if you haven't already:

    ```sh
    curl -sSL https://install.python-poetry.org | python3 -
    ```

2. Navigate to the project directory and install the dependencies:

    ```sh
    cd .../weather_provider_libraries/
    poetry install
    ```

## Using the Docker File

To build and run the Docker container, follow these steps:

1. Build the Docker image:

    ```sh
    docker build -t weather_provider_libraries