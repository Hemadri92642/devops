# Building Java Projects with Maven
This guide walks you through using Maven to build a simple Java project.

## What you’ll build
You’ll create an application that provides the time of day and then build it with Maven.

## What you’ll need
+ A favorite text editor or IDE
+ JDK 6 or later
+ Install Maven

## Install Maven.
+ [Install Maven on Windows](https://www.baeldung.com/install-maven-on-windows-linux-mac#installing-maven-on-windows)
+ [Install Maven on Linux](https://www.baeldung.com/install-maven-on-windows-linux-mac#installing-maven-on-linux)
+ [Install Maven on Mac OSX](https://www.baeldung.com/install-maven-on-windows-linux-mac#installing-maven-on-mac-os-x)

## Set up the project
First you’ll need to setup a Java project for Maven to build. To keep the focus on Maven, make the project as simple as possible for now.

#### Create the directory structure
---
+ Create a root project directory named `HelloWorldMaven` and `cd HelloWorldMaven`.
+ In a project directory of your choosing, create the following subdirectory structure.
+ For example, with `mkdir -p src/main/java/hello` on *nix systems:*

+ on Windows you can create this directory manually.

    ```
    └── src
        └── main
            └── java
                └── hello
    ```
