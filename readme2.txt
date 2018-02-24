The Web Ontology Classifier Application is developed using Play Frameworks and Java.

Before checking out the source code, make sure that Java (JDK 6 or 7) is installed, and download and install the latest Classic Distribution (Standalone version) of Play Frameworks.

Follow the instructions to install Play Frameworks. [a link](https://github.com/user/repo/blob/branch/other_file.md)

If the intention is to contribute to the project, you will need to check out the latest version of the WOC source code from the repository using http://git-scm.com/, and sync any changes back in to the remote repository. Git GUIs are available to make using git simpler. Alternatively, if you'd just like to make use of the application, you can download the latest source code as a ZIP or clone it to your desktop.

Once the source code has been checked out, and assuming the play script has been added to your PATH:

export PATH=$PATH:/relativePath/to/play the application can be accessed in a terminal by changing to the root directory of the application folder, and running the play command:

play To get the application to run, the Fact++ Description Logic Reasoner is required. This can be downloaded as a precompiled binary distribution for Mac OSX, Linux, or Windows.

Once this is downloaded, the relevant .dll or .jnilib file will need to be added to the java.library.path.

One way to do this is to specify the path of the file when launching the Play Framework:

play -Djava.library.path=/$PATH_TO_FILE If this is successful, the WOC application can be compiled

[woc] $ compile and run:

[woc] $ run Once running, the application should be accessible locally at http://127.0.0.1:9000.

The source code can be edited using any standard text editor, and has also been configured to work as an Eclipse Project using the Eclipse IDE.

To open the application in Eclipse, import the project as an existing project, specifying the root directory of the application.
