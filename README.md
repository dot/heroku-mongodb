# heroku-mongodb

tiny wrapper for mongodb

## Installation

```
$ git clone git://github.com/dot/heroku-mongodb.git
$ heroku plugins:link <to heroku-mongodb dir>
```

## Usage

### Compose

```
$ heroku compose:dump --help
Usage: heroku compose:dump

mongodump for compose mongodb

 -a, --app APP       # app to run command against
 -o, --output OUTPUT # destination for output
 -r, --remote REMOTE # git remote of app to run command against
```
