#ph-parent-pom

Generic Maven 3 parent POM with lots of default configuration.
It is pre-configured to handle the "ph-" software stack in a suitable way.

The latest released version is **1.9.2** and requires Maven 3.2.6 or higher and JDK 8 at build time (even though you may create Java 1.6 or 1.7 versions with it)!

The latest release for building JDK 6 applications is *1.4.1* (requires a JDK 7 at compile time).

To use it as your parent POM using the following snippet:
```xml
  <parent>
    <groupId>com.helger</groupId>
    <artifactId>parent-pom</artifactId>
    <version>1.9.2</version>
  </parent>
```

## News and noteworthy

  * 1.9.3
    * Version updates
  * 1.9.2 - 2016-11-03
    * Version updates
    * Improved site generation
  * 1.9.1 - 2016-07-12
    * Version updates
    * Added m2e mapping for maven-antrun-plugin
  * 1.9.0 - 2016-06-26
    * Version updates
    * Removed mandatory JUnit 4 dependency
 * 1.8.4 - 2016-05-27
 * 1.8.3 - 2016-05-25
 * 1.8.2 - 2016-05-10
 * 1.8.1 - 2016-05-03
 * 1.8.0 - 2016-02-01
   * First version for default JDK 8 builds
 * 1.4.2 - 2015-12-02
   * Changed default build version to Java 1.7
 * 1.4.1 - 2015-08-31
   * Last version that uses Java 1.6 as the default target  
    
  
## Hints

  * When building with Eclipse and you get an m2e error with "Manifest.write(...)" than have a look at https://github.com/tesla/m2eclipse-mavenarchiver/issues/9

---

My personal [Coding Styleguide](https://github.com/phax/meta/blob/master/CodeingStyleguide.md) |
On Twitter: <a href="https://twitter.com/philiphelger">@philiphelger</a>
