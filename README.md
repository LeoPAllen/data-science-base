# data-science-base

A base repo for data science projects. Clone this repo and change the repo name
and its remote configurations to start a new datascience project. Change the
README before pushing to github. Change the conda enviroment name in environment.yaml before creating
a new virtual environment. Add packages needed for for specific projects to the version of environment.yaml in the **renamed** repo.

##### Run The Following To Build A New Environment:
```
conda env create -f=environment.yml
```

##### Run The Following To Update An Environment:
```
conda env update -f=environment.yml
```

###### Create a .env File With Environment Variables By Running The Following:
```
nano .env
```
Make sure .env is on your global .gitignore file in your home directory and has
been added to your global exclusions.

##### Activate Environment By Running:
```
conda activate your_environment_name
```

