# A02

Using Visual Studio Code with Git & Github
---------  
- Installing Visual Studio Code & Prepping Your Workspace
    1. Download Visual Studio Code from https://code.visualstudio.com/ and run the downloaded installer.
    2. With Visual Studio Code opened, go to File > Preferences > Extensions , and install any needed extensions.
    3. Create a Github Account at https://github.com/
    4. Create a Repository; from the Dashboard, hit the "New" button at the top left of the screen.
    5. Give it a name, description, visibility settings, and a readme. This repository is what will be used with Visual Studio Code.

- Set up Git and Github for use with Visual Studio Code
    1. Install Git from https://git-scm.com/install/windows , and run the installer.
    2. Open Command Prompt, and type:
        git config --global user.name "Your Name"
	    git config --global user.email "your.email@example.com"
    This will configure Git and allow you to push changes.
    3. Go back to Visual Studio Code, and hit the icon that looks like a forking road (Source Control), and hit Clone Repository. A bar will appear at the top of the screen- hit "Clone from Github"
    4. Authorize it to sign in with your Github Account.
    5. Select the repository you wish to use with Visual Studio Code, and a folder on your computer you wish to clone the repository into.
    6. You can now create, modify, delete, move, or do many other things to your Github Repository straight from Visual Studio Code.

- Using Git and Github with Visual Studio Code
    1. Once you edit or create a file, you need to stage the change. In the Source Control panel, hit the plus icon on the file you have modified.
    2. You can now Commit the change to your local repository by hitting the Commit button. Make sure to give a description of what you modified!




REFERENCES:
    https://git-scm.com/book/ms/v2/Getting-Started-First-Time-Git-Setup
    https://code.visualstudio.com/docs/sourcecontrol/github