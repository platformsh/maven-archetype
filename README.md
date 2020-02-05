# Platform.sh Archetypes

In short, Archetype is a Maven project templating toolkit. An archetype is defined as an original pattern or model from which all other things of the same kind are made. The name fits as we are trying to provide a system that provides a consistent means of generating Maven projects.

This project contains several Maven archetypes to create Platform.sh projects.

## Payara

`mvn archetype:generate -DarchetypeGroupId=sh.platform.archetype   -DarchetypeArtifactId=payara  -DarchetypeVersion=0.0.1  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`
