# ReportISW2-ModuloSWTesting
## BOOKKEEPER
Per eseguire i test con i report di JaCoCo utilizzare il comando: **mvn test jacoco:prepare-agent jacoco:report**.
Per eseguire i test con di Mutation Coverage di Pit utilizzare il comando: **mvn org.pitest:pitest-maven:mutationCoverage**.

## ZOOKEEPER
Per eseguire i test con i report di JaCoCo utilizzare il comando: **mvn test jacoco:prepare-agent jacoco:report -DCoverage=true**.
Per eseguire i test con di Mutation Coverage di Pit utilizzare il comando: **mvn org.pitest:pitest-maven:mutationCoverage**.

## JCS
Eseguire il comando: **mvn install dependency:copy-dependencies org.jacoco:jacoco-maven-plugin:prepare-agent**;
Eseguire, poi, il file _report.sh_.


