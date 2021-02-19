# maven-java-archetype

 Archetype: wiperdog-osgi-ipojo-archetype:0.1.0

## Requirements

1. Java version
1. Maven version

### Project 
Steps to build a basic maven java project:

-  First created a repository in GitHub and initialized it with README.md and .gitignore(select maven).
-  Cloned the repository to my local.
-  Opened the temp folder with PowerShell by running as an administrator.
-  Ran below command to generate all the archetypes available in mvn.
```
mvn archetype:generate 
```
-  I have chosen archetype number 2753, I want to work on from the list generated.
-  Entered  unique 'groupId' and 'artifactId' that matches my repository name.
-  Left the version and package be default by pressing ENTER.
-  Now, I confirmed the configurations are correct.  [Y: :]
   By typing, Y.
-  This creates a new folder in C:\temp\new_folder
-  Opened the temp folder in VS Code. Reviewed all the files in the folders.
-  Opened PowerShell as an Admin in C:\temp
-  Ran below commands and saw the changes.
```
mvn clean
```
```
mvn compile
```
-  Now, ran 'mvn clean'
-  Copied src and pom.xml files from the temp folder to the cloned repo folder.
-  Used Git Bash to add the files to source control, create a commit, and push them to the cloud repo.
```
git add --all
git commit -m "add maven archetype"
git push origin master
```
