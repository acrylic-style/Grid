Paper [![Build Status](https://ci.acrylicstyle.xyz/job/Paper-1.16/badge/icon)](https://ci.acrylicstyle.xyz/job/Paper-1.16/)
===========

High performance Paper fork that aims to fix bugs, gameplay and mechanics inconsistencies.

How To (Server Admins)
------
Powergrid is a jar file that you can download and run just like a normal jar file.

Download Grid from our [downloads page](https://ci.acrylicstyle.xyz/job/Paper-1.16/).

Run the Paperclip jar directly from your server. Just like old times

  * Documentation on using Paper: [paper.readthedocs.io](https://paper.readthedocs.io/)
  * For a sneak peak on upcoming features, [see here](https://github.com/PaperMC/Paper/projects)

How To (Plugin Developers)
------
 * See our API patches [here](Spigot-API-Patches)
 * See upcoming, pending, and recently added API [here](https://github.com/PaperMC/Paper/projects/6)
 * Paper API javadocs here: [papermc.io/javadocs](https://papermc.io/javadocs/)
 * Maven Repo (for paper-api):
```xml
<repository>
    <id>grid</id>
    <url>https://repo.acrylicstyle.xyz/</url>
</repository>
```
 * Artifact Information:
```xml
<dependency>
    <groupId>xyz.acrylicstyle.grid</groupId>
    <artifactId>grid-api</artifactId>
    <version>1.16.1-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
 ```

**Or alternatively, with Gradle:**

 * Repository:
```groovy
repositories {
    maven {
        url 'https://repo.acrylicstyle.xyz/'
    }
}
```
 * Artifact:
```groovy
dependencies {
    compileOnly 'xyz.acrylicstyle.grid:grid-api:1.16.1-R0.1-SNAPSHOT'
}
```

How To (Compiling Jar From Source)
------
To compile Paper, you need JDK 8, maven, and an internet connection.

Clone this repo, run `./paper jar` from *bash*, get files.

How To (Pull Request)
------
See [Contributing](CONTRIBUTING.md)

Special Thanks To:
-------------

![YourKit-Logo](https://www.yourkit.com/images/yklogo.png)

[YourKit](https://www.yourkit.com/), makers of the outstanding java profiler, support open source projects of all kinds with their full featured [Java](https://www.yourkit.com/java/profiler/index.jsp) and [.NET](https://www.yourkit.com/.net/profiler/index.jsp) application profilers. We thank them for granting Paper an OSS license so that we can make our software the best it can be.
