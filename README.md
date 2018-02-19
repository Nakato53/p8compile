# p8compile


A bash script that allow to create multiple files for your game and compile them in your p8 file.

## Install
```
git clone https://github.com/Nakato53/p8compile.git
mv ./p8compile/p8compile.sh /usr/bin/p8compile ( /usr/local/bin/p8compile for OSX )
chmod +x /usr/bin/p8compile ( /usr/local/bin/p8compile for OSX )
rm -rf p8compile
```

## New game
```
# create a new project folder
mkdir myProject
cd myProject
p8compile myGame
# It will ask for :

PATH of Pico-8 bin ?
/Applications/PICO-8.app/Contents/MacOS/pico8

Name of the game ?
MyProject

Your author name ?
YourName
```

It will create structure :
  - bin/myproject.p8
  - main.lua

main.lua will contain a new project code


## Existing p8 file
```
p8compile myGame
# It will ask for :

PATH of Pico-8 bin ?
/Applications/PICO-8.app/Contents/MacOS/pico8

Name of the game ?
MyProject

Your author name ?
YourName
```

It will create structure :
  - bin/myproject.p8
  - main.lua

main.lua will contain your project code


## And now ?
You now can open you project folder with your prefered editor and organize your code like you want ...

Create files and folders ... organize function by entities etc ...

![Image of project](https://i.imgur.com/N5NfDjQ.png)

To compile all your file, use :
```
p8compile myGame
```

You can add "start" parameter to start pico8 with your game

```
p8compile myGame start
```