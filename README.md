Yahtzee Simulator
A two-player Yahtzee simulator built with Java, JavaFX, and FXML, featuring dice reroll logic, real-time frequency displays, and scoring across 13 categories.

Features
Two-player JavaFX interface.
Reroll logic for 10 dynamic dice values.
Real-time dice-frequency displays.
A 13-category scoring pipeline with instant calculations and rule enforcement.

Running the Project
You'll need a Java Development Kit (JDK) and JavaFX installed and configured to run this application.

How to run:
Open Command Prompt by pressing Windows + R, typing cmd, and pressing Enter.

Navigate to the folder containing the project's Java files:
cd /d "C:\Projects\yahtzee-simulator"

Set the path to your JavaFX SDK's lib folder:
set "PATH_TO_FX=C:\Tools\javafx-sdk\lib"

Compile the Java files with javac, then run the application with java:
javac --module-path "%PATH_TO_FX%" --add-modules javafx.controls,javafx.fxml -d out *.java
java --module-path "%PATH_TO_FX%" --add-modules javafx.controls,javafx.fxml -cp "out;." Main

These are example commands for Java files in one folder without package declarations, Java modules, or additional dependencies. Replace the paths and Main with your actual project folder, JavaFX SDK location, and entry-class name. Keep FXML files and other resources at the locations expected by the code. Projects with a different layout may require different commands.

Author
Ahmad Shahid
