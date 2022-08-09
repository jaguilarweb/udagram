# Pipeline 

## Overview

A github accout is mandatory

1.- Create a Github repository with the code to deploy
2.- Add config.yml file
3.- Connect your Github account with the CircleCI
4.- Select the repository with your aplication
5.- Provide the branch name that contains the .circleci/config.yml file
6.- Set up the project (click the buttom)

You can see the command execution included in your config.yml file if you click the "build" link.

The CircleCi follow the next steps (included in the config.yml file):

- Spin up environment
- Preparing environment variables
- Install NodeJS code
- Install NPM
- Checkout code
- Build
- Deploy

## Pipeline Diagram

![](https://github.com/jaguilarweb/udagram/blob/master/documentation/pipeline-diagram.png)
