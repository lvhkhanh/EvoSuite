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

`java.lang.IllegalArgumentException: Could not find class [tutorial.Stack_ESTest]` => copy classes from evosuit-tests/tutorial  to target/classes/tutorial ![](https://snag.gy/Lvh3UT.jpg)

[Microsoft Code Digger](https://marketplace.visualstudio.com/items?itemName=RiSEResearchinSoftwareEngineering.MicrosoftCodeDigger&ssr=false#overview)

![](https://snag.gy/Rw4Es6.jpg)

![](https://snag.gy/xX6pL2.jpg)

Refs
* [EvoSuite](http://www.evosuite.org/documentation/tutorial-part-1/)
* [CREATE YOUR OWN CLR PROFILER IN C#](http://topholt.com/c-clr-profiler/)
* [.NET Internals: The Profiling API](http://www.blong.com/conferences/dcon2003/internals/profiling.htm)
* [Is is possible to use Profiling API right from C#?](https://stackoverflow.com/questions/5736845/is-is-possible-to-use-profiling-api-right-from-c)

