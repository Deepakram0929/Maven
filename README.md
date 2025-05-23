| Command                  | Description                    |
| ------------------------ | ------------------------------ |
| `mvn archetype:generate` | Create new Maven project       |
| `mvn compile`            | Compile source code            |
| `mvn test`               | Run unit tests                 |
| `mvn package`            | Package compiled code as JAR   |
| `mvn clean`              | Clean generated files          |
| `mvn install`            | Install JAR into local repo    |
| `mvn dependency:tree`    | View project dependencies tree |


To create maven project --> 
mvn archetype:generate -DgroupId=com.example.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false


Source File Structure:

![image](https://github.com/user-attachments/assets/95dfb096-2804-4e1f-9bd2-212c1995a954)
