Simple project demonstrating how Lombok can generate boiler plate Java code. There is a single java 
user class com.shiffler.lomboktester.User. The user class is only 16 lines long but the effective .java file created by 
Lombok is around 150 lines. The following lombok annotations are demonstrated: 
<br>
@Data
<br>
@AllArgsConstructor
<br>
@NoArgsConstructor
<br>
@Builder
<br><br>
The impacts of these annotations can be observed by looking at User.class under target/classes/com/shiffler/lomboktester/User.class <br>
IntelliJ is able to decompile the byte code so it can be read as text. The pom.xml also contains an example of how to force maven to clean 
the project during the initialize phase of every build cycle.


