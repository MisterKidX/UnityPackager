# UnityPackager
Packaging template for Unity. this is a template repo, intended for you to copy and work on your own repo. 

Useful links:
* [Unity Manual Custom Packages](https://docs.unity3d.com/Manual/CustomPackages.html)
* [Unity Manual Packages](https://docs.unity3d.com/Manual/Packages.html)


## Quickstart

### Creating your own package

* to get started create a repo from this [template](https://github.com/MisterKidX/UnityPackager/generate)
* after the repo creation, clone it to your computer
* to *cleanly work* on your new package, you will need to open it in a unity project; just make sure you don't push any garbage that doesn't belong to the original package structure

### Installating your Package in a new Unity Project

* Go to the Package Manager
* Click the + button at the top left and choose Add Package from Git URL
* Enter your package repo's Git HTTPS (example: https://github.com/<username>/<reponame>.git)
* The package will be listed under the packages folder and will act like all packages
* Enjoy! 

### the upm package manifest
* Go over the package.json and change all relevant data
* You can add a "dependencies" entry and specify other packages that this package depends on
* When changing the name of the package, make sure to go the the .asmdef files and Documnetation and change their names respectively

## Package Manifest

### Git Dependencies
you can use the "depedencies" key to add your own git dependencies. Check out Unity's documentation at https://docs.unity3d.com/Manual/upm-git.html

## General

* If you want to nest packages use dependencies or [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
