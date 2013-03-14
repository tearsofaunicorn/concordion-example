concordion-example
==================

This project provides an example setup for running the [Concordion] acceptance testing framework as part of [Maven]'s integration-test phase.

It also splits the acceptance tests into a separate source directory to the project unit tests.

This source project accompanies the blog post here:

[http://tearsofaunicorn.com/articles/setting-up-concordion-with-maven.html](http://tearsofaunicorn.com/articles/setting-up-concordion-with-maven.html)

## Building the project and running the tests

The project can be built using the standard Maven commands:
```sh
   mvn clean install
```

To run the acceptance tests on their own you can:

```sh
   mvn integration-test
```

[Concordion]: http://concordion.org
[Maven]: https://maven.apache.org
