# Installing Eclipse and Checkstyle

If you haven't already, plase follow steps 1 through 4 at https://mathcs.clarku.edu/~cs121/exercises/week2/GettingStartedWindows.html. If you're using a Mac, please use https://mathcs.clarku.edu/~cs121/exercises/week2/GettingStartedMac.html. Note that step 0 is unecessary for Windows, as java can already be found in the Path by default. Note that `stdlib.jar` is not necessary, as the latest version of the `algs4.jar` libarary includes `stdlib`'s functionality.



1. Head to https://www.eclipse.org/ide/ and download "Java IDE."

    ![Eclipse Website](https://github.com/dvdmuckle/cs160-docs/blob/master/images/website.png)

2. Run the downloaded installer. If it says Java is required, click "No" on the following popup. The installer will then open a webpage where you can download the Java JDK if it is not present. Make sure to download JDK 1.8 if you don't have it. If you're using the same computer as from a previous CS class, you should already be settled with Java.

3. From the installer, select the "Eclipse IDE for Java Developers" option.

    ![Installer](https://github.com/dvdmuckle/cs160-docs/blob/master/images/installer.png)


4. Once the installer has completed installing Eclipse, luanch it. Eclipse will ask you where you want to make your workspace. You can chose any location on your machine for this. This will be where all your projects will be stored, so a good location for the workspace might be in your "Documents" folder. _Don't make it the "Documents" folder itself._ On the main menu, click "Launch the Eclipse Marketplace." From here, you can install many plugins for Eclipse that can enhance the IDE. We want to install the Checkstyle plugin. In the "Find" field, type "checkstyle" and hit enter. There should be three results. Install the last result, called "Checkstyle Plug-in 8.7.0."

    ![Eclipse Marketplace](https://github.com/dvdmuckle/cs160-docs/blob/master/images/marketplace.png)

5. Close the installer. Under "Window" in Eclipse, click "Preferences." Here you can tune some Eclipse settings. Click "Checkstyle" from the left menu. We want to add a new style. You should be supplied with a `checkstyle.xml` file. Before adding it to Eclipse, move it to a permanent folder, possibly where you set up your `algs4.jar` library. Now, click "New..." in the Checkstyle configurator. Set the type to be "External Configuration File." Name the configuration whatever you want, possibly CS160. Now you can "Browse..." for the file wherever you stored it earlier. Once done, hit "OK."

    ![Checkstyle](https://github.com/dvdmuckle/cs160-docs/blob/master/images/checkstyle.png)

6. Now that Eclipse is installed and configured with Checkstyle, you may wish to start writing unit tests with JUnit. Head on over to http://junit.org/junit4/ to read more about JUnit, and https://help.eclipse.org/oxygen/index.jsp?topic=%2Forg.eclipse.jdt.doc.user%2FgettingStarted%2Fqs-junit.htm for how to use it with Eclipse.

