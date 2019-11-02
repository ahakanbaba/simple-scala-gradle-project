
# Simple Scala Gradle Project

In this project we build a simple scala application using gradle


## Compile

```
./gradlew build
```

## Run

```
scala -cp build/libs/simple-scala-gradle-project.jar  example.Main
```

Note: The scala interpreter needs to have the same version as the scala version
mentioned in the build.gradle file

## Test

```
./gradlew test
```
