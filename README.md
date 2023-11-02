# Structuring Software Projects Sample
Demo for GHA_Gradle_Template


| Name          | Value                                            |
|:--------------|--------------------------------------------------|
| Documentation | [Structuring Software Projects Sample](https://docs.gradle.org/current/samples/sample_structuring_software_projects.html)|
| gradle-version |  8.4 |
| Kotlin          |  https://docs.gradle.org/current/samples/zips/sample_structuring_software_projects-kotlin-dsl.zip |
| Groovy        | https://docs.gradle.org/current/samples/zips/sample_structuring_software_projects-groovy-dsl.zip | 



NOTE: You can open this sample inside an IDE using the [IntelliJ's Gradle import](https://www.jetbrains.com/help/idea/gradle.html#gradle_import_project_start) or [Eclipse Buildship](https://projects.eclipse.org/projects/tools.buildship).

This sample shows how to structure a software product that consists of multiple components as a set of connected Gradle builds.
As such, it shows how Gradle is used to model a project's architecture and reflect that in the physical structure of the files that make up the software.
This example is described as part of the link:{userManualPath}/structuring_software_products.html[documentation on this topic].

The product that is built in this sample is an application that displays [Gradle Build Tool releases](https://gradle.org/releases/).

There are different ways to work with the sample:

- You may build or import the umbrella build in the root.
  There you can, for example, run the Spring Boot web application via `./gradlew :server-application:app:bootRun` or install the Android app using `./gradlew :android-app:app:installDebug`.
- You may only build or import one of the application builds directly.
  For example, `cd server-application` and run the app using  `../gradlew :app:bootRun`.
- You may only build or import a selected component (and its dependencies).
  For example, only import the `user-feature` build in the IDE.

*TODO*:Finalize Upload Removal - Issue #21439
