# ph-parent-pom

[![Maven Central](https://img.shields.io/maven-central/v/com.helger/parent-pom)](https://img.shields.io/maven-central/v/com.helger/parent-pom)

Generic Maven 3 parent POM with lots of default configuration.
It is pre-configured to handle the "ph-" software stack in a suitable way.

The latest released version is **3.0.2** and requires JDK 17 or higher at build time.

* The latest version that uses JDK 11 as the baseline is **2.1.4**
* The latest version that uses JDK 8 as the baseline is **1.12.0**

To use it as your parent POM using the following snippet:

```xml
  <parent>
    <groupId>com.helger</groupId>
    <artifactId>parent-pom</artifactId>
    <version>3.0.2</version>
  </parent>
```

## News and noteworthy

v3.0.3 - work in progress
* Updated to dependency-check-maven 12.1.5
* Updated to maven-failsafe-plugin 3.5.4
* Updated to maven-compiler-plugin 3.14.1
* Updated to maven-javadoc-plugin 3.12.0
* Updated to maven-shade-plugin 3.6.1
* Updated to maven-surefire-plugin 3.5.4
* Updated to maven-surefire-report-plugin 3.5.4
* Updated to spotbugs-maven-plugin 4.9.6.0

v3.0.2 - 2025-09-08
* Commented out the JUnit 5 dependencies, as they interfere with Spring Boot applications and I don't use it anyway 
* Updated to ph-buildinfo-maven-plugin 5.0.0
* Updated to ph-csscompress-maven-plugin 8.0.0
* Updated to ph-jscompress-maven-plugin 3.1.0
* Updated to spotbugs-maven-plugin 4.9.4.2

v3.0.1 - 2025-08-22
* Updated to Jakarta servlet-api 6.0.0 (JakartaEE 10)
* Updated to Jakarta jsp-api 3.1.1 (JakartaEE 10)
* Updated to maven-bundle-plugin 6.0.0
* Updated to spotbugs-maven-plugin 4.9.4.0

v3.0.0 - 2025-08-19
* Moving the baseline to Java 17
* Updated to central-publishing-maven-plugin 0.8.0
* Updated to dependency-check-maven 12.1.3
* Updated to JUnit 5.13.4
* Updated to maven-clean-plugin 3.5.0
* Updated to maven-ear-plugin 3.4.0
* Updated to maven-enforcer-plugin 3.6.1
* Updated to maven-gpg-plugin 3.2.8
* Updated to maven-javadoc-plugin 3.11.3
* Updated to maven-pmd-plugin 3.27.0
* Updated to ph-csscompress-maven-plugin 7.0.5
* Updated to spotbugs-maven-plugin 4.9.3.2

v2.1.4 - 2025-05-13
* Added new predefined profile `release-snapshot` to be used for deploying SNAPSHOTs to Maven Central

v2.1.3 - 2025-05-13
* Moved plugin `central-publishing-maven-plugin` from build `plugins` into the `pluginManagement`

v2.1.2 - 2025-05-02
* Fixed version number of the `license-maven-plugin`

v2.1.1 - 2025-05-02
* Enabled `autoPublish` for the maven-cenntral-publishing-plugin

v2.1.0 - 2025-05-02
* Updated to create releaes via the Sonatype maven-cenntral-publishing-plugin
* Updated to dependency-check-maven 12.1.1
* Updated to forbiddenapis 3.9
* Updated to jacoco-maven-plugin 0.8.13
* Updated to JUnit 5.12.2
* Updated to license-maven-plugin 5.0
* Updated to maven-failsafe-plugin 3.5.3
* Updated to maven-surefire-plugin 3.5.3
* Updated to maven-surefire-report-plugin 3.5.3
* Updated to ph-jscompress-maven-plugin 3.0.2
* Updated to spotbugs-maven-plugin 4.9.3.0

v2.0.8 - 2025-03-03
* Reverted to maven-bundle-plugin 5.1.9 (v6 requires at least Java 17)

v2.0.7 - 2025-03-02
* Updated to dependency-check-maven 12.1.0
* Updated to jdepend-maven-plugin 2.1
* Updated to forbiddenapis 3.8
* Updated to JUnit 5.12.0
* Updated to license-maven-plugin 4.6
* Updated to maven-bundle-plugin 6.0.0
* Updated to maven-checkstyle-plugin 3.6.0
* Updated to maven-clean-plugin 3.4.1
* Updated to maven-compiler-plugin 3.14.0
* Updated to maven-dependency-plugin 3.8.1
* Updated to maven-deploy-plugin 3.1.4
* Updated to maven-failsafe-plugin 3.5.2
* Updated to maven-gpg-plugin 3.2.7
* Updated to maven-install-plugin 3.1.4
* Updated to maven-jarsigner-plugin 3.1.0
* Updated to maven-javadoc-plugin 3.11.2
* Updated to maven-jxr-plugin 3.6.0
* Updated to maven-plugin-plugin 3.15.1
* Updated to maven-pmd-plugin 3.26.0
* Updated to maven-project-info-reports-plugin 3.9.0
* Updated to maven-site-plugin 3.21.0
* Updated to maven-surefire-plugin 3.5.2
* Updated to maven-surefire-report-plugin 3.5.2
* Updated to taglist-maven-plugin 3.2.1
* Updated to ph-csscompress-maven-plugin 7.0.4
* Updated to SLF4J 2.0.17
* Updated to spotbugs-maven-plugin 4.9.1.0

v2.0.6 - 2024-08-09
* Updated to dependency-check-maven 10.0.3
* Updated to forbiddenapis 3.7
* Updated to jacoco-maven-plugin 0.8.12
* Updated to JUnit 5.10.3
* Updated to license-maven-plugin 4.5
* Updated to maven-assembly-plugin 3.7.1
* Updated to maven-checkstyle-plugin 3.4.0
* Updated to maven-clean-plugin 3.4.0
* Updated to maven-compiler-plugin 3.13.0
* Updated to maven-dependency-plugin 3.7.1
* Updated to maven-deploy-plugin 3.1.2
* Updated to maven-enforcer-plugin 3.5.0
* Updated to maven-failsafe-plugin 3.3.1
* Updated to maven-gpg-plugin 3.2.4
* Updated to maven-install-plugin 3.1.2
* Updated to maven-jar-plugin 3.4.2
* Updated to maven-javadoc-plugin 3.8.0
* Updated to maven-jxr-plugin 3.4.0
* Updated to maven-plugin-plugin 3.13.1
* Updated to maven-pmd-plugin 3.24.0
* Updated to maven-project-info-reports-plugin 3.6.2
* Updated to maven-release-plugin 3.1.1
* Updated to maven-shade-plugin 3.6.0
* Updated to maven-source-plugin 3.3.1
* Updated to maven-surefire-plugin 3.3.1
* Updated to maven-surefire-report-plugin 3.3.1
* Updated to ph-csscompress-maven-plugin 7.0.2
* Updated to SLF4J 2.0.15
* Updated to spotbugs-maven-plugin 4.8.6.2
* Updated to taglist-maven-plugin 3.1.0

v2.0.5 - 2023-11-15
* Updated to dependency-check-maven 8.4.3
* Updated to jacoco-maven-plugin 0.8.11
* Updated to forbiddenapis 3.6
* Updated to JUnit 5.10.1
* Updated to license-maven-plugin 4.3
* Updated to maven-checkstyle-plugin 3.3.1
* Updated to maven-clean-plugin 3.3.2
* Updated to maven-dependency-plugin 3.6.1
* Updated to maven-enforcer-plugin 3.4.1
* Updated to maven-failsafe-plugin 3.2.2
* Updated to maven-javadoc-plugin 3.6.2
* Updated to maven-jxr-plugin 3.3.1
* Updated to maven-plugin-plugin 3.10.2
* Updated to maven-pmd-plugin 3.21.2
* Updated to maven-shade-plugin 3.5.1
* Updated to maven-surefire-plugin 3.2.2
* Updated to maven-surefire-report-plugin 3.2.2
* Updated to ph-csscompress-maven-plugin 7.0.1
* Updated to SLF4J 2.0.9
* Updated to spotbugs-maven-plugin 4.8.1.0

v2.0.4 - 2023-07-01
* Enforcing JSP API 3.0.0 to be compliant with JakartaEE 9
* Updated to dependency-check-maven 8.3.1
* Updated to jacoco-maven-plugin 0.8.10
* Updated to JUnit 5.9.3
* Updated to maven-assembly-plugin 3.6.0
* Updated to maven-bundle-plugin 5.1.9
* Updated to maven-checkstyle-plugin 3.3.0
* Updated to maven-clean-plugin 3.3.1
* Updated to maven-dependency-plugin 3.6.0
* Updated to maven-failsafe-plugin 3.1.2
* Updated to maven-gpg-plugin 3.1.0
* Updated to maven-plugin-plugin 3.9.0
* Updated to maven-pmd-plugin 3.21.0
* Updated to maven-project-info-reports-plugin 3.4.5
* Updated to maven-release-plugin 3.0.1
* Updated to maven-shade-plugin 3.5.0
* Updated to maven-source-plugin 3.3.0
* Updated to maven-surefire-plugin 3.1.2
* Updated to maven-surefire-report-plugin 3.1.2
* Updated to maven-war-plugin 3.4.0
* Updated to ph-buildinfo-maven-plugin 4.0.1
* Updated to spotbugs-maven-plugin 4.7.3.5

v2.0.3 - 2023-04-13
* Improved license header configuration file
* Updated to forbiddenapis 3.5.1
* Updated to jacoco-maven-plugin 0.8.9
* Updated to maven-checkstyle-plugin 3.2.2
* Updated to maven-enforcer-plugin 3.3.0
* Updated to maven-plugin-plugin 3.8.2
* Updated to maven-project-info-reports-plugin 3.4.3
* Updated to spotbugs-maven-plugin 4.7.3.4

v2.0.2 - 2023-03-30
* Updated the configuration of the license-maven-plugin
* Updated to SLF4J 2.0.7
* Updated to dependency-check-maven 8.2.1
* Updated to forbiddenapis 3.5
* Updated to license-maven-plugin 4.2
* Updated to maven-compiler-plugin 3.11.0
* Updated to maven-deploy-plugin 3.1.1
* Updated to maven-failsafe-plugin 3.0.0
* Updated to maven-install-plugin 3.1.1
* Updated to maven-plugin-plugin 3.8.1
* Updated to maven-release-plugin 3.0.0
* Updated to maven-resources-plugin 3.3.1
* Updated to maven-surefire-plugin 3.0.0
* Updated to maven-surefire-report-plugin 3.0.0
* Updated to ph-jscompress-maven-plugin 3.0.1
* Updated to spotbugs-maven-plugin 4.7.3.3

v2.0.1 - 2023-02-24
* Removed the SLF4J log4j12 artefact
* Removed the maven-cobertura-plugin - use jacoco instead
* Reverted to jakarta.servlet-api 5.0.0
* Updated to jakarta.servlet.jsp-api 3.1.1
* Updated to JUnit 5.9.2
* Updated to SLF4J 2.0.6
* Updated to dependency-check-maven 8.1.0
* Updated to forbiddenapis 3.4
* Updated to maven-assembly-plugin 3.5.0
* Updated to maven-checkstyle-plugin 3.2.1
* Updated to maven-dependency-plugin 3.5.0
* Updated to maven-deploy-plugin 3.1.0
* Updated to maven-ear-plugin 3.3.0
* Updated to maven-enforcer-plugin 3.2.1
* Updated to maven-install-plugin 3.1.0
* Updated to maven-jar-plugin 3.3.0
* Updated to maven-javadoc-plugin 3.5.0
* Updated to maven-plugin-plugin 3.7.1
* Updated to maven-pmd-plugin 3.20.0
* Updated to maven-shade-plugin 3.4.1
* Updated to ph-buildinfo-maven-plugin 4.0.0
* Updated to ph-csscompress-maven-plugin 7.0.0
* Updated to ph-dirindex-maven-plugin 4.0.0
* Updated to ph-jscompress-maven-plugin 3.0.0
* Updated to maven-project-info-reports-plugin 3.4.2
* Updated to spotbugs-maven-plugin 4.7.3.1

v2.0.0 - 2022-09-05
* Note: this POM version requires at least Maven 3.8.2 to build sites, because that versions updates JAnsi to 2.x which is a prerequisite for some plugins to work - see https://blogs.apache.org/maven/entry/apache-maven-3-8-2
* First version for default JDK 11 builds
* Moved the configuration of the `maven-javadoc-plugin` from `reporting` to `build` to work
* Removed the `org.eclipse.m2e:lifecycle-mapping` configuration
* Updated to jakarta.servlet-api 6.0.0
* Updated to jakarta.servlet.jsp-api 3.1.0
* Updated to JUnit 5.9.0
* Updated to SLF4J 2.0.0
* Updated to dependency-check-maven 7.1.2
* Updated to maven-assembly-plugin 3.4.2
* Updated to maven-bundle-plugin 5.1.8
* Updated to maven-checkstyle-plugin 3.2.0
* Updated to maven-deploy-plugin 3.0.0
* Updated to maven-install-plugin 3.0.1
* Updated to maven-javadoc-plugin 3.4.1
* Updated to maven-jxr-plugin 3.3.0
* Updated to maven-pmd-plugin 3.18.0
* Updated to maven-project-info-reports-plugin 3.4.1
* Updated to maven-rar-plugin 3.0.0
* Updated to maven-resources-plugin 3.3.0
* Updated to maven-site-plugin 3.12.1
* Updated to spotbugs-maven-plugin 4.7.1.1

v1.12.0 - 2025-10-01
* Backport for Maven Central releases

v1.11.5 - 2022-06-20
* Updated to dependency-check-maven 7.1.1
* Updated to forbiddenapis 3.3
* Updated to jacoco-maven-plugin 0.8.8
* Updated to JUnit 5.8.2
* Updated to maven-antrun-plugin 3.1.0
* Updated to maven-bundle-plugin 5.1.6
* Updated to maven-clean-plugin 3.2.0
* Updated to maven-compiler-plugin 3.10.1
* Updated to maven-dependency-plugin 3.3.0
* Updated to maven-ejb-plugin 3.2.1
* Updated to maven-enforcer-plugin 3.1.0
* Updated to maven-jar-plugin 3.2.2
* Updated to maven-javadoc-plugin 3.4.0
* Updated to maven-jxr-plugin 3.2.0
* Updated to maven-plugin-plugin 3.6.4
* Updated to maven-pmd-plugin 3.17.0
* Updated to maven-project-info-reports-plugin 3.3.0
* Updated to maven-shade-plugin 3.3.0
* Updated to maven-site-plugin 3.12.0
* Updated to ph-csscompress-maven-plugin 6.5.0
* Updated to SLF4J API 1.7.36
* Updated to spotbugs-maven-plugin 4.7.0.0
* Updated to taglist-maven-plugin 3.0.0
* Using `SLASHSTAR_STYLE` instead of `JAVADOC_STYLE` for `.jav`, `.jj` and `.jjt` based on https://github.com/hazendaz/license-maven-plugin/commit/c387c1865176e0d66e425ad9dddaa346e6a72a04
* Removed the default license mapping for `.xq` files because it is invalid

v1.11.4 - 2021-09-19
* Updated to apiguardian-api 1.1.2
* Updated to dependency-check-maven 6.3.1
* Updated to forbiddenapis 3.2
* Updated to jacoco-maven-plugin 0.8.7
* Updated to JUnit 4.13.2
* Updated to JUnit 5.8.0
* Updated to license-maven-plugin 4.1
* Updated to maven-bundle-plugin 5.1.2
* Updated to maven-checkstyle-plugin 3.1.2
* Updated to maven-dependency-plugin 3.2.0
* Updated to maven-enforcer-plugin 3.0.0
* Updated to maven-gpg-plugin 3.0.1
* Updated to maven-javadoc-plugin 3.3.1
* Updated to maven-jxr-plugin 3.1.1
* Updated to maven-plugin-plugin 3.6.1
* Updated to maven-pmd-plugin 3.15.0
* Updated to maven-project-info-reports-plugin 3.1.2
* Updated to maven-war-plugin 3.3.2
* Updated to ph-buildinfo-maven-plugin 3.0.2
* Updated to ph-csscompress-maven-plugin 6.3.4
* Updated to SLF4J API 1.7.32
* Updated to spotbugs-maven-plugin 4.3.0
* Removed ph-dirindex-maven-plugin 
* Improved the list of file extensions for license formatting

v1.11.3 - 2021-01-04
* Updated to apiguardian-api 1.1.1
* Updated to dependency-check-maven 6.0.4
* Updated to forbiddenapis 3.1
* Updated to jacoco-maven-plugin 0.8.6
* Updated to jakarta.servlet-api 5.0.0
* Updated to JUnit 4.13.1
* Updated to JUnit 5.7.0
* Updated to maven-ear-plugin 3.2.0
* Updated to maven-pmd-plugin 3.14.0
* Updated to maven-project-info-reports-plugin 3.1.1
* Updated to maven-resources-plugin 3.2.0
* Updated to spotbugs-maven-plugin 4.2.0
* Removed the predefined version for `javax.servlet:javax.servlet-api`
* Removed the predefined version for `javax.servlet.jsp:javax.servlet.jsp-api`

v1.11.2 - 2020-07-15
* Updated to dependency-check-maven 5.3.2
* Updated to forbiddenapis 3.0.1
* Updated to jakarta.servlet-api 4.0.4
* Updated to JUnit 5.6.2
* Updated to maven-antrun-plugin 3.0.0
* Updated to maven-assembly-plugin 3.3.0
* Updated to maven-bundle-plugin 5.1.1
* Updated to maven-dependency-plugin 3.1.2
* Updated to maven-ejb-plugin 3.1.0
* Updated to maven-project-info-reports-plugin 3.1.0
* Updated to maven-javadoc-plugin 3.2.0
* Updated to maven-shade-plugin 3.2.4
* Updated to maven-site-plugin 3.9.1
* Updated to maven-war-plugin 3.3.1
* Updated to ph-csscompress-maven-plugin 6.2.3
* Updated to spotbugs-maven-plugin 4.0.4

v1.11.1 - 2020-03-11
* Updated to dependency-check-maven 5.3.1
* Updated to JUnit 4.13
* Updated to JUnit 5.6.0
* Updated to maven-checkstyle-plugin 3.1.1
* Updated to maven-ear-plugin 3.0.2
* Updated to maven-pmd-plugin 3.13.0
* Updated to maven-shade-plugin 3.2.2
* Updated to maven-site-plugin 3.9.0
* Updated to maven-source-plugin 4.2.1
* Updated to ph-buildinfo-maven-plugin 3.0.1
* Updated to ph-csscompress-maven-plugin 6.2.1
* Updated to ph-dirindex-maven-plugin 3.0.2
* Updated to ph-jscompress-maven-plugin 2.2.3
* Updated to spotbugs-maven-plugin 3.1.12.2
* Updated to SLF4J API 1.7.30

v1.11.0 - 2019-11-07
* Updated to JUnit 5.5.2
* Updated to SLF4J API 1.7.29
* Updated to dependency-check-maven 5.2.2
* Updated to forbiddenapis 2.7
* Updated to jacoco-maven-plugin 0.8.5
* Updated to maven-assembly-plugin 3.2.0
* Updated to maven-bundle-plugin 4.2.1
* Updated to maven-jar-plugin 3.2.0
* Updated to maven-site-plugin 3.8.2
* Updated to maven-source-plugin 3.2.0
* Added managed version for `jakarta.servlet:jakarta.servlet-api`
* Added managed version for `jakarta.servlet.jsp:jakarta.servlet.jsp-api`
* Replaced `org.codehaus.mojo:findbugs-maven-plugin` with `com.github.spotbugs:spotbugs-maven-plugin`

v1.10.9 - 2019-07-17
* Updated to JUnit 5.5.0
* Updated to SLF4J API 1.7.26
* Updated to APIGuardian API to 1.1.0
* Updated to maven-bundle-plugin 4.2.0
* Updated to maven-checkstyle-plugin 3.1.0
* Updated to maven-compiler-plugin 3.8.1
* Updated to maven-javadoc-plugin 3.1.1
* Updated to maven-jar-plugin 3.1.2
* Updated to maven-jdeps-plugin 3.1.2
* Updated to maven-pmd-plugin 3.12.0 
* Updated to maven-source-plugin 3.1.0
* Updated to maven-surefire-plugin 2.22.2
* Updated to maven-war-plugin 3.2.3
* Updated to jacoco-maven-plugin 0.8.4
* Updated to ph-csscompress-maven-plugin 6.2.0
* Updated to ph-dirindex-maven-plugin 3.0.1
* Updated to ph-jscompress-maven-plugin 2.2.2
* Removed the UML Doclet because it conflicts with certain outputs
* Added `org.owasp:dependency-check-maven` reporting plugin

v1.10.8 - 2019-02-03
* Improved license formatting configuration
* Updated to JaCoCo 0.8.3
* Updated to JUnit 5.3.2
* Updated to maven-assembly-plugin 3.1.1
* Updated to maven-jar-plugin 3.1.1
* Updated to maven-jarsigner-plugin 3.0.0
* Updated to maven-plugin-plugin 3.6.0
* Updated to maven-pmd-plugin 3.11.0
* Updated to maven-shade-plugin 3.2.1

v1.10.7 - 2018-10-23
* Plugin version updates
* Fixed `maven-project-info-reports-plugin` v3 configuration
* Updated to maven-bundle-plugin 4.1.0

v1.10.6 - 2018-10-01
* Updated to JUnit5 5.3.1
* Updated to maven-bundle-plugin 4.0.0
* Plugin version updates

v1.10.5 - 2018-08-06
* Plugin version updates

v1.10.4 - 2018-08-06
* Plugin version updates

v1.10.3 - 2018-03-23
* Plugin version updates
* Restored default JUnit 4 behaviour of surefire

v1.10.2 - 2018-03-07
* Plugin version updates
* Fixed an error of Java9 auto select (whysoever)

v1.10.1 - 2018-02-27
* Plugin version updates
* Updated to JUnit 5.1
* Improved JDK 9 support

v1.10.0 - 2018-01-28

* version updates
* Started adding support for JUnit 5
* Removed `<prerequisite>` element from POM

v1.9.3 - 2017-04-12

* version updates

v1.9.2 - 2016-11-03

version updates
* Improved site generation

v1.9.1 - 2016-07-12

version updates
* Added m2e mapping for maven-antrun-plugin

v1.9.0 - 2016-06-26

version updates
* Removed mandatory JUnit 4 dependency

v1.8.4 - 2016-05-27

v1.8.3 - 2016-05-25

v1.8.2 - 2016-05-10

v1.8.1 - 2016-05-03

v1.8.0 - 2016-02-01
* First version for default JDK 8 builds

v1.4.2 - 2015-12-02
* Changed default build version to Java 1.7

v1.4.1 - 2015-08-31
* Last version that uses Java 1.6 as the default target  

## Hints

* v1.9.3 or higher: when having errors with `maven-assembly-plugin`: change goal from `attached` to `single`
* When building with Eclipse and you get an m2e error with "Manifest.write(...)" than have a look at https://github.com/tesla/m2eclipse-mavenarchiver/issues/9
* The latest release for building with JDK 6 is *1.4.1* (requires a JDK 7 at compile time).

---

My personal [Coding Styleguide](https://github.com/phax/meta/blob/master/CodingStyleguide.md) |
It is appreciated if you star the GitHub project if you like it.