# Django, Nuxt.js and Heroku

## heroku setup

```
$ heroku login
$ heroku create
$ heroku buildpacks:set heroku/python
$ heroku buildpacks:add --index 1 heroku/nodejs
$ git push heroku master
```
