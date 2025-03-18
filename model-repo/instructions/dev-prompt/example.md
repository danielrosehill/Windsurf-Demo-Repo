# Example Development Prompt

Your task is to develop a Python GUI for Linux.

You should use a library like Pyqt 6 or Pyqt 5. 

Here's what I would like the GUI to do:

## Intended Features

- The GUI should provide a convenient interface for quickly creating Github repositories that are intended to be used with the Windsurf IDE. 
- The GUI should have a text field called rules in which the user populates text in markdown. When the repository is created, this file should be generated in the repository (at its base) as .windsurfrules. 
- There should be a toggle for public and private. If the user chooses public then a public repository is created and if the user chooses private then the repository will be created with private settings. 
- There is a Github PAT in the environment variables file that you can use for this project. 