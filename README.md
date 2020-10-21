Small app that opens Jupyter Notebooks on double click. The app opens `.ipnyb` files using nbopen on macOS.  

To install this app, first make sure you have [brew](https://brew.sh/index) and [python3](https://www.python.org) installed. 
Then run 
``` 
brew tap alexarntzen/homebrew-alex;
``` 
in the terminal to tap my homebrew tap. Then run 
``` 
brew cask install open-jupyter-notebook;
``` 
to install the app. 


When the app is installed, right click on a `.ipnyb` file, and select open with `Open Jupyter Notebook`. You can then set this option as default.


The open script for jupyter notebooks is copied from sahuja's answer on [stackoverflow](https://stackoverflow.com/questions/16158893/open-an-ipython-notebook-via-double-click-on-osx/46995543).
