# React-Native App
This is my first app on React Native which play some preloaded albums music.

## Project Setup:
This Project requires Android Sdk, react-native cli, git-bash, node.js, some editor like Atom, sublime, brackets etc.

*Duh - My fav is ATOM.*

#### How to run the program in virtual machine:
1. Open your terminal to first install react-native cli on your pc by typing command
    npm install -g react-native-cli
2. Then you have to install and setup the android studio.
3. After that you just have choose any directory you like, in my case I choose the D:/ partition hard disk for this. So, it totally depend on yours. So, for downloading
the react-native package. You just have to type this command
    react-native init practice
    *Note in my case react-native latest version is not compatible, so I have installed
    the downgrade version of it. Type this command, if you faced any problem regarding
    to version*
    react-native init --version="0.55.4" practice
4. After that long process of downloading over terminal, you have to setup the android Sdk.
First, you have to import the downloaded directory of the android sdk to android studio,
Secondly, after above process you have to install an emulator by going to tools, then avd
manager. In this you have to download the version of marshmallow of API 23, which is
totally compatible for this app.
5. At last, after doing all that above steps, go to terminal and type command
react-native run-android                #for android users
react-native run-ios                    #for ios users

This may take some time. This loading and building the app totally depends on how fast
your PC is.

## Expected Output:
