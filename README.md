# git-haiku
Add ancient Japanese poetry to your commits in a `prepare-commit-msg` hook.

Created by: [@tobiastalltorp](https://twitter.com/tobiastalltorp)

<img width="960" alt="git haiku overview" src="https://user-images.githubusercontent.com/1172400/232972961-dcf1f610-a8b1-4e8e-998b-b1be8f177fd0.png">

## Features
### @levelsio mode
Pieter Levels writes no commit message before pushing to production.   
https://twitter.com/levelsio/status/1590908364393156608?s=20

That shouldn't stop him from getting some poetry into his deploys!

Here's an example of a haiku written for an **empty commit message** 👇

<img width="784" alt="levelsio mode" src="https://user-images.githubusercontent.com/1172400/232976631-282c0fef-6e42-4138-bfae-469da4ebdb39.png">



## How to install on Mac
1. Set your open ai token

`export HAIKU_OPEN_AI_TOKEN=<your-open-ai-token>`

2. Create the file in your repository

`touch .git/hooks/prepare-commit-msg`

3. Make the file executable

`chmod +x .git/hooks/prepare-commit-msg`

4. Copy the beautiful ruby code found in [hooks/prepare-commit-msg](hooks/prepare-commit-msg) into your file and press save.

5. Make a commit with a title 

`git commit -m "initial commit"`

6. Haiku added to your commit description 🌸


## DEMO

https://user-images.githubusercontent.com/1172400/232891373-aee53c5e-da9a-4a7c-8329-313f9e1187b7.mov


