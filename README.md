for jacoco tests:
mvn clean install
report: target/site/jacoco

for pitest:
mvn test pitest:mutationCoverage
report: target/pit-reports
