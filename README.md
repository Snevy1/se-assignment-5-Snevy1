[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284740&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

    - **Here are the steps**
         1. Visit the official website
            - Here is the [link] (https://code.visualstudio.com/download)
            - Click on the download button for Windows
         2. Download the Installer:
            - The download will start automatically.
            - Locate the downloaded installer executable file (usually named VSCodeUserSetup-{version}.exe)
         3. Run the Installer
            - Follow the on-screen instructions to complete the installation
         4. Choose Installation Location
            - By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code
         5. Agree to License Terms
            - By downloading and using Visual Studio Code, you agree to the license terms and privacy statement.
         6. Start coding

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     **Configurations and settings**
     - Autosave
     - Format on Save:
     - Font and Font Size - many developers prefer "Fira Code" or "Source Code Pro".

     **Extensions**
     - Prettier - Code Formatter
     - ESLint
     - GitLens
     - Live Server
     - Path Intellisense

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

    **Activity Bar**
     - Located on the side (usually the left side) of the window.
     - Contains icons representing different functionalities
       - Explorer: Allows you to navigate and manage files and folders in your project
       - Search: Provides search functionality across your codebase
       - Source Control: Integrates with version control systems (e.g., Git).
       - Run and Debug: Helps you run and debug your code.
       - Run and Debug: Helps you run and debug your code.
       - Extensions: Manages VS Code extensions.
   **Side Bar**
       - Adjacent to the Activity Bar (on the left side by default)
       - Contains additional panels:
         - File Explorer: Displays your project’s directory structure
         - Outline: Shows an overview of your code’s structure (functions, classes, etc.).
         - Extensions: Lists installed extensions
         - Debug: Provides debugging tools.
         - Git: Shows Git-related information.
   **Editor Group**
         - The central area where you write and edit code.
         - You can split it into multiple columns (each containing an editor tab)
         - Each tab represents a file or document you’re working on
   **Status Bar**
         - Located at the bottom of the window
         - Displays various information
            - Line and Column Numbers: Shows your cursor position.
            - Language Mode: Indicates the programming language of the current file.
            - Git Branch: Displays the active Git branch.
            - Extensions: Shows enabled extensions.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   - The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows you to access many of the editor's functions, commands, and settings quickly. It provides a centralized way to execute commands, without needing to navigate through menus or remember keyboard shortcuts.

   **How to access**

   - Keyboard Shortcut: Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac).
   - Menu: Go to the View menu and select Command Palette.

    **examples**
     1. Opening Files:
         - Command: Open File
         - Type >Open File to quickly open a file by name.
      2. Running Built-in Commands:
         - Command: 'Run Build Task'
         - Type >Run Build Task to execute a predefined build task.
      3. Installing Extensions:
         - Command: Extensions: Install Extensions
         - Type >Extensions: Install Extensions to open the extensions marketplace and install new extensions.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
        **Role**
        - Visual Studio Code (VS Code) extensions play a crucial role in enhancing your development experience.
        - Extensibility Model: VS Code’s rich extensibility model lets extension authors directly plug into the VS Code UI and contribute functionality through the same APIs used by VS Code.


        **Finding and Installing Extensions:**
        - Open the Extensions view by clicking the Extensions icon in the Activity Bar or using the shortcut ⇧⌘X (Windows/Linux: Ctrl+Shift+X).
        - Browse the Visual Studio Code Marketplace to discover extensions. Each extension includes a brief description, publisher details, download count, and a rating.
        - To install an extension, click the “Install” button. Once installed, it changes to a “Manage” gear button.
        - For example, you can install the “TODO Highlight” extension, which highlights text like ‘TODO:’ and ‘FIXME:’ in your code for easy identification.

        **Examples**
        - ESLint: Linting tool for JavaScript and TypeScript.
        - Prettier: Code formatter for consistent styling
        - Debugger for Chrome: Debug JavaScript code in Chrome.
        - Live Server: Launches a local development server for live reloading.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
    **How to open integrated terminal**
    - Click on the 3 dots on top of vs code
    - After clicking there will be 2 arrow signs with one labeled "terminal"
    - Click on the arrow then click on "new terminal"
    - Alternatively, you can press ctrl + "`" key above the tab key

    **Advantages of using integrated terminal**
    - It provides integration with the editor to support features like links and error detection
    - The integrated terminal can run commands such as mkdir and git just like a standalone terminal

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   **Creating Files and Folders**
     1. Creating a New File:
        - Keyboard Shortcut: Press Ctrl + N (Windows/Linux) or Cmd + N (Mac) to create a new untitled file.
        - Explorer: In the Explorer sidebar, right-click in the directory where you want to create the file and select New File. Enter the name of the new file and press Enter.
      2. Creating a New Folder:
        - Explorer: Right-click in the directory where you want to create the folder and select New Folder. Enter the name of the new folder and press Enter.

      3. Opening Files and Folders
         - Opening a File:Keyboard Shortcut: Press Ctrl + O (Windows/Linux) or Cmd + O (Mac) to open the file dialog and select the file you want to open.
         - Explorer: Click on the file name in the Explorer sidebar to open it.
      4. Opening a Folder
         - Keyboard Shortcut: Press Ctrl + K, then Ctrl + O (Windows/Linux) or Cmd + K, then Cmd + O (Mac) to open the folder dialog and select the folder you want to open.
         - Menu: Go to File > Open Folder and select the folder you want to open.
      5. Managing Files and Folders
         - Renaming a File/Folder:
           - Explorer: Right-click the file or folder and select Rename. Enter the new name and press Enter.
         - Deleting a File/Folder:
             - Explorer: Right-click the file or folder and select Delete. Confirm the deletion when prompted.
      6. Moving a File/Folder:
         - Drag and Drop: Click and drag the file or folder to the desired location within the Explorer
         - Cut and Paste: Right-click the file or folder, select Cut, then right-click in the destination folder and select Paste.
      7. Navigating Between Files and Directories Efficiently
         - Quick Open:
           - Keyboard Shortcut: Press Ctrl + P (Windows/Linux) or Cmd + P (Mac) to open the Quick Open dialog. Start typing the name of the file you want to open and select it from the list.
         - Go to Symbol:
          - Keyboard Shortcut: Press Ctrl + Shift + O (Windows/Linux) or Cmd + Shift + O (Mac) to open the Go to Symbol dialog. This is useful for navigating to specific functions, classes, or symbols within a file.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
     **How to customize**
     1. Open the Settings Editor
        - Navigate to File > Preferences > Settings.
        - Alternatively, use the shortcut ⇧⌘P (Windows/Linux: Ctrl+Shift+P) and search for Preferences: Open Settings.
      2. Customization Examples:
        - Change Theme:
          - Open the Settings editor.
          - Search for “Color Theme” and choose your preferred theme (e.g., “Dark+ (default dark)” or “Light+ (default light)”).
      3. Adjust Font Size:
        - In the Settings editor, search for “Font Size”.
        - Modify the “Editor: Font Size” setting to your desired value (e.g., 14).
      4. Modify Keybindings:
        - Search for “Keybindings” in the Settings editor
        - Click “Edit Keybindings” to customize keybindings or add your own shortcuts.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   **Steps**
   1. Setting Up and Starting Debugging
     - Install the Necessary Extensions:
      - Ensure you have the relevant language extension installed for your project (e.g., Python, Node.js, C++, etc.). You can find these in the Extensions Marketplace (Ctrl + Shift + X).
     - Open Your Project:
       - Open the folder containing your project files in VS Code (File > Open Folder or Ctrl + K, Ctrl + O).
     - Create a Simple Program:
     - Configure the Debugger:
        - Open the Debug view by clicking on the Debug icon in the Activity Bar on the side or pressing Ctrl + Shift + D.

       - Click on the gear icon to open the launch.json file, which configures the debugger.
       - If it’s your first time, VS Code will prompt you to create a launch.json file. Select the appropriate environment (e.g., Node.js for JavaScript).
     - Configure launch.json:
     - Set Breakpoints
     - Start Debugging:
       - In the Debug view, select the configuration you created in launch.json from the dropdown and click the green play button (or press F5).
   2. Key Debugging Features in VS Code
     - Breakpoints:
       - Set breakpoints by clicking in the gutter next to the line numbers. You can also set conditional breakpoints by right-clicking a breakpoint and selecting Edit Breakpoint.
     - Watch Expressions:
       - In the Debug view, you can add watch expressions to monitor the value of variables or expressions as you step through your code.
     - Call Stack:
       - View the call stack to see the sequence of function calls that led to the current point of execution.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

     **Integration**
     1. Install Git
       - Ensure you have Git installed on your computer. If not, follow the instructions in the Source Control view within VS Code to install it.
       - Restart VS Code after installing Git.
     2. Open a Git Repository:
       - Clone a Repository Locally:
         - Use the Git: Clone command from the Command Palette (⇧⌘P or Ctrl+Shift+P) or the “Clone Repository” button in the Source Control view.
         - Authenticate with GitHub if cloning from there.
         - Select a repository to clone to your local machine.
      - Initialize a New Local Git Repository: 
         - Open an existing or new folder in VS Code.
         - In the Source Control view, click the “Initialize Repository” button.
         - This creates a new Git repository in the current folder.
      3. Making Commits
         - After making changes to your code, open the Source Control view.
         - Stage the changes by clicking the “+” icon next to each file.
         - Enter a commit message and click the checkmark icon to commit your changes.
         - Alternatively, use the keyboard shortcut Ctrl+Enter (Windows/Linux) or ⌘Enter (Mac).
      4. Create and Switch Branches:
         - Use the Source Control view to create a new branch.
         - Switch between branches using the branch dropdown in the bottom-left corner.
      5. Push Changes to GitHub:
         - To publish your local repository to GitHub
           - Click the “Publish to GitHub” button in the Source Control view
           - Choose a name and description for the repository.
           - Decide whether it should be public or private.
           - VS Code pushes your code to the remote repository.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

