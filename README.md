# heroku-buildpack-juman
This is a _Heroku Buildpack_ for running [JUMAN 7.01](http://nlp.ist.i.kyoto-u.ac.jp/index.php?JUMAN++) for natural language processing.

## Usage

``` 
$ heroku buildpacks:add https://github.com/d0iasm/heroku-buildpack-juman.git
$ git push heroku master
```

### To avoid error 'Compiled slug size: <size> is too large (max is 500M).'
1. Move some files out of the repo such as design documents(.sketch, .mp3, .mpg).
2. Ignore some files by creating `.slugignore`.


## Uninstall
```
$ heroku buildpacks:remove https://github.com/d0iasm/heroku-buildpack-juman.git
$ git push heroku master
```
