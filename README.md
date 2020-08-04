# Building_Escape

This is a game I made following the Udemy Gamedev.tv Unreal Engine Tutorial.

Note to self:
- Next time adding Unreal to Github, remember assets and binaries are too large to be supported
- To add project:
1. Make repository in Github, with .gitignore targeting Unreal to not push large files
2. Make Unreal Project in folder with the same name as the Repository
3. Pull Repository
4. Put all contents of Unreal Project in the local repository
5. Add, Commit, Push

The problem with using git init and adding .gitignore is that git doesn't actually follow the .gitignore. It will only follow it once it is established after a commit. Problem is that our files are too large to commit in the first place. Therefore we must establish that .gitignore first, then add the project files. Unfortunately, Unreal only allows you to create a new folder with your project name rather than using a pre-existing folder.

Look into Git LFS for future endeavors.
