# Eureka! Clinical Web Application Parent pom.xml
[Georgia Clinical and Translational Science Alliance (Georgia CTSA)](http://www.georgiactsa.org), [Emory University](http://www.emory.edu), Atlanta, GA

# What does it do?
It is the parent pom used by all Eureka! Clinical web applications. It specifies [eurekaclinical-parent](https://github.com/eurekaclinical/eurekaclinical-parent) as its parent pom. It has a fairly large dependencyManagement section with various dependencies that provide the following functionality:
* logging
* utility libraries
* delimited file handling
* JDBC drivers
* INI file handling
* email handling
* versions of standard APIs
* CAS client
* REST API creation
* dependency injection
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

## Additional configuration
Read the [eurekaclinical-parent](https://github.com/eurekaclinical/eurekaclinical-parent) project's README for instructions. The instructions for that project also apply to this one.

## Getting help
Feel free to contact us at help@eurekaclinical.org.
