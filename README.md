# codewars-archetype
Simple maven archetype for Codewars katas

Prerequisites
-------------

- JDK 8
- Maven 3

Create a project
----------------

### Manually Install
```bash
git clone https://github.com/TugrulAsik/codewars-archetype.git
mvn clean install
```

### Generate

```bash
    mvn archetype:generate \
        -DarchetypeGroupId=com.tugrul \
        -DarchetypeArtifactId=codewars-archetype \
        -DarchetypeVersion=1.0.0 \
        -DgroupId={your.groupId} \
        -DartifactId={your.artifactId} \
        -Dversion={your.version} \
        -DarchetypeRepository=https://github.com/TugrulAsik/codewars-archetype
```
