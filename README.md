# maven-install-local-jar
use the maven command to install local jar files which are not existing on the maven center repository.

## Command
```
mvn install:install-file  -DgroupId=your-group-id -DartifactId=your-artifact-id -Dpackaging=jar -Dversion=your-version-number -Dfile="jar file absolutely path"
```

## Example
```
mvn install:install-file  -DgroupId=net.sourceforge.jgeocoder -DartifactId=jgeocoder -Dpackaging=jar -Dversion=0.5 -Dfile="C:\Users\sgyyz\Downloads\jgeocoder-0.5-jar-with-dependencies.jar"
```

## Note
Please ensure that the `Dfile` path without space.
