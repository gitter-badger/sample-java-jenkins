# Using this Project

This project is using the latest Selenium Bindings.

## Setup
Run these commands depending on your base OS.

### On Mac OS

Install Java JDK

Install Homebrew `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Install Maven `brew install maven`

Run `brew install geckodriver`

## Running Tests

The following commands are instructions on how to run the tests

### From CLI

`mvn test`

### Intellij Idea

There is a shared run configuration that has the maven target setup and another with a sample built in NUnit test runner option.
