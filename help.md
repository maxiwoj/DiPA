# Help
## Env init
```bash
eval "$(rbenv init -)"
export PATH="/Users/maksymilianwojczuk/.rbenv/shims:$PATH" # for overwriting system ruby with rbenv ruby 
```

check ruby version: 
```
$ ruby -v # should be 3.0.0 in shims
```

in case still using the system ruby, add to PATH as the first arg:
```bash
$ export PATH="/Users/maksymilianwojczuk/.rbenv/shims:$PATH"
```

## Project init
Needed to run on first serve:
```bash
$ bundle add webrick
$ bundle install
```

## Local dev
To start dev server:
```bash
$ bundle exec jekyll serve
```
To build the theme.
 
```bash
$ bundle exec jekyll build
```

Some useful links on ruby setup:
https://stackoverflow.com/questions/10940736/rbenv-not-changing-ruby-version
https://help.learn.co/en/articles/2789231-how-to-upgrade-from-ruby-2-3-to-2-6
https://github.com/jekyll/jekyll/issues/8523