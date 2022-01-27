# idea-copy-resources
Test strange behaviour in IntelliJ IDEA 2021.3 (Ultimate Edition)

1. Clone the project into IDEA
2. Build the project - folder "a/target/classes" contains the file "text.xml"
3. Either via drag-n-drop or via "Refactor > Copy file", copy "a/src/main/resources/test.xml" into "b/src/main/resources"

Expected behaviour:
- folder "b/target/classes" should contain the file "text.xml"

Actual behaviour:
- folder "b/target/classes" is empty 
