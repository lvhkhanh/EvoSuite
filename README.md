# EvoSuite

Build:

* [Choco](https://chocolatey.org/docs/installation)

`@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"`

* [Git](https://gitforwindows.org/)

```
choco install git
refreshenv
```

* [Maven](https://maven.apache.org/)

```
choco install maven
refreshenv
```

* [wget]()
```
choco install wget -y
refreshenv
```
* [unzip]()
```
choco install unzip -y
refreshenv
```

* [JDK](https://www.oracle.com/technetwork/java/javase/downloads/index.html)

```
choco install jdk8
refreshenv
```

Add Path `C:\Program Files\Java\jdk-12.0.2\bin`

Add JAVA_HOME `C:\Program Files\Java\jdk-12.0.2\`

```
echo %JAVA_HOME%
```

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
* [Code-based test generation](http://mit.bme.hu/~micskeiz/pages/code_based_test_generation.html#TH08)
* [Evaluating code-based test-generator tools](https://www.slideshare.net/micskeiz/evaluating-codebased-testgenerator-tools)
* [Symbolic Execution-based Test Tool Evaluator (SETTE)](https://github.com/SETTE-Testing/sette-tool/wiki)
* [Survey on Automatic Test Data Generation Tools and Techniques for Object Oriented Code](https://bvucoepune.edu.in/wp-content/uploads/2018/BVUCOEP-DATA/Research_Publications/2015_16/42.pdf)
* [Automated Software Test Generation: Some Challenges, Solutions, and Recent Advances](https://patricegodefroid.github.io/public_psfiles/lncs10000-2018.pdf)
* [Mutation Testing in .NET, part 2](https://medium.com/comparethemarket/mutation-testing-in-net-part-2-590cca87f2e6)
* [Fettle](https://github.com/ComparetheMarket/fettle)
* [Paket](https://github.com/fsprojects/Paket), [NuGet]()
* [xUnit](https://xunit.net/), [NUnit](https://github.com/nunit/)
* [Roslyn](https://github.com/dotnet/roslyn)
