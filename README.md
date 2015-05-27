<img src="https://avatars1.githubusercontent.com/u/12617483?v=3&s=120" align="right" />
# Polyglotness
> Develop the same project in X different languages.

https://github.com/polyglotness/polyglotness

1. python
2. ruby
3. php
4. c
5. c++
6. c#
7. lua
8. perl
9. go
10. rust
11. julia
12. R
13. Java
14. elixir
15. JavaScript - Node.js

# Why?

The project idea is to motivate programmers to be polyglot and know how to use 15 languages and its specific ecosystem and platform, it is a personal challenge taken by any individual who applies as a CANDIDATE.

Also it is FOR FUN! for community interation, to learn new things, and to compete with others in order to get your Polyglot BADGE!

# Colaborate

New ideas will be always welcome, open an issue!

# Project 

The idea is to develop a simple project in a bunch of different languages to prove your polyglot-ness

This project wants you to perform the following requirements in every language/platform in the list.

1.  Create a command line (CLI) interface handling arguments
2.  Perform HTTP requests to a REST API
3.  Parse a JSON file
4.  Download and save image files locally
5.  Save some data to an SQL database
6.  Create e CRUD tool to admin that database (preferably Desktop Graphical, second web, third cli)
7.  Serve an REST API
8.  Consume a rest API and do interactions which saves data in to a NoSQL database
9.  Send emails
10. Packagement and deploy abilities
11. Write tests (that pass)


## Stories

Only 7 simple user stories, develop each of them in each language.

NOTE: only pass to the next story, once the previous is implemented and tested for every language!

1. As a DEVOPS, I want a COMMAND LINE TOOL, that grabs a GIVEN number of pictures to be downloaded along with its data from instagram API in order to save that data in a local SQLIte database
also saving every image locally, including thumbnails. (see **The Data** for data model)

2. As a DATA QUALITY PERSON I want, preferably a Graphical CRUD TOOL (gui or web), to admin the populated SQLITE database allowing me to edit and add new items.

3. As a DEVELOPER I want a REST API to have READ only access to the data in SQLITE Database.

4. As s TAXONOMIST I want a graphical interface (desktop, mobile or web) to consume that REST API, view the images and its tags, comments and description + the author details.
and allows me to classify that images selecting between 5 categories ('food', 'animal', 'place', 'person', 'object') and I want the classification data to go to a MongoDB Database.

5. As a BOSS I want to receive a daily email resume with the classifications.

6. As a SYSADMIN I want a simple way to perform setup and deploy for the application.

7. As a QUALITY ENGINEER I want to see tests, test coverage and of course, tests passing!


## The Data

Because of Authentication reasons a sample search was made and the data is on
data.json (if needed to host locally) or https://api.myjson.com/bins/2e3xw static API.

The JSON has data from 20 photos on instagram they are under the 'data' key

each item in 'data' has the following significant keys for this project

tags, comments, created_time, caption, user, images

If you like you can substitute the data with a new search on instagram API or even better, add a step to search directly in instagram given a tagname

## Instructions

1. Fork this repository
2. Add your name to CANDIDATES file including a link to your fork and send the PR
2. Develop the project for each language listed
3. Write the tests
4. Adjust your .travis.yml and make it pass the tests
5. Add your name to and a link to travis.yml to POLYGLOTS file and send the PR
6. If everything is ok the PolyglotBot will tell you!

## Rules

### Project structure

You have to keep the code related to each language inside its own folder, you do not have to follow any kind of design pattern, do the way you want since you write the mandatory tests and make it pass on travis CI. Also, you can use third party libs when developing, since they can help abstract some implementations that are not so required for this project.

### CI

Travis CI is the CI of choice because it supports multiple languages in the same repository, there is a file **.travis.yml** in the root of the repository, you just have to register your own fork on travis and fill the travis file with the required steps to deploy, build and test each language project.

### Mandatory tests

There is a bunch of mandatory tests to be written, some of them you will find in test_specs.md file, some of them will be automtically send by PolyglotBot

### Development sequence

You have to follow the order of the stories starting at the number 1, develop the story number 1 for each language, test it and since you develop 1 for avery language you can pass to the story number 2 and then...

### The validation

The Polyglotness Bot is the mind behind the Polyglotness challenge, this bot will keep monitoring every repository listed in CANDIDATES, will do some Data Analisys to be sure that the development flow is something that can be done by a human and nobody tries to cheat on the process. 

But more important than that, we trust you!

Also, the Bot will select 3 new requirements to be developed and will automatically post it as "issue' to every repository listed in CANDIDATES.

There will be some default mandatory tests to be written and the bot will select 3 new test cases to be implemented.

Once someone is validated as a Polyglot that person becomes a member of this organization and will have rights to moderate another applicants if needed.

# Since the 7 stories is implemented and all tests passed!

> Congrats! you are a Polyglot Programmer!

you will get your badge, your name written in our virtual rosseta stone, a sticker and a t-shirt oferred by one of our future sponsors!
