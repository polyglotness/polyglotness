# Polyglotness tests specification

For each user story there is some mandatory tests to write and make them to pass in travis CI, as each language has a different method for unittests, you can choose any unittest framework since it is supported by Travis.

## Tests for each story

1. As a DEVOPS, I want a COMMAND LINE TOOL, that grabs a GIVEN number of pictures and its data from instagram API in order to save that data in a local SQLIte database
also downloads and saves locally every image, including thumbnails from that items in the JSON returned by the API. (see **The Data** for data model)

    test_the_url_returns_a_valid_json
    test_the_json_has_the_mandatory_fields (the list is "the data" in readme)
    test_the_image_limit_argument_is_a_valid_integer

2. As a DATA QUALITY PERSON I want, preferably a Graphical CRUD TOOL, to admin the populated SQLITE database allowing me to edit and add new items.

3. As a DEVELOPER I want a REST API to have READ only access to the data in SQLITE Database.

4. As s TAXONOMIST I want a graphical interface (desktop, mobile or web) to consume that REST API, view the images and its tags, comments and description + the author details.
and allows me to classify that images selecting between 5 categories ('food', 'animal', 'place', 'person', 'object') and I want the classification data to go to a MongoDB Database.

5. As a BOSS I want to receive an email notification resume with the classifications.

6. As a SYSADMIN I want a simple way to perform setup and deploy for the application

7. As a QUALITY ENGINEER I want to see tests, test coverage and of course, tests passing!
