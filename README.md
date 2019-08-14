# EvoSuite

[JDK](https://www.oracle.com/technetwork/java/javase/downloads/index.html)

Add Path `C:\Program Files\Java\jdk-12.0.2\bin`

Add JAVA_HOME `C:\Program Files\Java\jdk-12.0.2\`

`javac -version`

Add Path [Maven](https://maven.apache.org/) `~\apache-maven-3.6.1\bin`

`mvn compile`

`option 6 is no longer supported. Use 7 or later.`

```
<properties>
    <maven.compiler.source>1.7</maven.compiler.source>
    <maven.compiler.target>1.7</maven.compiler.target>
  </properties>
```

`java.lang.RuntimeException: Did not manage to automatically find tools.jar. Use -Dtools_jar_location=<path> property` => Removed since Java 9

Download `tools.jar`, 

Use older JDK

[EvoSuite](http://www.evosuite.org/documentation/tutorial-part-1/)

