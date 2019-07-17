# apache-spark-basic-java
Spark with Java basic example

Base reference from https://www.baeldung.com/apache-spark
Created a separate repo for easy usage and testing

## Steps
1. git clone and do mvn package
2. Tested with spark local mode in Windows
   Copy the jar and input file to your local directory where spark-shell was executed
spark-submit --class com.baeldung.WordCount --master local apache-spark-basic-java-1.0-SNAPSHOT.jar spark_example.txt
