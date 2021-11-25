# heroku-static-site

Place the html app in `web/` and deploy to heroku.

## Buildpack

https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-static

The `static.json` file is required to use this buildpack.

## Deploy to heroku

```sh
$ git clone https://github.com/apfromiit/heroku-static-site
$ cd heroku-static-site
$ heroku create <appname> --buildpack heroku-community/static
$ git push heroku master
$ heroku open
```
