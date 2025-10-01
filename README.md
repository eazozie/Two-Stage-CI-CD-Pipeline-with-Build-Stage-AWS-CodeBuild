

# A Two-Stage CI/CD Pipeline Setup with a build stage - AWS CodeBuild


##Project Details:

-	I will be setting up a two-stage CI/CD pipeline using CodePipeline with a build stage to stimulate an application build - AWS CodeBuild 
-	I will be installing Python 3.9
-	Check the version of Python installed.
-	Display my name (Ebubechukwu Azozie) on the simple my_app.py
-	Run my_app.py

## Resources to use

-	Source: GitHub 
-	Target: AWS CodeBuild
-	Orchestrator: AWS CodePipeline


## Step 1

I created a GitHub remote repository and cloned it to my local repository 
eazozie/Two-Stage-CI-CD-Pipeline-with-Build-Stage-AWS-CodeBuild

## Step 2 

-	I created my Python file named ‘my_app.py’ to print my name ‘Ebubechukwu Azozie’
-	I also created a buildspec.yml file and configured my build
-	I successfully sent the files to my GitHub remote repository


<img width="975" height="694" alt="image" src="https://github.com/user-attachments/assets/611d4e8b-b090-4d35-8987-97baad0858fc" />


## Step 3

I created an AWS CodePipeline with a source and a build stage

Source: GitHub 
Target: AWS CodeBuild


I successfully created a working AWS CodePipeline with a source and a build stage


<img width="975" height="469" alt="image" src="https://github.com/user-attachments/assets/e7dce5d7-924a-42e9-8466-3a05c5a48729" />



Checking the build logs from my AWS CodeBuild console


<img width="975" height="606" alt="image" src="https://github.com/user-attachments/assets/905d9d1f-098d-4088-947c-dee0f4642290" />





