# Ultimate Windows Toolbox
This script is the culmination of many scripts and gists from github with features of my own. I am building this script to be a swiss army knife of Windows tools to help setup and optimize machines.

## My Additions
- One command to run
- Full GUI implementation
- Winget install
- Install popular programs with one click
- O&O Shutup 10 CFG and Run
- Dark/Light mode
- Semi-configurable

## How to Run
Paste this command into Powershell (admin):
```
# Long URL
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/thegamerhat/old-win10-utility/master/old-win10-utility.ps1'))

# Short URL
iex ((New-Object System.Net.WebClient).DownloadString('https://bit.ly/3bv7jOE'))
```
Or, shorter:
```
# Long URL
iwr -useb https://raw.githubusercontent.com/thegamerhat/old-win10-utility/master/old-win10-utility.ps1 | iex

# Short URL
iwr -useb https://bit.ly/3bv7jOE | iex
```

For complete details check out https://christitus.com/debloat-windows-10-2020/
