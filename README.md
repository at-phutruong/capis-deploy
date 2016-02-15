# Minagine New

Management System App

# How to Install

Step 1: Clone repo
```
$ git clone git@github.com:team-hurricane/minagine_renew.git
```

Step 2: Create database.yml and secrets.yml
```
$ cp config/database.yml.example config/database.yml
$ cp config/secrets.yml.example config/secrets.yml
```

Step 3: Install gem dependencies
```
$ bundle install
```

Step 4: Install packages via Bower. We need to install bower before. See http://bower.io/ to install bower if not yet.
```
$ bower install
```

Step 5: Run App
```
$ bundle exec rails s -b 0
```
