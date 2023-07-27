# How to install Git and connect it with your Visual Studio Code in Windows.  
## Download Git  
Download the Git installer from the official Git website: https://git-scm.com/download/win   
### Run the installer  
1. When you run the installer you will be greeted by the user agreement.  
2. Then select the directory where you want git to be installed.  
3. After directory selection you will be prompted to select components, the default is enough for git use, but you can also check other   options if desired.  
4. As the setup will create shortcuts in the start menu folder, it gives you the choice of changing the folder. The default option is fine.  
5. Choose the editor that you use and want to be gits default editor. We will select the visual studio code as Git's default editor.  
6. For Adjusting the name of the initial branch in new repositories we will let git decide.  
7. For Adjusting your path environment use the Recommended option.  
8. Choosing the SSh executable. Use the Open SSL library(default option).  
9. Configuring the line ending conversions. As this is for windows installation we will select the Windows-style option.  
10. Configuring the terminal emulator to use with git bash. Use windows console.  
11. Choosing the default behaviour of "git pull". check Default(fast-forward or merge)  
12. Choose a credential helper. Check Git Credential Manager  
13. Enable file system caching.  
14. Configuring exerimental options. it is on you if you want to enable any option.  
15. Install.  
you have successfully installed Git on your device.  
To check if it is installed correctly you can open command prompt and type "git --version" without quotations. If it shows the git version, Git has been successfully installed.

## Connecting with Visual Studio Code  
If you had Visual Studio Code already installed on your device git should be working 