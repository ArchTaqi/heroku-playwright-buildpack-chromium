# Heroku Playwright Buildpack Only Chromium for Python

This buildpack installs all the needed dependencies and Chromium browser and its driver to use Playwright ONLY Chromium on Heroku.

Note: In heroku settings python buildpack must be added before this buildpack. Or you can add python from cli:

```txt
heroku buildpacks:add --index 1 heroku/python
```
then

```txt
heroku buildpacks:add https://github.com/gokhantuffer/heroku-playwright-buildpack-chromium.git -a my-app
```
