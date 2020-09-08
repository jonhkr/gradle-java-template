# Template Project

Gradle + Java

## Features
- Code formatting using [spotless](https://github.com/diffplug/spotless) plugin
- Test coverage using Jacoco
- Junit 5 for tests
- Centralized dependency management

## Requirements

This is a [cookiecutter](https://github.com/cookiecutter/cookiecutter) template, follow the instructions [here](https://github.com/cookiecutter/cookiecutter) to install it.

## Usage

```sh
cookiecutter gh:jonhkr/gradle-java-template
```

## Structure

```
.
|____README.md
|____gradle
| |____wrapper
| | |____gradle-wrapper.jar
| | |____gradle-wrapper.properties
| |____deps.gradle
|____gradlew
|____.gitignore
|____.github
| |____workflows
| | |____gradle.yml
|____build.gradle
|____.gitattributes
|____gradlew.bat
|____settings.gradle
|____src
| |____test
| | |____resources
| | |____java
| | | |____template
| | | | |____AppTest.java
| |____main
| | |____resources
| | |____java
| | | |____template
| | | | |____App.java
```
