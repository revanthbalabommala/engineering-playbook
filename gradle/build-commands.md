# Gradle Commands

## Build & Run
```bash
./gradlew clean openApiGenerate --info
./gradlew clean build --refresh-dependencies
./gradlew build -x test
./gradlew bootRun --rerun-tasks --args='--spring.profiles.active=local'

## Tasks
./gradlew tasks

## Dependencies
./gradlew dependencies

## Stop daemon
./gradlew --stop

## Version
./gradlew --version