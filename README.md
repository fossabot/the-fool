# The Fool
## A tarot card game
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcbanisi%2Fthe-fool.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcbanisi%2Fthe-fool?ref=badge_shield)


## A bearly software game

-------------------------------------
To run the Docker image on local dev:
-------------------------------------
1) Install Docker Community Edition (https://www.docker.com/get-docker)

2) `docker run -p 8000:8000 -v <FULL_PATH_TO_CLONED_REPOSITORY>:/app/ bearlysoftware/the-fool-dev`

3) Browse to http://localhost:8000/game/

---------------------------------
To run unit tests: `python manage.py test --pattern="*Test*.py"`

To run server: `python manage.py runserver` 
(then browse to http://localhost:8000/game/)

[<img src="https://travis-ci.org/bearly-software/the-fool.svg?branch=master">](https://travis-ci.org/bearly-software/the-fool)

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcbanisi%2Fthe-fool.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcbanisi%2Fthe-fool?ref=badge_large)