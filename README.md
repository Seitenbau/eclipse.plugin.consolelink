# Console Links - Eclipse Plug-in

[![Build Status](https://buildhive.cloudbees.com/job/Seitenbau/job/eclipse.plugin.consolelink/badge/icon)](https://buildhive.cloudbees.com/job/Seitenbau/job/eclipse.plugin.consolelink/)


This eclipse plug-in provides support for file system links in the eclipse console.
A link to a file must start with file:// and the file must reference a file in the current eclipse workspace.
Only files without whitespaces are supported by the plugin.

Try something like System.out.println("file://C:/workspace/consolelink/pom.xml"); the path in the eclipse console 
now works as a link to the pom.xml file.  

## Requirements

 - Eclipse Indigo 3.7.2
 - Maven 3.0.x to build the project

## Installation

The eclipse plug-in could be installed from the following eclipse update site:

  		http://seitenbau.github.com/eclipse.plugin.consolelink/


## Build and Installation

- Download Apache Maven Version 3.0.x

- Run mvn clean package in the root folder of the project

- Install the plug-in from the local update site 
  The update site can be found in the folder consolelink.repository/target/site

## License

Apache License, Version 2.0 (current)
http://www.apache.org/licenses/LICENSE-2.0
