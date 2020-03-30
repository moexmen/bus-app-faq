# MOE School Bus FAQ

This static site is generated by Jekyll and can be found in the `_site` directory.
The instructions below are for building the static site again.

## Install Jekyll

1. Install Jekyll (assuming you have your Ruby environment with bundler set up)
```
gem install --user-install bundler jekyll
```

2. Get Ruby version
```
ruby -v
```

3. Append your path file (replace X.X with the first 2 digits of your Ruby version).
Make sure you restart your terminal or `source` your terminal config file in order for
the `path` variable to be updated.
```
echo 'export PATH="$HOME/.gem/ruby/X.X.0/bin:$PATH"' >> ~/.bash_profile
```

4. To check your gem paths point to your home directory: `gem env`
and check that `GEM PATHS:` points to a path in your home directory.

5. If it's successful, the `jekyll` command should work.

## Develop and build

1. To develop:
```
jekyll serve
```

2. To build:
```
jekyll build
```
