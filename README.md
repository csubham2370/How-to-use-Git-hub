# How-to-use-Git-hub

## create a new repository on the command line
* echo "# How-to-use-Git-hub" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/csubham2370/How-to-use-Git-hub.git
* git push -u origin main
*  #--------------------------------------------------------------------------------------
## push an existing repository from the command line
* git remote add origin https://github.com/csubham2370/How-to-use-Git-hub.git
* git branch -M main
* git push -u origin main
  *  #--------------------------------------------------------------------------------------
  ## Clone the repository: git clone
  * git clone <repository_url>
  
  
## To generate a requirements.txt file for your Python project, you can use the following command in your project directory:
* pip freeze > requirements.txt
## If you already have a requirements.txt file and want to install the dependencies listed in it, you can use the following command:
* pip install -r requirements.txt

## Creating a virtualenv
* py -m venv .venv
## Activate a virtual environment
* .venv\Scripts\activate
* To confirm the virtual environment is activated, check the location of your Python interpreter:
* where python
* .venv\Scripts\python
## Deactivate a virtual environment
* deactivate
