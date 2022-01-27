# ReportISW2-ModuloSWTesting
## BOOKKEEPER
Per eseguire i test con i report di JaCoCo utilizzare il comando: _mvn test jacoco:prepare-agent jacoco:report_.

Per eseguire i test di Mutation Coverage di Pit utilizzare il comando: _mvn org.pitest:pitest-maven:mutationCoverage_.

## ZOOKEEPER
Per eseguire i test con i report di JaCoCo utilizzare il comando: _mvn test jacoco:prepare-agent jacoco:report -DCoverage=true_.

Per eseguire i test di Mutation Coverage di Pit utilizzare il comando: _mvn org.pitest:pitest-maven:mutationCoverage_.

## JCS
Eseguire il comando: _mvn install dependency:copy-dependencies org.jacoco:jacoco-maven-plugin:prepare-agent_;

Eseguire, poi, il file _report.sh_.


