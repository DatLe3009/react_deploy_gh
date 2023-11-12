# Chapter23: Build & Deploy Your React Apps

## deploy with project create-react-app

https://create-react-app.dev/docs/deployment

## npm 

[gh-pages]

## process (continue project 11tut)

### step1: uninstall npm don't use

- run `npm uninstall @testing-library/jest-dom @testing-library/react @testing-library/user-event web-vitals`

### step2: install npm `gh-pages` -D

### step3: in `package.json`

- add `"homepage": "https://myusername.github.io/my-app"`

myusername : DatLe3009

my-app: react_deploy_gh 

- in "scripts": add 

`"predeploy": "npm run build"`

`"deploy": "gh-pages -d build"`

### step4: Create new repository in github is name of project

### step5: create a new repository on the command line

git init

git add .

git commit -m "first commit"

### step6: push an existing repository from the command line

git remote add origin https://github.com/DatLe3009/react_deploy_gh.git

git branch -M main

git push -u origin main

### step7: 

npm run deploy
