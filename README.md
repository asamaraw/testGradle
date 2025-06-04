# testGradle

This is a test project that demonstrates the usage of the Wiz Gradle Plugin.

## Project Overview

This project is set up to showcase how to integrate the Wiz Gradle Plugin into a Java project. It includes basic Gradle configuration and a sample task.

## Prerequisites

- Java 17 or higher
- Gradle 8.9 or higher
- WIZ Gradle plugin code in the same folder as this project and built (artifact is in `wiz-gradle-plugin/build/libs` and referenced from filepath in `build.gradle`)
- Wiz CLI installed and available in PATH

## Project Setup

The project is configured with:
- Java plugin
- Wiz Gradle Plugin
- Maven Central repository

## Available Tasks

- `./gradlew build`: Builds the project
- `./gradlew wizScanDir`: Runs a Wiz directory scan
- `./gradlew hello`: A sample task that prints "Hello, World!"

## Configuration

The Wiz plugin is configured with:
```groovy
wiz {
    projectId = 'example-project'
    repositoryName = 'test-repo'
}
```

## Getting Started

1. Clone the repository
2. Ensure Java 17+ is installed
3. Ensure Wiz CLI is installed and in PATH
4. Run `./gradlew build` to build the project
5. Run `./gradlew wizScanDir` to perform a Wiz scan

## Project Structure

- `build.gradle`: Main build configuration
- `settings.gradle`: Project settings
- `.gitignore`: Git ignore rules
- `README.md`: This file

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
