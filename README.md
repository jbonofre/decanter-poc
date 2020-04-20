# Decanter PoC

This PoC shows how to create a simple feature XML preconfiguring and wrapping Apache Karaf Decanter collectors, processors, and appenders.

It's easy to install in a running Apache Karaf runtime:

----
karaf@root()> feature:repo-add mvn:net.nanthrax.poc/decanter-poc/1.0-SNAPSHOT/xml/features
karaf@root()> feature:install decanter-poc
----