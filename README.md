# UnityPackager
Packaging template for Unity.

https://docs.unity3d.com/2019.3/Documentation/Manual/CustomPackages.html

## Installating the Package in Unity

* Go to the Package Manager
* Click the + button at the top left and choose Add Package from Git URL
* Enter this Git's HTTPS (https://github.com/MisterKidX/UnityPackager.git)
* The package will be listed under the packages folder
* Enjoy! 

## Use Guide

* Go over the package.json and change all relevant data
* You can add a "dependencies" entry and specify other packages
* When changing the name of the package, make sure to go the the .asmdef files and Documnetation and change their names respectively
* Now you can upload your own git repo and use the layout there
* Follow the Installation guide to install your package in a unity project

## General

* If you want to nest packages use dependencies or [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
