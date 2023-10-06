# java-cli-buildr-hibernate-cockroachdb-single-node-without-ssl-simple

## Description
Creates a small database table
called `dog` and populates with
hql.
A java buildr build, that connects to single node
cockroach database without ssl.

## Tech stack
- java
- buildr
  - hibernate
  - hql
  - log4j
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)
