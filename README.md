# maven-install-local-jar
use the maven command to install local jar files which are not existing on the maven center repository.

## Command
```
mvn install:install-file  -DgroupId=your-group-id -DartifactId=your-artifact-id -Dpackaging=jar -Dversion=your-version-number -Dfile="jar file absolutely path"
```
