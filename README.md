[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15417405&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Unfortunately, I do not use Windows 11, but I can provide the steps for ubuntu 20.04. As always, before installation make sure the system is up to date.

   ```bash
   sudo apt update
   sudo apt upgrade
   ```

   - Download the Visual Studio Code .deb package from the official website: <https://code.visualstudio.com/docs/setup/linux>
   - Open the terminal and navigate to the Downloads directory using the `cd` command.

   - Run the following command to install the .deb package:

     ```bash
     sudo apt install ./code_1.91.1-1720564633_amd64.deb.deb
     ```

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   - After installing VS Code, users can customize their coding environment by adjusting the following settings:
     - Theme: Dark mode as default or choose from a variety of themes available in the marketplace.
     - Font Size: Small possible font size for better readability.
     - Keybindings: Customize keybindings to match your workflow.
     - Extensions: python. formatter and linter [ruff]
     - Editor Settings: Tab size - 4, Word wrap

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Main components of the VS Code user interface:
   - Activity Bar: Contains icons for different views like Explorer, Search, Source Control, and Extensions. Users can switch between these views by clicking on the respective icons.
   - Side Bar: Provides access to different panels like Explorer, Search, Source Control, and Extensions. Users can customize the Side Bar by adding or removing panels based on their preferences.
   - Editor Group: Displays the open files in the editor. Users can split the editor into multiple groups to view and edit files side by side.
   - Status Bar: Shows information about the current file, such as the line ending, file encoding, and indentation. It also displays the language mode and Git status.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette is a powerful tool in VS Code that allows users to access various commands and features through a search interface. Users can open the Command Palette by pressing `Ctrl+Shift+P`. Some common tasks that can be performed using the Command Palette include:
   - Quick access to extensions commands

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions in VS Code are add-ons that enhance the functionality of the editor by providing additional features, language support, and tools. Users can find, install, and manage extensions through the Extensions view in the Activity Bar. Some essential extensions for web development include:

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   The integrated terminal in VS Code allows users to run shell commands, scripts, and other terminal-based tasks directly within the editor. Users can open the integrated terminal by pressing `Ctrl+``. Some advantages of using the integrated terminal compared to an external terminal include:

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
