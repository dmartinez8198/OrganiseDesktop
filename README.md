# OrganiseDesktop

Takes all the files on your desktop and put them in folders according to extensions. NO MORE MESSY DESKTOPS!
At least not on the outside :)

# Installation Guide:
1) Download the repo
2) Run the "activate" Shell Script inside the Organise Desktop folder
3) Open Clean.py inside OrganiseDesktop/organise_desktop

# Demo
![Screenshot](demo1.png)

The buttons are `Clean`, `Exit`, `Undo`, `Schedule`, `Remove Schedule` and do exactly as they are implied.

# Proposed UI
![ProposedUI](https://user-images.githubusercontent.com/28908100/80692304-019d4400-8a97-11ea-99e1-70fd28fb2325.png)

Our proposed UI would be integrated into the operating system and be configured as an option that can be selected once an icon is right-clicked.

# Proposed Changes

Some of the changes we would like to see implemented into this project in the future would be the Proposed UI mentioned above. Additionally, while the program does create folders to organize the desktop icons into it would be better to also organize icons within the folders based on extensions by creating additional folders within the created folders basing them on specific extensions. 

# Prerequisites

All the necessary packages are mentioned in requirements.txt. They can be installed by

running `pip install -r requirements.txt` or using ``pipenv install`` and it will automatically detect the `requirements.txt` and setup an enviroment for you. For development purposes, I suggest you create a
virtual environment or use a dependency manager like [pipenv](https://github.com/pypa/pipenv) to keep a clear state, separate from your own setup.

The activate.sh script has been provided to ensure a standard development environment. To create the environment if it doesn't already exist, or simply load it otherwise, run `source ./activate.sh`

You can also use docker in combination with pipenv, [here](https://github.com/dfederschmidt/docker-pipenv-sample) you have an example.

If you do not want to create a virtual environment, just run the pip command above and ignore the following. Otherwise, the activate.sh script will handle the creation and loading of the virtual environment with all the necessary dependencies. Furthermore, once a new dependency is established, remove requirements.txt and please run `pip freeze > requirements.txt` to generate a new file that should be committed to version control.

Python3 Instructions:
`python -m venv organise_desktop`

To activate it, run `source organise_desktop/bin/activate`

### Build from Source

`$ git clone https://github.com/blavejr/OrganiseDesktop.git`
Navigate to the repo and run the following command:
`$ pip install -r requirements.txt`

# Contributing
Please read the [Contributing Guidlines](https://github.com/blavejr/OrganiseDesktop/blob/master/CONTRIBUTING.md) for details about pull requests, bug reports or opening an issue. 
