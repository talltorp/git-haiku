# git-haiku
 Add ancient Japanese poetry to your commits in a `prepare-commit-msg` hook.

<img width="960" alt="git haiku overview" src="https://user-images.githubusercontent.com/1172400/232972961-dcf1f610-a8b1-4e8e-998b-b1be8f177fd0.png">


## How to install on Mac
1. Set your open ai token

`export HAIKU_OPEN_AI_TOKEN=<your-open-ai-token>`

2. Create the file in your repository

`touch .git/hooks/prepare-commit-msg`

3. Make the file executable

`chmod +x .git/hooks/prepare-commit-msg`

4. Copy the beautiful ruby code found in [hooks/prepare-commit-msg](hooks/prepare-commit-msg) into your file and press save.


## DEMO

https://user-images.githubusercontent.com/1172400/232891373-aee53c5e-da9a-4a7c-8329-313f9e1187b7.mov


