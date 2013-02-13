This project creates a standalone, portable, Groovy script launcher, which you can bunlde with your Groovy script. It will let anyone run the Groovy script if they have Java, even if they have not installed Groovy.

It was inspired by http://www.weheartcode.com/2009/01/14/writing-portable-groovy-scripts-with-a-magic-runnable-jar/ but this one uses Gradle to build a self-contained Jar

To build, simply run

    gradle
    
The executable jar will end up in ./build/libs/GroovyLauncher-1.0-standalone.jar, so to try it, do

    java -jar build/libs/GroovyLauncher-1.0-standalone.jar hello.groovy