# apps-n-settings
Just some apps and settings I use for my work environment.

- [Sublime](#sublime)
- [Cmder (Windows)](#cmder)
- [Postman](#postman)

## Sublime
- Install [Sublime Text 3](http://www.sublimetext.com/3)
- Enter license key (check email)
- Install [Package Control](https://packagecontrol.io/installation)
- Close Sublime
- Copy files from the [sublime folder](sublime) into *Packages/User/* (get full location from Preferences -> Browse Packages...)
- TODO: GitSavvy config is windows specific
- TODO: add mac keybinds

## Cmder
*Windows*  
Shell app setup to use git bash  

- Install [cmder](http://cmder.net/)
- In Settings -> Startup -> Tasks
  - Click '+' to add new task, name it 'GitBash'
  - Hotkey: LCtrl+N
  - Task parameters: `/dir "D:\dev"` (or whatever start directory)
  - Commands: `"C:\Program Files (x86)\Git\bin\bash.exe" --login`
- In Settings -> Startup
  - Choose *Specified named task* and select `{GitBash}` 

## Postman
REST client  

[Download here](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en)
