#ph-parent-pom

Generic Maven 3 parent POM with lots of default configuration.
It is pre-configured to handle the "ph-" software stack in a suitable way.
By default it builds Java 1.6 applications but requires a JDK 1.7 to be used as certain plugins require JDK 1.7! 

The latest released version is **1.4.1**

To use it as your parent POM using the following snippet:
```xml
  <parent>
    <groupId>com.helger</groupId>
    <artifactId>parent-pom</artifactId>
    <version>1.4.1</version>
  </parent>
```

---

On Twitter: <a href="https://twitter.com/philiphelger">Follow @philiphelger</a>
