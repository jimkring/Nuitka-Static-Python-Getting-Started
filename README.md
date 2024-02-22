# Nuitka-Static-Python-Getting-Started

Steps:

## Installing Nuikta-Python
1. Clone the repo
- `git clone https://github.com/Nuitka/Nuitka-Python.git` to download a copy of the repo into the `Nuitka-Python` folder.
2. Built it from source by running these commands
- `cd Nuitka-Python` to navigate into the Nuitka-Python folder you just cloned
- `.\build.bat -x64` to start the build process (note there are `build.sh` and `build.mac.sh` scripts for Linux and Mac)
3. After the build completes you will have a newly build version of Nuitka-Python in the `output` folder.

Note that you probably want to make a copy of this folder for each project, rather than using it directly, since it self-modifies.

Note: It is a good idea to activate the visual studio developer shell for x64 native (both for building NP and also for running the built NP python.exe when `pip install`ing a package, since it needs to use the same compiler):
"C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Auxiliary\Build\vcvars64.bat"

## Using Nuitka-Python

1. Make a copy of your built nuitka-python:
- Copy the `output` folder to another folder like `my_project_nuitka_static`.
