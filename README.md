# Use-VS-Code-to-build-MPLAB-projects
Example of how to use VS Code to build MPLAB C/C++ projects  

Description: Visual Studio Code is a more pleasant development environment to work with than MPLAB. This example shows how VS Code can be used for building MPLAB C/C++ projects. It does not show how to debug from VS Code.  

Instructions:
1. Rename the vscode folder to .vscode 
2. Port_IO_Demo.code-workspace is the VS Code workspace file. Open it to open VS Code. 
3. Open the c_cpp_properties.json file in .vscode folder. Set all the project include paths, defines, compiler path, cStandard, cppStandard and intelliSenseMode.
4. All the build tasks (build, clean and rebuild) are configured in the tasks.json file in the .vscode folder. 
5. Build the project once with MPLAB, so that the .generated_files folder is created.
6. Then it is possivle to build, clean and rebuild using the VS Code tasks.

Example project info: The Port_IO_Demo example project is setup as a bare metal project. It is configured to be built for the PIC32MX General Purpose Starter Kit (DM320001) development board with the PIC32 processor. Version 5.5 of MPLAB is used.

Note: Tested on Windows 10
