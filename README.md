### Boston House Pricing Prediction


### Software and Tools Requirements

1. [Github Account] (https://github.com)

2. [HerokuAccount] (https://heroku.com)

3. [VsCodeIDE] (https://code.visualstudio.com)

4. [GitCLI] (https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

'''
conda create -p venv python==3.7 -y

'''

Configuring git name

'''

git config --global user.name 

'''

Configuring  git Email
'''
git config --global user.email 
'''

## Step 1:  add all files to Repository

'''
git add .

'''
## Step 2: commit message to a current repository

'''
git commit -m "Commit Message"

'''

### Step 3 : Push Data into current Repository that we have created in github we have push that file changes into local system to github repository:

'''
git push origin <Branch_name>

'''

then we will create app.py file 


## after app is Ready

'''
we have to create Proc File 

then we have write below Script:


web: gunicorn app:app

'''

[Deployed Web Application] (https://boston-houseprice1.herokuapp.com/)


## We are Creating an Docker File 

# Whenever We are Considering Github Actions by CI/CD Pipeling

'''
We have to create one folder called .github--> inside that we have to create workflows --> inside that 
you have to create a file main.yaml file


inorder to add secret key  for github actions we have go to github--> Settings--> Secret-->Dependatbot

Add Name : HEROKU_API_KEY
API Key {that has to be copied from heroku}

# we have to create two other Secret keys 




'''

