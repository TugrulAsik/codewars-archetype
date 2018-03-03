# codewars-archetype
Simple maven archetype for Codewars katas

Prerequisites
-------------

- JDK 8
- Maven 3

Create a project
----------------

```bash
    mvn archetype:generate \
        -DarchetypeGroupId=com.tugrul \
        -DarchetypeArtifactId=codewars \
        -DarchetypeVersion=1.0.0 \
        -DgroupId=my.groupid \
        -DartifactId=my-artifactId \
        -Dversion=version \
        -DarchetypeRepository=https://github.com/TugrulAsik/codewars-archetype
```
