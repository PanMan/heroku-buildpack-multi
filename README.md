# heroku-buildpack-multi

Depreciated, as Heroku supports multiple buildbacks natively: https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app

Use multiple buildpacks on your app

## Usage

    $ heroku buildpacks:set https://github.com/ddollar/heroku-buildpack-multi.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git#v86

## License

MIT
