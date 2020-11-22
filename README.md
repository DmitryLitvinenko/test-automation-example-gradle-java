TBD

##Technologies:
Java15, Gradle, Selenide, Junit5, Allure, ...

##Run tests with gradle:
#####Run all tests:
```
    gradle clean test // gradle need to be installed, for example with brew
    ./gradlew clean test //not required installed gradle
```
``
note: ./gradlew indicates you are using a gradle wrapper, without wrapper you would need to install it manually,
 for example with brew and use gradle
``
* Run specific test:

        -> ./gradlew test --tests *ExampleTest.negativeTest
        
##Official documentation:
* Allure with Gradle doc:
https://plugins.gradle.org/plugin/io.qameta.allure
https://github.com/allure-framework/allure-gradle
* JUnit5 user guide: 
https://junit.org/junit5/docs/snapshot/user-guide/    
* Gradle Java plugin
https://docs.gradle.org/current/userguide/java_plugin.html       
* Gradle Java testing 
https://docs.gradle.org/current/userguide/java_testing.html#test_filtering
##Additional info:

* Upgrade Gradle wrapper:
```
    gradle wrapper --gradle-version 6.7.1
```