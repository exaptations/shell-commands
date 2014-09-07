Maven Commands

Skipping Tests
```
mvn -Dmaven.test.skip=true
```

Run a specific test method
```
mvn -Dtest=TestMavenCli#testMavenCli test
```

Dependency as graphml
```
mvn dependency:tree -Doutput=/path/to/file.graphml -DoutputType=graphml
```
