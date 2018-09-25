Archetype Modern Starter
========================

[![Build Status](https://travis-ci.org/coder168/archetype-modern-starter.svg?branch=master)](https://travis-ci.org/coder168/archetype-modern-starter)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.coder168/archetype-modern-starter.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.github.coder168%22%20AND%20a:%22archetype-modern-starter%22)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

What is it
----------

This maven archetype is used to generate modern java standalone application project.

* [project homepage](https://github.com/coder168/archetype-modern-starter)
* [apache license 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
* [issue tracking](https://github.com/coder168/archetype-modern-starter/issues)

The generated project uses the following technologies:

* java 8
* maven 3.5.x
* log4j 2.11.1
* junit 4.12

How to use
----------

Under the command line, type the following command:
   > mvn archetype:generate -Dfilter=archetype-modern-starter

or
   > mvn archetype:generate -Dfilter=io.github.coder168:

and then follows the given instructions.

How to install into local repository
------------------------------------

If you want to install the latest version(SNAPSHOT) into your local repository:

1. clone the archetype project
2. under project directory, type the following command:
   > mvn clean install
