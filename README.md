# How to make a repo and upload it to Github?
*This is a simple test from Level0-week2* 

### 1. Create your repo on Github


The Github UI is easy to use, just click on new repo and choose if it will be public or private, with README file or not..

### 2. Initialize your repo locally 

- Make sure your are in the right folder of the project by using the cmd `cd path`
- Use the cmd `git init`

### 3. Create your files

Like the README file, or others up to the language your are using

### 4. Stage your changes

Use the cmd `git add .` to add everything, or simply `git add README.md` to add changes of a specific file (the README file in this case)

### 5. Commit your changes with a meaningful message as best practices

Use the cmd `git commit -m "First version of the README file"` 

### 6. Push them to the remote repo

- First copy the link of your repo from Github
- Link your local repo to Github by using the cmd `git remote add origin the link`
- Then use the cmd `git push -u origin main`

