# Github Pages

## My To-Dos

- [x] Initialize site
- [ ] Things to add: Sample lecture notes, contact info, collaboration

## Steps to initialize Jekyll site

1. Install [Ruby](http://jekyllrb.com/docs/installation/) on your local machine's operating system.

2. Within your terminal, install **jekyll** and **bundler** gems. [Reference](http://jekyllrb.com/docs/)

```Shell
gem install jekyll bundler
```
3. Initialize github repo named `<github.username>.github.io` and `git clone` to local machine. Then navigate to cloned repo folder.

```Shell
cd <github.username>.github.io
```

4. Create Jekyll site within repo folder. [Reference](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)

```Shell
jekyll new --skip-bundle .
```

5. Follow steps 8 thru 13 to setup the site files. [Reference](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)

```Shell
# Ensures all specified dependencies in _config.yml are installed
bundle install
```

6. You can test your site on your local machine before pushing to remote.

```Shell
bundle exec jekyll serve
```

Preview site in browser at `http://localhost:4000`.


