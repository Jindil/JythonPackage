## How to use

1. Make a copy of this repository.
1. Delete `src/test/java` if you don't require tests.
1. Put your scripts into a *subfolder* of `src/main/resources/scripts` (the name of the subfolder[s] corresponds to the menu[s] where the commands will appear).
1. Edit `pom.xml` to reflect your project information.
1. Run `mvn` to build your jar file, or `mvn -Dimagej.app.directory="PATH TO YOUR FIJI.app"` to directly copy the jar file and possible dependencies into your ImageJ/Fiji installation.
