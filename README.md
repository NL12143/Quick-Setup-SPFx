Quick setup for SPFx dev station

Reference:  
https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-development-environment 

NodeJS
------
Install NodeJS Long Term Support (LTS) version. 
If you have NodeJS already installed please check you have the latest version using node -v. 
It should return the current LTS version. 

node -v

npm install -g npm@3.

Install a code editor 
---------------------
Visual Studio Code

Install Yeoman and gulp
-----------------------
npm install -g yo gulp
npm install -g @microsoft/generator-sharepoint
npm install @microsoft/generator-sharepoint --save-dev
