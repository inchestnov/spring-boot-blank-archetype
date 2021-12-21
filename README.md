# Archetype for blank Spring Boot project

## How to use

1. Clone project from git
```text
git clone https://github.com/inchestnov/spring-boot-blank-archetype
```
2. Install archetype to .m2:
```text
cd spring-boot-blank-archetype
mvn install
```
3. Generate project 
```text
cd /path-to-directory-with-new-project
mvn archetype:generate \
  -DarchetypeGroupId=chestnov \
  -DarchetypeArtifactId=spring-boot-blank-archetype \
  -DarchetypeVersion=1.0.0-SNAPSHOT \
  -DartifactId=test-project \
  -Dpackage=com.company.test \
  -DinteractiveMode=false
```

Maven will generate a project with specified artifactId and package.
GroupId has default as *chestnov* and version has default as *1.0.0-SNAPSHOT* (but it is possible to configure it via command).