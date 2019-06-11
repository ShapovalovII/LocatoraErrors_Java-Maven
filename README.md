* Run test

```bash
mvn -Dtest=SmartLocatorNotInDatabase test
mvn -Dtest=InitialLocatorWithInvalidTAName test
mvn -Dtest=SmartLocatorInDatabase test
mvn -Dtest=TALocatorWithInvalidInitialLocator test
mvn -Dtest=InitialLocatorNotExistOnUsePage test

```