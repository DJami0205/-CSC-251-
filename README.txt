FAMILY FARM MANAGER (Java Swing)
Requires: JDK 11 or newer (javac -version to check).

FOLDER LAYOUT
FarmManager/
  src/   <- all 11 .java files go here (no package statements)
  out/   <- compiled .class files (created automatically)
  run.bat (Windows) / run.sh (Mac/Linux)

RUN FROM COMMAND LINE
  cd FarmManager
  javac -d out src/*.java     (Windows: javac -d out src\*.java)
  java -cp out FarmApp

RUN IN ECLIPSE:  File > New > Java Project "FarmManager" > copy all .java files
                 into the src folder (default package) > right-click FarmApp.java > Run As > Java Application.
RUN IN INTELLIJ: New Project > copy .java files into src > right-click FarmApp > Run.
RUN IN VS CODE:  Open the FarmManager folder (Java extension pack) > open FarmApp.java > Run.
