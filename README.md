# Caysen's C++ Boilerplate for VSCode

These snippets are best used with entire C++ projects. If you are looking to debug a single file, take a look at the Single File branch. That's much easier to set up and should work as long as each file has a different name.

**C is not supported at this time.**

## Installation
1. Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
2. `Configure User Snippets`
3. Make a new snippet file (name whatever you want).
4. Copy/Paste from the snippet file here into the new file.
5. Save the file.

## Usage
1. Create a new folder for C++ project. **The folder name cannot have spaces!**
2. Open the folder in VSCode.
3. Start writing your code. Once you're done, continue to the next step.
4. Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
5. `CMake: Quick Start`
6. Follow the prompts to create a new C++ project. (All names must be the same as the Workspace/Project name)
7. Open the `CMakePresets.json` file and type "CMakePresets.json" after the `"CMAKE_BUILD_TYPE"` line.
8. Hit enter and the line should autocomplete. You should see the CFlags.
9. **Make sure to delete the spaces where it tells you to.**
10. Create a new .vscode folder.
11. Create your launch.json, tasks.json, and settings.json files in the .vscode folder.
12. For each one, type the file name and hit enter. The file should autocomplete.
13. **For each file, make sure to delete the spaces where it tells you to.**
14. Open the Command Palette again.
15. `CMake: Debug`
16. If your program debugs without issue, try debugging the program through VS Code to make sure everything works.

## Common Issues

### GDB Not Found
1. Make sure you have GDB installed. `brew install gdb`
2. Code Sign your GDB if on MacOS. Use ChatGPT to help you with this.
3. Close and reopen VSCode after installing GDB.