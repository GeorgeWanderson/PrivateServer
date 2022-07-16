
# OBSERVATIONS ⚠️

This is a clone made for using in 2022. You can find the original creator here: [Ogar](https://github.com/OgarProject/Ogar).
We made small updates in this repositorie for using bots and multiplayer server.
Read the description of client and server, thanks.


>---

# Information 📃
Current version : **1.6.1**

![Language](https://img.shields.io/badge/language-node.js-yellow.svg)
[![License](https://img.shields.io/badge/license-APACHE2-blue.svg)](https://github.com/Barbosik/OgarMulti/blob/master/LICENSE.md)

Original MultiOgar code is based on the private server implementation [Ogar](https://github.com/OgarProject/Ogar). The original code rightfully belongs to the [OgarProject](https://github.com/OgarProject).

MultiOgar-Edited code however, is based on MultiOgar code that has been heavily modified and improved by many collaborators. The overall goal of this fork is to make physics as vanilla as possible, cleanup most of the code, and add lots of new features while maintaining better performance than the original MultiOgar.

>---

# Installation 💻
## Windows

1. Download and install node.js: https://nodejs.org/en/download/
2. Download this repo
3. Unzip MultiOgar-Edited code into some folder.
4. Run the win-Install_Dep.bat file.
5. Run win-Start.bat

**All these files can be found in the `run` folder.**


### Installing required modules.

```batch
:: Install Required Modules.
npm install

:: Starting the server.
cd src
node index.js
```

## Linux:
```bash
# First update your packages:
sudo apt-get update

# Install git:
sudo apt-get install git

# Install node.js:
sudo apt-get install nodejs-legacy npm

# Clone MultiOgar-Edited:
git clone git://github.com/Megabyte918/MultiOgar-Edited.git

# Install dependencies:
cd MultiOgar-Edited
npm install

# Run the server:
cd src
sudo node index.js
```

