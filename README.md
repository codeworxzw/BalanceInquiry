## jPOS Template

Clone this project in order to create your own jPOS based application.

We recommend that you install [Gradle](http://gradle.org/) in order to build your jPOS projects, but if you don't have it installed, you can use the Gradle wrapper scripts `gradlew` and `gradlew.bat`. In the following instructions, when we say `gradle` we really mean either your installed Gradle or one of the wrapper scripts (depending if you are on Unix or DOS based platforms).

### Build an eclipse project
````
gradle eclipse
````

### Build an IDEA project
````
gradle idea
````

### Build your own jar
````
gradle jar
````

### Check the jPOS version
````
gradle version
````

### Create a distribution of your application
````
gradle dist
````
This creates a tar gzipped file in the `build/distributions` directory.

### Create the runtime directory
````
gradle runtime
````
Creates a directory `runtime` with everything you need to run jPOS. Once the directory is created, you can `cd runtime` and call `java -jar your-project-version.jar` or the `bin/q2` script available in the `bin` directory.

### Generate an install a Maven artifact
````
gradle install
````

### List available Gradle tasks
```
gradle tasks
````
