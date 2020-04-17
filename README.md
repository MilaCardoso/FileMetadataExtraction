#### METADATA EXTRACTOR
Extracting metadata from file names and creating an associated XML file.

#####  NOTES - FILES AND FOLDERS
*XML_Source* must be in the same root folder as *MetadataExtractor.jar*.
Do not rename *XML_Source* folder.
*XML_Source* containes *xml template*. DO NOT change the name of the *generic.metadata.xml*.


1. Download the repo from github as a ZIP file
2. Open the folder called FileMetadataExtraction-master in your downloads
3. Choose Extract All in the menu bar
4. Enter the extracted FileMetadataExtrction-master Folder
5. Open the folder called RunnableSolution--mustUnzip
6. Choose Extract All in the menu bar
7. Rename the "RunnableSolution--mustUnzip" to just "RunnableSolution"
7. Drag the unzipped RunnableSolution folder to your desktop
8. Open the Command Prompt from your list of applications
9. Type "cd Desktop/RunnableSolution" into the command prompt and hit the Enter key
10. Enter the Prompt Format below into the command prompt, changing fullPathNameToYourFolderFullOfTestFiles
text to the path to the folder that contains your test files, and hit enter

```
Prompt Format:
java -jar MetadataExtractor.jar fullPathNameToYourFolderFullOfTestFiles
```

Example:
```
C:\Users\karl.harvey\Desktop\RunnableSolution>java -jar MetadataExtractor.jar "C:\Users\karl.harvey\Desktop\Tests"
```