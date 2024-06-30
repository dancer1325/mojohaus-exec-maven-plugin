## How has it been created?
* `mvn archetype:generate -DgroupId=com.example -DartifactId=example-project -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false`

## How to run?
* `mvn clean compile`
* `mvn exec:exec -Dexec.executable="java" -Dexec.args="-cp %classpath com.example.App"`
  * `%classpath` is evaluated