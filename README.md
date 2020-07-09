#### PRE-REQUISITE
Install JRE 8 or greater - https://www.oracle.com/java/technologies/javase-jre8-downloads.html

#### METADATA EXTRACTOR
Extracting metadata from file names and creating an associated XML file.

#####  NOTES - FILES AND FOLDERS

1. Download the MetadataExtractor.jar
2. Open the Command Prompt
3. Type "cd Desktop/RunnableSolution" into the command prompt and hit the Enter key
4. Enter the Prompt Format below into the command prompt, changing fullPathNameToYourFolderFullOfTestFiles text to the path to the folder that contains your test files, and hit enter
5. Enter the Prompt Format below into the command prompt window, changing the fullPathNameToYourFolderFullOfTestFiles text to the path to the folder that contains your test files, and hit enter

```
Prompt Format:
java -jar MetadataExtractor.jar fullPathNameToYourFolderFullOfTestFiles
```

Example:
```
C:\Users\karl.harvey\Desktop\RunnableSolution>java -jar MetadataExtractor.jar "C:\Users\karl.harvey\Desktop\Tests"
```