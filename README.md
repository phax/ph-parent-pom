#ph-parent-pom

Generic Maven 3 parent POM with lots of default configuration.
It is pre-configured to handle the "ph-" software stack in a suitable way.

The latest released version is **1.9.0** and requires Maven 3.2.6 or higher and JDK 8!

The latest release for building JDK 6 applications is *1.4.1* (requires a JDK 7 at compile time).

To use it as your parent POM using the following snippet:
```xml
  <parent>
    <groupId>com.helger</groupId>
    <artifactId>parent-pom</artifactId>
    <version>1.9.0</version>
  </parent>
```

## News and noteworthy

  * 1.9.0: version updates; removed mandatory JUnit 4 dependency
  
## Hints

  * When building with Eclipse and you get an m2e error with "Manifest.write(...)" than have a look at https://github.com/tesla/m2eclipse-mavenarchiver/issues/9

---

My personal [Coding Styleguide](https://github.com/phax/meta/blob/master/CodeingStyleguide.md) |
On Twitter: <a href="https://twitter.com/philiphelger">@philiphelger</a>
