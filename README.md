# p8compile


A bash script that allow to create multiple files for your game and compile them in your p8 file.

##How to use
```
git clone
cd p8compile
mv p8compile.sh /usr/bin/p8compile ( /usr/local/bin/p8compile for OSX )
chmod +x /usr/bin/p8compile

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

#It will create structure :
  - bin/myproject.p8
  - main.lua

 
```
