# Commands (tasks) supported in the Gradle build script
----------------------

Tasks (running them from the root directory):
- ./gradlew build: Runs the set of Java build tasks, including "assemble" which compiles and jars your code and "test"
- ./gradlew serverTest: Runs tests defined in cts-java.  Requires a running server.
- ./gradlew sourceJar: Creates a source jar
- ./gradlew javadocJar: Generates javadocs and jars them up.
- ./gradlew createDists: Runs two subtasks, zipCli and zipServer, to create the corresponding distribution zip files.


A single project (and any projects which that project depends upon) may be run in one of two ways:
- From the root directory:  ./gradlew -p project_name task
- From the projects directory: ../gradlew task




