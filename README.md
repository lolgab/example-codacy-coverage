# Cobertura example

## What?

Sample project that uses Maven Cobertura plugin

## Prerequisites

1.  Java JDK 8
2.  Maven 3.0+

## How?

```bash
$ git clone git@github.com:dds-utn/cobertura-example.git
$ cd cobertura-example
$ mvn dependency:resolve
$ mvn clean test
$ mvn cobertura:check
```

## Generated HTML site

```bash
$ mvn cobertura:cobertura
```

And check **target/site/cobertura/index.html**.
