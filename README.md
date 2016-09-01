# concordion-timing-extension-demo

Demonstrates the usage of the Concordion Timing Extension


[![Build Status](https://travis-ci.org/concordion/concordion-timing-extension-demo.svg?branch=master)](https://travis-ci.org/concordion/concordion-timing-extension-demo)

# Introduction
------------

This project demonstrates the usage of the [Concordion](http://concordion.org) [Timing Extension](https://github.com/concordion/concordion-timing-extension).


Example output is shown [here](https://concordion.github.io/concordion-timing-extension-demo/spec/spec/Timing.html). 

# Running the tests
---------------------------

### Using Gradle

The download includes support to run the tests with the [Gradle](http://www.gradle.org/) build tool. The code base includes the Gradle Wrapper, which will automatically download the correct version of Gradle. 

Gradle can be run from the command line or from your IDE:

Command line
============
From the command line, `cd` to the folder containing a copy of this project, and run 

  `./gradlew clean test` on Unix-based systems, or 
  `.\gradlew clean test` on Windows.

This will download the required dependencies, clean the existing project, recompile all source code and run all the tests. 

Additional Gradle Files
-----------------------

`dev.gradle` is only needed if you want to run against snapshot or local builds of the concordion-timing-extension.

`publish.gradle` is only needed if you want to publish the output to Github pages.

If copying the project for your own use, you probably won't want either of these files.

### Using Maven

1. Download and install maven
2. From a command line opened at the location to which this package has been unzipped, run `mvn test`
3. View the Concordion output under the subfolder `target/concordion/demo`

Mailing List
-----------------
Feel free to discuss this demo project on the Concordion [mailing list](https://groups.google.com/d/forum/concordion).
