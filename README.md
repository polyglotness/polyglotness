# Polyglotness

Develop the same project in X different languages.

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

Only 7 simple user stories

1. As a DEVOPS, I want a COMMAND LINE TOOL, that grabs a GIVEN number of pictures and its data from instagram API in order to save that data in a local SQLIte database
also downloads and saves locally every image, including thumbnails from that items in the JSON returned by the API. (see **The Data** for data model)

2. As a DATA QUALITY PERSON I want, preferably a Graphical CRUD TOOL, to admin the populated SQLITE database allowing me to edit and add new items.

3. As a DEVELOPER I want a REST API to have READ only access to the data in SQLITE Database.

4. As s TAXONOMIST I want a graphical interface (desktop, mobile or web) to consume that REST API, view the images and its tags, comments and description + the author details.
and allows me to classify that images selecting between 5 categories ('food', 'animal', 'place', 'person', 'object') and I want the classification data to go to a MongoDB Database.

5. As a BOSS I want to receive an email notification resume with the classifications.

6. As a SYSADMIN I want a simple way to perform setup and deploy for the application

7. As a QUALITY ENGINEER I want to see tests, test coverage and of course, tests passing!


## The Data

Beacuse of Authentication reasons a sample search was made and the data is on
data.json (local file if needed to host locally) or https://api.myjson.com/bins/2e3xw static API.

The JSON has data from 20 photos on instagram they are under the 'data' key

each item in 'data' has the following significant keys for this project

tags, comments, created_time, caption, user, images

If you like you can substitute the data with a new search on instagram API or even better, add a step to search direclty in instagram given a tagname

## Instructions

1. Fork this repository
2. Add your name to CANDIDATES file including a link to your fork and send the PR
2. Develop the project for each language listed
3. Write the tests
4. Adjust your .travis.xml and make it pass the tests
5. Add your name to and a link to travis.yml to POLYGLOTS file and send the PR
6. If everything is ok!

> Then

# Congrats! you are a Polyglot Programmer!
you will get a sticker and a t-shirt oferred by one of our sponsors!
