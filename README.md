# A02

Using Visual Studio Code with Git & Github
---------  
- Installing Visual Studio Code & Prepping Your Workspace
    1. Download Visual Studio Code from https://code.visualstudio.com/ and run the downloaded installer.
    2. With Visual Studio Code opened, go to File > Preferences > Extensions , and install any needed extensions.
    3. Create a **Github** Account at https://github.com/
    4. Create a **Repository**; from the Dashboard, hit the "New" button at the top left of the screen.
    5. Give it a name, description, visibility settings, and a readme. This repository is what will be used with Visual Studio Code.

- Set up Git and Github for use with Visual Studio Code
    1. Install **Git** from https://git-scm.com/install/windows , and run the installer.
    2. Open Command Prompt, and type:
        git config --global user.name "Your Name"
	    git config --global user.email "your.email@example.com"
    This will configure Git and allow you to push changes.
    3. Go back to Visual Studio Code, and hit the icon that looks like a forking road (Source Control), and hit **Clone** Repository. A bar will appear at the top of the screen- hit "Clone from Github"
    4. Authorize it to sign in with your Github Account.
    5. Select the repository you wish to use with Visual Studio Code, and a folder on your computer you wish to clone the repository into.
    6. You can now create, modify, delete, move, or do many other things to your Github Repository straight from Visual Studio Code.

- Using Git and Github with Visual Studio Code
    1. Once you edit or create a file, you need to stage the change. In the Source Control panel, hit the plus icon on the file you have modified.
    2. You can now **commit** the change to your local repository by hitting the commit button. Make sure to give a description of what you modified!
    3. You can now **push** the changes to the repository on Github. In the Graph Panel (found in Source Control), hit the push button (arrow pointing up).
    
- Extra Tips and Tricks
    1. To change to a different **branch**, hit the Source Control icon on the bottom left of the screen. This will let you create and swap into different branches, letting you work on features or changes seperately.
    2. If you ever want to see the differences between your local repository and the **remote** repository, you can use **fetch**. Hit the Fetch button (dotted down arrow) in the Graph panel. It will download the contents of the repository, but won't merge them.
    3. **Pull** (solid down arrow) is another option to download the contents of the remote repository, but will automatically **merge** them with your local copy. 
    4. When merging changes, sometimes changes conflict with each other, causing a **merge conflict**. Visual Studio Code will automatically mark the lines that are causing conflicts. For simple conflicts, you can resolve them directly in the editor.
        - Accept Current Change to keep your version.
        - Accept Incoming Change to keep the incoming version.
        - Accept Both Changes to keep both versions. 
    For more complex changes, there is a 3 way editor which shows the Current Version, Incoming Version, and what the result would be. It will let you accept either the incoming or current change, combine them, or ignore them.
    
References
---------  
    - https://git-scm.com/book/ms/v2/Getting-Started-First-Time-Git-Setup
    - https://code.visualstudio.com/docs/sourcecontrol/github
    - https://about.gitlab.com/blog/git-pull-vs-git-fetch-whats-the-difference/
    - https://code.visualstudio.com/docs/sourcecontrol/merge-conflicts
