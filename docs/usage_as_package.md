# Usage Guide

## Using the Full Controller

To use the full controller, follow these steps:

1. Install the project using pip or Poetry:

    ```sh
    pip install weather_provider_libraries
    ```

    or

    ```sh
    cd .../weather_provider_libraries/
    poetry install
    ```

2. Import and use the `Controller` class in your code:

    ```python
    from weather_provider_libraries.core import Controller

    controller = Controller()
    event = controller.get_event(source_name="example", model_name="example_model_1")
    ```

## Installing and Using a Single Source

To install and use a single source, follow these steps:

1. Install the project using pip or Poetry:

    ```sh
    pip install weather_provider_libraries
    ```

    or

    ```sh
    cd .../weather_provider_libraries/
    poetry install
    ```

2. Import and use the `Source` class in your code:

    ```python
    from weather_provider_sources.example import ExampleSource

    source = ExampleSource()
    event = source.get_event(model_name="example_model_1")
    ```

## Installing and Using a Single Model

To install and use a single model, follow these steps:

1. Install the project using pip or Poetry:

    ```sh
    pip install weather_provider_libraries
    ```

    or

    ```sh
    cd .../weather_provider_libraries/
    poetry install
    ```

2. Import and use the `Model` class in your code:

    ```python
    from weather_provider_sources.example import ExampleModel

    model = ExampleModel()
    event = model.get_event()
    ```