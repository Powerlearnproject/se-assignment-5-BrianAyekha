### 1. Installation of VS Code

To install Visual Studio Code (VS Code) on a Windows 11 operating system, follow these steps:

1. **Download VS Code**:
   - Go to the [Visual Studio Code website](https://code.visualstudio.com/).
   - Click on the "Download for Windows" button.

2. **Run the Installer**:
   - Open the downloaded `VSCodeUserSetup-x64-<version>.exe` file.
   - Follow the prompts in the installation wizard:
     - Accept the license agreement.
     - Choose the installation location (default is usually fine).
     - Select additional tasks like creating a desktop icon, adding VS Code to the PATH (important for command-line usage), and associating file types.

3. **Finish Installation**:
   - Click "Install" to complete the process.
   - Once the installation is complete, you can launch VS Code directly from the installer or from the start menu.

**Prerequisites**:
- Windows 11 OS.
- Administrative privileges to install software.

### 2. First-time Setup

After installing VS Code, consider adjusting the following configurations for an optimal coding environment:

1. **Settings Sync**:
   - Enable Settings Sync from the Manage icon (gear icon) > Settings Sync > Turn On.
   - This will sync your settings, keybindings, extensions, and more across devices.

2. **Theme and Appearance**:
   - Change the theme via File > Preferences > Color Theme or using `Ctrl+K` then `Ctrl+T`.
   - Popular themes include "Dark+ (default dark)", "Light+ (default light)", and extensions like "Dracula" or "One Dark Pro".

3. **Extensions**:
   - Install essential extensions from the Extensions view (Ctrl+Shift+X).
   - For web development, consider:
     - `ESLint`: Linting JavaScript and TypeScript code.
     - `Prettier - Code formatter`: Code formatting.
     - `Live Server`: Launch a development local server with live reload.
     - `Debugger for Chrome`: Debug JavaScript code in the Google Chrome browser.

4. **Settings**:
   - Adjust settings via File > Preferences > Settings or `Ctrl+,`.
   - Set auto-save, editor font size, tab size, and more to fit your preferences.

### 3. User Interface Overview

The main components of the VS Code user interface are:

1. **Activity Bar**:
   - Located on the far left.
   - Provides access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.
   - Customizable with additional views via extensions.

2. **Side Bar**:
   - Located next to the Activity Bar.
   - Displays the contents of the selected view from the Activity Bar, like the file explorer or the source control panel.

3. **Editor Group**:
   - The main area where files are opened and edited.
   - Supports multiple editors side-by-side, with tabs for each open file.
   - You can split the editor to view and edit files simultaneously.

4. **Status Bar**:
   - Located at the bottom.
   - Provides information about the current file and workspace, such as line and column number, file type, encoding, and Git branch.
   - Includes shortcuts for changing language modes and managing extensions.

### 4. Command Palette

The Command Palette is a powerful tool in VS Code that provides access to all commands and actions.

- **Accessing the Command Palette**:
  - Press `Ctrl+Shift+P` (or `F1`).
  
- **Common Tasks Using the Command Palette**:
  - Open settings: `Preferences: Open Settings (JSON)`
  - Install extensions: `Extensions: Install Extensions`
  - Run a task: `Tasks: Run Task`
  - Toggle terminal: `View: Toggle Integrated Terminal`
  - Git commands: `Git: Commit`, `Git: Push`

### 5. Extensions in VS Code

Extensions enhance the functionality of VS Code. They can be found, installed, and managed through the Extensions view:

- **Finding Extensions**:
  - Open the Extensions view with `Ctrl+Shift+X`.
  - Use the search bar to find extensions.

- **Installing Extensions**:
  - Click the "Install" button on the desired extension in the Extensions view.

- **Managing Extensions**:
  - Disable, uninstall, or configure extensions from the Extensions view.

**Essential Extensions for Web Development**:
- `ESLint`
- `Prettier - Code formatter`
- `Live Server`
- `Debugger for Chrome`
- `Path Intellisense`

### 6. Integrated Terminal

To open and use the integrated terminal in VS Code:

- **Opening the Terminal**:
  - Use `Ctrl+` to toggle the terminal.
  - Alternatively, go to View > Terminal.

- **Advantages of the Integrated Terminal**:
  - Provides a command-line interface directly within VS Code.
  - Allows you to run commands, scripts, and tools without leaving the editor.
  - Supports multiple terminal sessions.
  - Synchronizes with the current working directory of the editor.

### 7. File and Folder Management

To manage files and folders in VS Code:

- **Creating Files and Folders**:
  - Right-click in the Explorer view and select "New File" or "New Folder".
  - Use `Ctrl+N` to create a new file.

- **Opening Files and Folders**:
  - Use File > Open File or File > Open Folder.
  - Drag and drop files/folders into the editor.

- **Navigating Between Files**:
  - Use the Explorer view or `Ctrl+P` to quickly open files by name.
  - Use `Ctrl+Tab` to switch between open files.

### 8. Settings and Preferences

To customize settings in VS Code:

- **Accessing Settings**:
  - Use File > Preferences > Settings or `Ctrl+,`.
  - Settings can be viewed and edited in both a UI and JSON format.

- **Examples of Customizing Settings**:
  - **Change Theme**: Go to Settings, search for "Color Theme", and select a theme.
  - **Adjust Font Size**: Search for "Font Size" and set your desired size.
  - **Modify Keybindings**: Go to File > Preferences > Keyboard Shortcuts or `Ctrl+K` then `Ctrl+S`.

### 9. Debugging in VS Code

To set up and start debugging a simple program:

1. **Open a Project**:
   - Ensure your project is open in VS Code.

2. **Configure Launch Settings**:
   - Go to Run and Debug view (`Ctrl+Shift+D`).
   - Click on "create a launch.json file" to configure the debugger for your environment (Node.js, Python, etc.).

3. **Set Breakpoints**:
   - Click in the gutter next to the line number in the editor to set breakpoints.

4. **Start Debugging**:
   - Click the green play button in the Run and Debug view.
   - Use the debug toolbar to step through code, continue execution, and inspect variables.

**Key Debugging Features**:
- Breakpoints, step over/in/out, watch variables, call stack, and debug console.

### 10. Using Source Control

To integrate Git with VS Code:

1. **Initialize a Repository**:
   - Open the Source Control view (`Ctrl+Shift+G`).
   - Click "Initialize Repository" if you don’t have one already.

2. **Making Commits**:
   - Stage changes by clicking the "+" icon next to changed files.
   - Enter a commit message and click the checkmark icon to commit.

3. **Pushing to GitHub**:
   - Add a remote repository with `git remote add origin <repository URL>`.
   - Push changes using `git push -u origin main`.

VS Code offers a seamless interface for managing source control tasks, including viewing changes, making commits, and synchronizing with remote repositories.
![screenshot on visual code labeling](../screenshot.png)