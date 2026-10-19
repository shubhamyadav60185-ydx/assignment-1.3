Aim

To create and manage a project folder structure using terminal commands and open the project in Visual Studio Code.

1. Open the Terminal

Open Windows Terminal or Command Prompt on the computer. The terminal allows us to create, rename, delete, and navigate files and folders using commands.

2. Create the Main Project Folder

Use the following command to create the main folder:

mkdir web-development-practice

Navigate into the project folder:

cd web-development-practice

3. Create Week Folders

Create three folders named week-1, week-2, and week-3:

mkdir week-1 week-2 week-3

4. Create an index.html File in Each Folder

Run these commands to create an HTML file inside each week folder:

type nul > week-1/index.html
type nul > week-2/index.html
type nul > week-3/index.html

These commands create empty HTML files that can be edited later.

5. Practice Navigation, Renaming, and Deleting

A. Navigation

cd week-1
cd ..
dir

cd week-1 opens the week-1 folder.

cd .. returns to the parent folder.

dir displays the files and folders in the current directory.

B. Renaming a Folder

ren week-3 week-3-practice
ren week-3-practice week-3

The first command renames the folder, and the second restores its original name.

C. Deleting a Folder

mkdir temp-folder
rmdir temp-folder

These commands create and then delete an empty temporary folder.

6. Open the Project in Visual Studio Code

First, make sure you are inside the web-development-practice folder. Then run:

code .

This command opens the current project folder in Visual Studio Code. If the code command is not recognized, enable the VS Code command-line option or open the folder through VS Code manually.

Final Folder Structure

After completing the commands, the folder structure should look like this:

web-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html

Conclusion

In this assignment, I learned how to create folders and files, navigate between directories, rename and delete folders, and open a project in Visual Studio Code using terminal commands.

Submission

Record of the terminal commands used.

Screenshot of the final folder structure in Visual Studio Code or File Explorer.