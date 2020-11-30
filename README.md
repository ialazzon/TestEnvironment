**Test Environment**

This project includes all files and resources needed to run the test cases for the four case studies presented in the paper.

- Folder _metamodels_ includes all the meta-model (.ecore) files.
- Folder _models_ includes all the models used in the test cases.
- The EUnit files are in folder _tests_. These files have .eunit extension. The test cases to be executed in a case study are those listed in the .eunit files. The contents of an .eunit file can be automatically generated by our Regression Test Selection Tool.
- The transformation programs are in the folder _transformation_.
- The Ant files necessary for executing the test cases and invoking EUnit are in the .xml files: eunit1.xml,…, eunit4.xml.

Note the following mapping between the ant files, .eunit files, and the case studies:

| Case Study | The corresponding .eunit File in the _tests_ folder: | The corresponding ant file: |
| --- | --- | --- |
| OO2DB | et1.eunit | eunit1.xml |
| QN2QPN | atl2.enut | eunit2.xml |
| BibTeX2DocBook | atl3.eunit | eunit3.xml |
| CPL2SPL | atl4.eunit | eunit4.xml |

To run a test suite in a case study, right-click the corresponding launch file. Then go to Run and select the first run configuration that appears in the menu.

To get a copy of Eclipse with Epsilon, visit [https://www.eclipse.org/epsilon/download/.](https://www.eclipse.org/epsilon/download/)