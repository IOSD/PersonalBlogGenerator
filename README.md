# Personal Blog Generator

A static website generator made as a part of  IOSD winter projects.

### Prerequisite

- Python
- HTML/CSS
- Markdown

### Steps

- Making a Command Line Tool in Python using predefined libraries to serve as interface with our **generator**
- Taking a Structured Markdown File and compiling it to a HTML Page using a python script.
- Using the generation code and generating the *index* , *about* and a *collection* of post.
- Adding Custom Themes to the project
- Adding Customization options for Generation  , Variables Injection in Templates and many other features (Depending upon your creativity)
- Finishing the Project and Making a Python Package.



### Task 1

![](https://img.shields.io/badge/team-a-green.svg?style=for-the-badge) ![](https://img.shields.io/badge/team-b-green.svg?style=for-the-badge)

- Make a command line tool in Python which responds to following commands :
  - `create` - Initializes a new site at a given path
  - `gen` - Generates the website to a configured deploy folder
  - `serve` - Starts a local http server that regenerates based on the requested file
- Tool must have a `-h`  and `-v` flag for displaying *help* and *version* respectively.
- Each Command must have it's own `-h` flag for displaying a short description and listing all available options.
- [Click Python Library](http://click.pocoo.org/5/) can be used for making the tool.