# Heroku buildpack: MongoDB

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run mongo commands (http://www.mongodb.org/).

It installs MongoDB 4.0.4 for Ubuntu 18.04 or 16.06 from https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu1804-4.0.4.tgz or https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu1604-4.0.4.tgz

Usage
-----

Example usage:

    $ heroku create myapp --buildpack http://github.com/Lendix/heroku-buildpack-mongo.git
    $ git push heroku master
    
or:

    $ heroku buildpacks:add http://github.com/Lendix/heroku-buildpack-mongo.git
