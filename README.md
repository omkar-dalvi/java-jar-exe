# Java-JAR-EXE conversion 
- ## Converting from Java to JAR file
  - Download [NetBeans with JDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk-netbeans-jsp-3413139-esa.html)
  - Install Netbeans
  - Create a new project or open an existing project
  - It will generate a structure as shown in the following figure <br>
    ![Image](img/1.PNG)
  - Open the file containing the main method (In my case it is LoadBalancing.java)
  - In the Run Tab, select the option "Clean and Build Project" <br>
    ![Image](img/2.PNG)
  - It will generate the jar file and in the Output, it will show the path of the jar file (Refer the below figure) <br>
    ![Image](img/3.PNG)
  - The jar file for the project is created successfully!
- ## Converting from JAR to EXE file
  - Download [Launch4j](https://sourceforge.net/projects/launch4j/files/launch4j-3/3.12/)
  - Install the Launch4j app and open it
  - In the "Basic" tab, give the path to store the exe file in the "Output file" field<br>
    <strong>Note:</strong> The path should end with filename.exe
  - In the "Jar" field, give the path to the jar file created in the above section
  - (OPTIONAL)The following steps are required if you are using any external JAR file in your project
    - In the "Classpath" tab, check the "Custom classpath" checkbox
    - In the "Main class" field, provide the name of the class containing the main method<br>
      <strong>Note:</strong> If your project is in a package, then the class name should be preceded by the package name eg. packageName.className
    - In the "Edit Item" field, give the path to the external JAR files used in your project
    - After providing the path, click on the "Accept" button to add it to the classpath
    - Follow the above two steps for remaining JAR files
  - In the "JRE" tab, give the minimum JRE version required for your project in the "Min JRE version" field
  - Finally, click on the Gear icon in the menu bar, it will ask for a path for the log file. Give appropriate path for the log file
  - The EXE file for your Java project is created succesfully!
  - To check the exe file, click on the play button (Test Wrapper) in the menu bar. It will give the output in the Log text area located at the bottom of the application
  
  Congratulations! You have successfully created your JAR and EXE file for your Java Project 
  
  Cheers!
  
