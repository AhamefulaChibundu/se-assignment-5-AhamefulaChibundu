[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15264957&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   VsCode is also known as  Visual studio code. It is a text editor used for writing codes. Installing VsCode is also easy, follow the following steps and you will be able to successfully install it:
   1. Visit code.visualstudio.com, you should see "download for Windows". Click on it  and it would download the installation file
   2. Once the download is complete, double click on the downloaded file and it would open the installation wizard.
   3. Click on “I accept the agreement”, click on “next”
   4. You can choose to check the “Create a desktop icon” if you want an icon to be created on your desktop after installation, then click next. 
   5. Click on "Install". After successful installation click on finish, VsCode would launch on its own.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   For optimal coding environment, some initial cofigurations should be made depending on the kind of projects you plan on doing. Firstly, its a good practice to set your theme to your taste and then enable autosave to whatever code you type. Another thing you need to do is to install and enable necessary extensions you need. If you are going to be working with python files, you should download python extension verified by microsoft. other extensions you could download are dart, flutter, etc. 


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Activity bar: Located on the far left-hand side. Lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.

   Side bar: Contains different views like the Explorer to assist you while working on your project, Search Panel which provides search and replace functionality across files in your project, Source Control Panel which displays Git repository status, allows staging/unstaging changes, and shows commit history, Run and Debug Panel which contains configurations for running and debugging your code and Extensions Panel which lists installed extensions and allows you to search for and install new ones.
   
   Editor Group: The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.

   Status bar: The Status Bar displays various information and provides shortcuts to perform certain actions. It shows context-specific information related to the currently active file or workspace.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows you to access and execute a wide range of commands and functions within the editor. It provides a quick and efficient way to perform tasks without navigating through menus or remembering keyboard shortcuts. 
   
   The Command Palette can be accessed in two primary ways:
   Using the Keyboard Shortcut: Press Ctrl+Shift+P (or Cmd+Shift+P on macOS)
   Through the Menu: Go to View > Command Palette

   A good example is changing language mode, Type Change Language Mode in command palette to set the language mode for the current file.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions in Visual Studio Code (VS Code) enhance its functionality by adding support for additional languages, debuggers, tools, and services. They allow users to customize their development environment to suit their specific needs.
   we can open the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by using the keyboard shortcut Ctrl+Shift+X (or Cmd+Shift+X on macOS). On the search box, you can type any extension you wish to install.
   Examples of such extensions are python, dart, flutter, debugging tools, etc.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   The integrated terminal can be opened in different ways in VS code:
   1. Using keyboard shortcut: press ctrl + `
   2. Go to View > Terminal.
   3. Open the Command Palette with Ctrl + Shift + P then Type Terminal: Create New Terminal and press Enter.
   Some advantages of using the integrated terminal compared to an external terminal include:
   1. Convenience: you don’t have to switch between applications. This provides a more streamlined and efficient workflow. You can run commands, scripts, or manage version control directly from your editor
   2. Efficiency: You can quickly switch between writing code and executing commands. For example, you can write a script and run it immediately in the integrated terminal without leaving the editor.
   3. Integration with Editor Features: Errors and outputs from commands are easier to trace back to your code, as they are displayed within the same interface. You can click on paths and error messages in the terminal to quickly navigate to the corresponding file and line in the editor.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creating, opening, and managing files and folders in Visual Studio Code is straightforward.
   Creating files: Open the Explorer view by clicking the Explorer icon in the Activity Bar or pressing Ctrl + Shift + E, right-click on the folder where you want to create a new file and select New File, type the desired filename and press Enter.

   Creating folders: Open the Explorer view, right-click on the folder where you want to create a new folder and select New Folder, type the desired folder name and press Enter.

   Opening files: Go to File, Open File and select the file from your file system.

   Opening folders: Go to File, Open Folder and then select the desired folder. This will open the folder in the Explorer view.

   Managing files and folders has to do with renaming and deleting files or folders.
   Renaming: Right-click on a file or folder in the Explorer view and select Rename, type the new name and press Enter.

   Deleting: Right-click on a file or folder in the Explorer view and select Delete. A prompt comes up to confirm the deletion, confirm when prompted.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   We can find and customize settings in VS code by going to settings. To do this, You click on file, preferences and then settings or you can press crtl + ',' to go to settings. You can also access settings at the buttom left of VS code.

   To change the theme, go to settings and then search for "theme color", choose whatever theme you prefer and hit enter. OR Select the File, Preferences, Theme, Color Theme and then chose the theme you want and press enter.

   To change font size, go to settings and then search for font size. you can choose any font size you want and press enter.

   Key bindings are simply keyboard shortcuts for commands. You can change the key bindings to suit your taste. JUst click on file, preferences and then click on keyboard shortcuts. You would see all the shortcuts available, choose anyone you choose to edit and then enter your prefered shortcut and press enter.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Debugging means checking and fixing errors or mistakes in your program. To debug a simple program in VS code, follow these steps:
   1. Go to extensions and download the debugging extension
   2. To bring up the Run and Debug view, select the Run and Debug icon in the Activity Bar on the side of VS Code. You can also use the keyboard shortcut Ctrl+Shift+D.
   3. select Run and Debug on the Debug start view or press F5 and VS Code will try to run your currently active file. VS Code will try to automatically detect your debug environment, but if this fails, you will have to choose it manually.

   Visual Studio Code (VS Code) is a powerful code editor that includes a variety of features for debugging. Here are some of the key debugging features available in VS Code:
   
   1. Breakpoints
   
   Set Breakpoints: You can click next to the line numbers in your code to set breakpoints. This pauses the execution of your program at specific points so you can inspect the state of your application.

   Conditional Breakpoints: You can set conditions for breakpoints so they only trigger when certain conditions are met.

   Function Breakpoints: You can break execution when a specific function is called.
   2. Debug Console
   
   Evaluate Expressions: In the Debug Console, you can run JavaScript or other language-specific commands and see their output immediately.
   
   Watch Variables: You can add variables to the Watch pane to monitor their values throughout the debugging session.
   
   3. Call Stack
   
   View Call Stack: This shows you the function call hierarchy at any point during your program's execution, helping you trace the flow of your application.
   
   4. Variables Pane
   
   Inspect Variables: You can view and inspect the values of local and global variables, including their current state and type.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Integrating Git with VS Code for version control is straightforward. Here’s a step-by-step guide on how to initialize a repository, make commits, and push changes to GitHub:

    1. Launch VS Code and then open the Terminal. You can open the terminal by navigating to View and then Terminal or by using the shortcut Ctrl+ `.
    2. Use the terminal to navigate to your project folder. For example: cd name of project folder
    3. Initialize a new Git repository by running 'git init'. This command creates a new .git directory in your project folder.
    4. Make any chanage in the file you are working on and then use the command 'git add name_of_file' in the terminal. This would stage the changes.
    5. Commit the staged changes with a commit message. Eg: git commit -m "Your commit message"
    6. Create a Repository on GitHub: Go to GitHub and create a new repository. Do not initialize it with a README, .gitignore, or license file.
    7. Copy the Repository URL: Copy the URL of your new GitHub repository (e.g., https://github.com/yourusername/your-repo.git).
    8. Add Remote: Add your GitHub repository as a remot. Eg: git remote add origin https://github.com/yourusername/your-repo.git
    9. Push your commits to GitHub: git push -u origin master. Note that The -u flag sets origin as the default remote for future pushes.
    10. After these initial setup, you can follow this workflow for subsequent changes. git add name_of_file, git commit -m "Your commit message" and then git push


    Refrences: https://code.visualstudio.com/docs/getstarted/userinterface



 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

