Heroku buildpack: Redline Smalltalk
===================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for Redline Smalltalk apps.


Usage
-----

[Detailed Example](https://gist.github.com/gists/4129809)

Quick Example:

    $ heroku create --buildpack https://github.com/will/heroku-buildpack-redline.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Redline Smalltalk app detected

Hacking
-------

To use this buildpack, fork it on Github.  Push up changes to your fork, then create a test app with `--buildpack <your-github-url>` and push to it.

Note: You will need to have your build copy the necessary jars to run your application to a place that will remain included with the slug.

Commit and push the changes to your buildpack to your Github fork, then push your sample app to Heroku to test.

License
-------

Licensed under the MIT License. See LICENSE file.
