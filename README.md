# TemDataBrowser
A graphical user interface based on ScopeFoundry for viewing TEM data.

![GUI example](https://github.com/ercius/TemDataBrowser/blob/main/TemDataBrowser_window.png?raw=true)

# Installation
First install QT bindings. For example:
`pip install PyQt5`

Then install this package and the rest of the dependencies:

`pip install TemDataBrowser`

# Running the GUI

## From a python interpreter
Start python interpreter, import the package, and run the `open_file` function:

`$ python`

`>>> import TemDataBrowser`

`>>> TemDataBrowser.main()`

to start the graphical user interface. No file name is required.

## From the command line

A script should be installed on your system such that opening a command line
and typing `TemDataBrowser` will open the graphical uiser interface.
