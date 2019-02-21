# pn_setup_instructions
Basic computer setup instructions for Project Night challenge participants.

## Install Python
We use only Python3 at Project Night. We currently recommend [3.6.x](https://www.python.org/downloads/release/python-368/) (as of 2019/02/21) for broad library compatibility.

## Install a Text Editor
We encourage either [Sublime Text 3](https://www.sublimetext.com/3) or [Atom](https://atom.io/) because they're free, cross-platform, relatively simple for all participants to use, and memory efficient. However, feel free to use a comparable editor. Please avoid using custom keybindings such as Vim or Emacs to ease development by all group participants during challenges.

## Download the Repository
If you are familiar with git, run:
```
  git clone https://github.com/chicagopython/<repo_name>.git
```
If not:
 1. Go to https://github.com/chicagopython/<project_name>
 2. Click on "Clone or download" > "Download ZIP" and unzip the file that gets downloaded
 3. From your command line, change directories to the path where you unzipped the repository:

	On linux or OS X: `cd path/to/project`
	
	On Windows: `cd path\to\project`


## Set up virtualenv
If you are using Linux or OS X, run the following to create a new virtualenv:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
On Windows, instead run the following:
```
python3 -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```
