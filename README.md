"This is readme of 5"<br>
# Solution of Scenario 5: Use of .gitignore <br>
In this we have  files in your project that should not be tracked by Git, such as log files or build artifacts.<br>
Firstly,we will create a new repository from terminal using mkdir and initalize the repo using command"git init"<br>
Then we will create two files named as "tracked_file.txt" and "ignored_file.log"<br>
Then Create a .gitignore file and add patterns to exclude the appropriate files.<br> 
Now we will Verify that the ignored files are not tracked by Git.<br>
Here are the screenshot : ![alt text](<ss all files.jpg>) , ![alt text](<ss initialization of repo.jpg>) ,![alt text](<ss status of file.jpg>) , ![alt text](<ss tracked file.jpg>)  <br>
Command used : 1.git init = used to initalize the repository.<br>
               2.git commit = it commit the changes to the stagigng area <br>
               3.git status : display the state of the working directory and the staging area<br>
               <br>
               <br>
               <br>
# Real-Life Use Cases of .gitignore:<br>
*The .gitignore file is essential in any project to ensure that certain files are not tracked by Git. Here are some real-life use cases and types of files typically included in it:<br>
1.Configuration Files:<br>

Use Case: Prevents environment-specific settings from being shared across different environments.<br>
Example: .env, config.yaml<br>
2.Log Files:<br>

Use Case: Avoids cluttering the repository with logs generated during application runtime.<br>
Example: *.log<br>
3.Build Artifacts:<br>

Use Case: Excludes compiled binaries, temporary files, and output directories created during the build process.<br>
Example: /build, /dist<br>
4.System-Specific Files:<br>

Use Case: Prevents OS or IDE-specific files from being tracked, which are irrelevant to the project's functionality.<br>
Example: .DS_Store, Thumbs.db<br>
5.Temporary Files:<br>

Use Case: Excludes temporary files created by text editors or IDEs during development.
Example: *.swp, *.tmp<br>


              
               

