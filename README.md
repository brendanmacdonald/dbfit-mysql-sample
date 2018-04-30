# README

These tests will run against a default installation of MySQL Server - this will contain a database called 'world' with a table called 'city'

# Execution
There are two ways to execute the tests.

## Via the command line
```
java -jar lib/fitnesse-20150424-standalone.jar -c "TestSuite?suite&format=text"
```

## Via the browser
```
./startFitnesse.bat
```
followed by opening
```
http://localhost:8085/TestSuite?suite
```