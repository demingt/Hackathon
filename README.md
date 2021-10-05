# Starter Pack
hustle for the win

# quick installation start

unzip

In the command line, navigate to the root directory of the unzipped folder.

Initialize the local directory as a Git repository.

`git init main`

To create a repository for your project on GitHub, use the `gh repo create` subcommand. Replace `project-name` with the desired name for your repository. 

`gh repo create project-name`

Follow the interactive prompts. 

Pull changes from the new repository that you created. 

`git pull --set-upstream origin main`

Stage, commit, and push all of the files in your project.

`git add . && git commit -m "initial commit" && git push`

create a virtual environment for your project
`python3 -m venv hackathonenv`

`hackerthonenv\Scripts\activate`

`pip install -r requirements.txt`

`flask run`

# commands to write for setting up

`python3 -m venv hackerthonenv`

# start the virtual environment

`hackerthonenv\Scripts\activate`

# to deactivate the virual environment

`deactivate`

# command to update the dependency used

`python -m pip freeze > requirements.txt`


