# MonkeyTalk

MonkeyTalk is a web application inspired by reddit in which a user can post a
topic (usually a link) in which others will be able to comment and vote on.
Users are able to create an account by signing up, which will require a standard
email and password in addition to the username to be displayed. This information
can always be adjusted by going to the accounts page. Once authenticated, a user
can make comments and vote on links posted by others as well as edit or share
their own links. One can still view links without authentication however other
options are restricted.

## Live Demo

A demo version of this project can be viewed
[Here](https://monkeytalk.herokuapp.com/)

## System Requirements:

1. Ruby

   This project requires ruby version 2.2 or greater to be installed on the
   system.

   #### \*Note: for ruby version >= 2.4, gems (particularly json) may need updating

2. Sqlite3 is required for database storage (development)

3. PostgreSQL is required for production database


## Startup

Within the project directory, install the necessary dependencies then run the
server.

* Install dependencies:

```
  bundle install
```

* Migrate database

```
  rake db:migrate
```

* Start rails server:

```
  rails s
```

* View site on localhost:3000
