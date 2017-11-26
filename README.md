# java-scala-maven-bootstrap

## Build
mvn clean package

## Java run
java -cp target/bootstrap-1.0-SNAPSHOT.jar com.seungjoon.data.HelloJavaWorld

## Scala run
scala -classpath target/bootstrap-1.0-SNAPSHOT.jar com.seungjoon.data.HelloScalaWorld

## Spark Sample
spark-submit --class com.seungjoon.data.SparkPi target/bootstrap-1.0-SNAPSHOT.jar 3
