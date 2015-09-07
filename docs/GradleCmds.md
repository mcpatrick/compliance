# Commands (tasks) supported in the Gradle build script
----------------------

From the root directory:
- ./gradlew build: Runs the set of Java build tasks, including "assemble" which compiles and jars your code and "test"
- ./gradlew sourceJar: Creates a source jar
- ./gradlew javadocJar: Generates javadocs and jars them up.


A single project (and any projects which that project depends upon) may be run in one of two ways:
- From the root directory:  ./gradlew -p project_name task
- From the projects directory: ../gradlew task




