# heroku-buildpack-pyknp
This is a _Heroku Buildpack_ for running [KNP](http://nlp.ist.i.kyoto-u.ac.jp/?KNP) and [JUMAN](http://nlp.ist.i.kyoto-u.ac.jp/index.php?JUMAN++) tools for natural language processing with Python.

## Usage
```
$ wget 
$ heroku buildpacks:add https://github.com/d0iasm/heroku-buildpack-pyknp.git
$ git push heroku master
```

## Uninstall
```
$ heroku buildpacks:remove https://github.com/d0iasm/heroku-buildpack-pyknp.git
$ git push heroku master
```
