## git Quick Help Reference

#### Setting up git global settings
```
git config --global user.name "<USERNAME_HERE>"
git config --global user.email "<EMAIL_HERE>"
```

#### Checking out a git repo from a previously established source
```
cd <PARENT_FOLDER_OF_DESIRED_GIT_LOCATION>
```
####### THEN, CHOOSE ONE OF THE FOLLOWING:
  1. `git clone ssh://<INSERT_APPLICATION_KEY_HERE><INSERT_USERNAME_HERE>@<INSERT_IP_TO_HERE>/path/to/my-project.git`
  2. `git clone http://<INSERT_APPLICATION_KEY_HERE><INSERT_USERNAME_HERE>@<INSERT_IP_TO_HERE>/path/to/my-project.git`

#### Creating a git repo from scratch
```
mkdir <YOUR_NEWLY_CREATED_GIT_DIR>
cd <YOUR_NEWLY_CREATED_GIT_DIR>
git init
```

#### Check git status
1. Short Status: `git status -s`
2. Long Status: `git status`
