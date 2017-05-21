# eurekaclinical-parent-standard-deps
[Atlanta Clinical and Translational Science Institute (ACTSI)](http://www.actsi.org), [Emory University](http://www.emory.edu), Atlanta, GA

# What does it do?
It is the parent pom used by all Eureka! Clinical web applications. It has a fairly large dependencyManagement section with various dependencies that provide the following functionality:
* logging
* utility libraries
* delimited file handling
* H2, PostgreSQL and Oracle JDBC driver versions
* INI file handling
* email handling
* versions of standard APIs
* CAS client
* REST API creation
* dependendency injection
* object-relational management
* unit and system testing
* database migration
* templates

Use these versions of these dependencies in Eureka! Clinical projects for the functionality listed above.

## Version history
### Version 1

## Specifying this pom as a parent
```
<parent>
    <groupId>org.eurekaclinical</groupId>
    <artifactId>eurekaclinical-parent-standard-deps</artifactId>
    <version>version</version>
</parent>
```

## Getting help
Feel free to contact us at help@eurekaclinical.org.
