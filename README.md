A plugin skeleton generator
===============

This webapp is a front-end for `mvn hpi:create` that creates a new plugin,
but it's less error prone and doesn't require fiddling `~/.m2/settings.xml`

To run app locally to test, `mvn jetty:run`.

To deploy this app into production, `mvn bees:deploy`. This application
runs on CloudBees RUN@cloud under the `jenkins` account