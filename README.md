# heroku-buildpack-pyknp
This is a _Heroku Buildpack_ for running [KNP](http://nlp.ist.i.kyoto-u.ac.jp/?KNP) and [JUMAN](http://nlp.ist.i.kyoto-u.ac.jp/index.php?JUMAN++) tools for natural language processing with Python.

## Usage
We need to the workaround because the knp file is too much size.

```.slugignore


```

### To avoid error 'Compiled slug size: <size> is too large (max is 500M).'
1. Move some files out of the repo such as design documents(.sketch, .mp3, .mpg).
2. Ignore some files by creating `.slugignore`.

``` 
$ heroku buildpacks:add https://github.com/d0iasm/heroku-buildpack-pyknp.git
$ git push heroku master
```

## Uninstall
```
$ heroku buildpacks:remove https://github.com/d0iasm/heroku-buildpack-pyknp.git
$ git push heroku master
```
