# apps-n-settings
Just some apps and settings I use for my work environment.

- [Sublime](#sublime)
- [Cmder (Windows)](#cmder)
- [Postman](#postman)
- [OS Extensions](#os-extensions)

## Sublime
- Install [Sublime Text 3](http://www.sublimetext.com/3)

- Enter license key (check email)
- Install [Package Control](https://packagecontrol.io/installation)
- Close Sublime

- Install the following packages:
  - Babel
  - BracketHighlighter
  - Color Highlighter
  - GitSavvy
  - LESS
  - Markdown Preview
  - Predawn Monokai
  - Pretty JSON
  - SideBarEnhancements
  - TernJS
  - Text Pastry
  - Theme - Flatland
  - DocBlockr
- Close Sublime
- Copy files from the [sublime folder](sublime) into *Packages/User/* (get full location from Preferences -> Browse Packages...). Make sure to get the right platforms.
- In `GitSavvy.sublime-settings`, edit the git executable path

- View -> Side Bar -> Show Open Files

## Cmder
*Windows*  
Shell app setup to use git bash  

- Install [cmder](http://cmder.net/)

For minimal setup
- In Settings -> Startup -> Tasks
  - Click '+' to add new task, name it 'GitBash'
  - Hotkey: LCtrl+N
  - Task parameters: `/dir "D:\dev"` (or whatever start directory)
  - Commands: `"C:\Program Files (x86)\Git\bin\bash.exe" --login`
- In Settings -> Startup
  - Choose *Specified named task* and select `{GitBash}` 

Or import [settings](cmder/cmder.xml)

## Postman
REST client  

[Download here](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en)

## OS Extensions

ClipX (Windows): [download](http://bluemars.org/clipx/)  

Alfred2 (OS X): [download](https://www.alfredapp.com/)
  - Set Powerpack license (check email)
  - Set terminal to iTerm2 with [this applescript](https://github.com/stuartcryan/custom-iterm-applescripts-for-alfred) for Custom
  - Add [custom web searches](http://alfredtips.com/s/popular/1/)
