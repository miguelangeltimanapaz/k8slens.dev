# k8slens.dev
This project help you to compile the binaries of project https://github.com/lensapp/lens

# Windows:

# Requirements
* Install node [v16.20.2](https://nodejs.org/dist/v16.20.2/node-v16.20.2-x64.msi)
* execute command: #>npm install -g npm@9.6.7
* Install [python-3.6.8-amd64.exe](https://www.python.org/ftp/python/3.6.8/python-3.6.8-amd64.exe)
* Install Visual Studio 2017 Community (using the "Desktop development with C++" workload), for more detail https://github.com/Microsoft/nodejs-guidelines/blob/master/windows-environment.md#compiling-native-addon-modules

# Steps
* execute command: #>npm install 
* execute command: #>npm run build:app
  If you have this problem:
  Something went wrong installing the "sharp" 
  module Cannot find module '../build/Release/sharp-win32-x64.node'
  Execute:
  #>npm cache clear
  #>npm rebuild --verbose sharp

# Linux:

# Requirements
* Install node v16.20.2 
* execute command: #>npm install -g npm@9.6.7

# Steps
* execute command: #>npm install 
* execute command: #>npm run build:app


![alt text](https://github.com/miguelangeltimanapaz/k8slens.dev/blob/main/images/k8slens1.png?raw=true)

![alt text](https://github.com/miguelangeltimanapaz/k8slens.dev/blob/main/images/k8slens2.png?raw=true)

![alt text](https://github.com/miguelangeltimanapaz/k8slens.dev/blob/main/images/k8slens3.png?raw=true)
