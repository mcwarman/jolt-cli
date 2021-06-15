# JOLT Cli

Simple build gradle to create package for jolt cli.

```shell
gradle clean install
cd ./build/distribution
java -jar ./lib/jolt-cli.jar transform ./shift.json ./data.json
````
