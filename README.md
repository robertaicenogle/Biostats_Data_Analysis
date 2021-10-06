# Biostatistics_Paradigm
This repository follows/documents the UT Data Analytics Certificate Program. 

### Purpose
The goal is to develop a general data analytics paradigm. Throughout this process, we'll discover new programs/software, terminology, and a novel set of skills that can be applied to various projects.

## Definitions
   - **Command Line** - The command line is used to navigate and perform tasks on a computer. (macOS) Terminal Application. (Windows) Command Prompt.
   - **Github Repository** - 
   - **Interpreter** - 
   - **Git Bash** - An app for Microsoft Windows environments that installs Bash (Bourne-again shell) and Git on Windows OS.
   - **Shell** - A terminal application, like Terminal on macOS, used to interface with an OS through written commands.
   - **Homebrew** - 
   - **Xcode** - 
   - **Dependencies** - 

### Commands
- **pwd** - Present working directory
- **ls** - list files

## The Terminal Application

### Opening the Terminal Application - macOS
   1. Press Command+Space to open Spotlight Search.
   2. Type "Terminal" into the search bar and press Enter.
   3. Next, select the Terminal application to launch it. You can save Terminal to your dock for easy access.

### Using the Terminal Application
The terminal on my screen shows the following:

Last login: Fri Oct  1 00:35:18 on console
daniellaandrobert@Daniellas-iMac ~ % 

The first line shows the details of the last login. The second line provides the name of the computer (in this case, daniellaandrobert@Daniellas-iMac). The second part, ~ %, has three key parts:

   1. The squiggly line, **~**, is how the computer lets us know we are in the home directory.
   2. The name "daniellaandrobert" is the name of the home directory. The home directory on a Mac is the little house that appears in the sidebar of the Finder window under Favorites.
   3. The $ is what programmers call the prompt, which is where we will type commands.

### Finding Your Home Directory
Every time you open the terminal application, it will open in the home directory. Using commands, we can find the terminal "path" to the home directory.

To find the path to your home directory (or any directory), enter the command **pwd** after the prompt, $. Then press Enter to run, or execute, the command.  **pwd** stands for "print working directory." The working directory is the current directory you are working in. For example, right now we are working in the home directory. After we run the **pwd** command, the computer responds with current folder in use.

The command to view files and folders in the terminal is **ls**, which means "list files." If we type **ls** after the prompt and press Enter, the terminal will print the folder names in alphabetical order from top to bottom and right to left.

### Navigating with the Terminal Application
To navigate to a folder - for example Downloads - type cd Downloads. The cd command means "change directory."

To nagative to a new folder type cd .. The two dots after cd tells the computer to go back one level, which, in our case, is the home directory. ext, he would type cd Desktop and press Enter. Now Tom would be in his Desktop directory, or folder.

Typing cd ~ returns a user to the main directory - the desktop folder.

A technique used by more experienced programmers is to type cd ../Desktop after the prompt and then press Enter. This command allows you to go back one directory, or folder, level from the Downloads directory to the home directory, and then navigate to the Desktop folder. Let's break this command down in detail.

   - The cd .. tells the computer to go back up one level.
   - The forward slash "/" is a path separator.
   - After the forward slash, we add the directory or folder, Desktop.

## Install Xcode, Homebrew and git on a Mac
   - Follow instrucctions for installing **Xcode** at https://treehouse.github.io/installation-guides/mac/homebrew 
**Homebrew**



