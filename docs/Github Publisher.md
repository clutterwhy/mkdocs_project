---
share: true  
---

|Repo name|username|branch|
|:-:|:-:|:-:|
|mkdocs_project|clutterwhy|main|

- Python
	- Download Python installer https://www.python.org/downloads/
	- Install the python installer
	- Commands
		- python3 --version
			- return "Python 3.11.1"
		- python3
			- enter Python mode in terminal
		- exit ()
			- tells Python to close the interpreter
		- pip3 install bs4
			- install the pip library onto the system
	- create python virtual environment 
		- `cd desktop`
		- run `python3 -m venv pip_install`
		- `cd pip_install`
		- `pip3 install --upgrade pip`
- mkdocs
		- installation
			- pip3 install mkdocs
			- `mkdocs --version` to view the version
		- New project
			- run `mkdocs new my-project` 
			- `cd my-project`
		- Commands
			- `mkdocs new [dir-name]` - Create a new project.
			- `mkdocs serve` - Start the live-reloading docs server.
				- http://127.0.0.1:8000
			- `mkdocs build` - Build the documentation site.
- Github
	- Create a new repo
		- Add .gitignore for python
	- Get repo git into project folder
		- git clone https://github.com/clutterwhy/mkdocs_project.git
		- move the mkdocs `docs` folder into the github folder
	- Build from project folder
		- mkdocs gh-deploy
			- clutterwhy / 2020Singapore.
			- git remote add origin https://github.com/clutterwhy/mkdocs_project.git
			- token: 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
			- git clone https://github.com/clutterwhy/mkdocs_project.git
- Plugin
	- 