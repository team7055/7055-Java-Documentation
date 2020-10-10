# Git

Git is, "a distributed version-control system for tracking changes in source code during software development." It is used to better organize changes made to a large code base shared by many people, just like our robot code.
Git can take a while to get the hang of. Thankfully, you only need to know a few essential functions to get started with the robot code. If you'd rather learn from a person who knows what they're talking about, explore the following [YouTube playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV) which will teach you Git basics without even coding.

## Installation

### Preliminary Info & Operating Systems
Only complete these installation steps if you plan on writing and contributing code from you own machine. If you only use the school machines (will most likely be impossible 2020), or edit through GitHub (not recommended), you do not need to follow these steps.
This section will be written from the point of view of a Windows user, as we currently do not have access to Mac machines. There are most likely many online resources you can use to find out how to install Git on macOS. Git cannot be installed on a school Chromebook.

### Installing
Go to [https://git-scm.com/download/win](https://git-scm.com/download/win), which will begin downloading the Windows Git installer.

### Setps & Options
❗*\*Note: many of these steps are general recommendations. If you are an advanced user or programmer, feel free to change some of these steps. Just note that your experience may be slightly different and we may not be able to help completely. An asterisk (\*) will be placed next to mandatory steps.*

- Leave the install location to the default spot.
- Leave the selected components to default. You may add a desktop icon if you wish.
- Leave the start menu folder at default.
- Set the default text editor to Visual Studio Code (or your editor of choice)*
- Select the middle option, "Git from the command line and also from 3rd-party software"*
- Leave the default option "Use the OpenSSL library"
- Leave the line ending conversions to the default option
- Select the default option ("Use MinTTY")
- Leave the extra options on default
- Do not add experimental options

You are now done! You can launch git bash through the start menu (Windows search bar) or the desktop icon if you added it.

## Basic Command Prompt Navigation

When opened, your git bash terminal should look roughly like this:

![Terminal](/images/git1.jpg)
In green, it should say your desktop's name/ID

The command line is essentially just the File Browser in text form. Just like you can click to go to different folders, you can enter different folders here. Use the **ls** (list) command to list all of the files and directories (folders) from your current directory (folder).

![Terminal](/images/git2.jpg)
Yours should look similar but not the same.

Every item with a / at the end means it is a folder, or directory. If it does not have the /, it is a file.

Let's navigate to the Desktop folder. Because Windows is stupid, my desktop folder is hidden inside of my OneDrive folder. You can verify/discover this by using Window's own file browser and finding the path to your files and folders through that (slower, but easier for newcomers).

To enter another folder, simply use the **cd** (change directory) command.

![Terminal](/images/git3.jpg)

You can tell you've entered the directory when the yellow text above the $ changes from "~" to "~/FOLDERNAME" (not actually FOLDERNAME, just the name of the folder you cd into). This yellow text gives you the path of your current working directory, or in other words, the directories you needed to enter in order to get where you are now. The single "~" simply indicates the root directory.
To get to the Desktop directory, we can simply cd into it like so. I used ls here to verify that Desktop was inside of OneDrive directory.

![Terminal](/images/git4.jpg)

Here, you can store your code and projects. You can also follow these steps to find a project in any other directory, such as Documents.