# Crystal Heroku Buildpack

You can create an app in Heroku with Crystal's buildpack by running the
following command:

```bash
$ heroku create myblog --buildpack https://github.com/f/heroku-buildpack-kamber.git
```

In order for the buildpack to work properly you should have a `Projectfile`
file, as it is how it will detect that your app is a Crystal app.

To learn more about using custom buildpacks in Heroku, read [their docs](https://devcenter.heroku.com/articles/third-party-buildpacks#using-a-custom-buildpack).
