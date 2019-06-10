* Run test

```bash
mvn -Dtest=SmartLocatorNotInDatabase test
mvn -Dtest=InitialLocatorInvalidWithXpath test
mvn -Dtest=SmartLocatorInDatabase test
mvn -Dtest=InitialLocatorWithInvalidXpath test
mvn -Dtest=InitialLocatorNotExistOnUsePage test

```