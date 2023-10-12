## Steps To Reproduce

1) run `./gradlew wrapper --gradle-version=8.4`
2) run `./gradlew clean build run` and confirm there's no warning from console
3) locate to `build.gradle` and uncomment L26
4) run `./gradlew clean build run` again, this time see the warning messages 
