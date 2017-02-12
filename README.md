# nurseHelpBuilder
Generate database and UI code from xml schema, for customizing NurseHelper for 
different clients

## Purpose
This repository is one component of a final long-term care facility electronic 
patient health data and charting package.  This component will ultimately be 
used to generate code based on an xml schema which is tailored to an individual 
care facility's particular needs.  This will decrease the time and effort needed 
to customize this package as needed, for each different company/facility.  
This should also minimize time needed to implement changes that could be 
needed in the future.

This component is to be used with [nurseHelper.](https://github.com/janlep47/nurseHelper)

## Installation
This respository can be installed on your working directory.  The java files 
can be imported into AndroidStudio with [nurseHelper.](https://github.com/janlep47/nurseHelper)
  See [how to use Android Studio.](http://www.instructables.com/id/How-To-Create-An-Android-App-With-Android-Studio/)

## Instructions
This code consists of example .xsd files, which are one example of an implementation 
for a long-term facility's database.  The .java output files are also included.  
Some example .xml files are included, which correspond to the schema (.xsd) files.
  See this [xml schema tutorial](http://www.w3schools.com/xml/xml_schema.asp) for 
more information on how to create schema files.

Once the schema files have been defined, create the output .java files from the 
command line:
'xjc -p <your-package> <your-file.xsd> -d <your-subdirectory>'

## License
See LICENSE.md

## Remaining Tasks
This repository is a beginning example.

