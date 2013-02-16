# heroku-buildpack-multi

Use multiple buildpacks on your app

## Usage

    $ heroku config:add BUILDPACK_URL=https://github.com/nprokopev/heroku-buildpack-multidir.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#versions
    https://github.com/heroku/heroku-buildpack-ruby.git
