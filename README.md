# Blog 

Available at https://blog-gh.noki.fr

Powered with Hugo

Theme used is a customized version of smol, hosted [here](https://github.com/NokiDev/blog_theme)

## Intro

// TODO

## Helper (to not forget)

### Writter setup 

Setup publish directory
```
git worktree add -B gh-pages public origin/gh-pages
```


### Basic commands

- Dev Env

```
hugo server --config config/production_gh/config.yml -d public
```


- Publish 
```
hugo
cd public && git add --all && git commit -m "Publishing to gh-pages" && cd .
git push upstream gh-pages
```


## TODOS

*Global todolist for things I need to do but didn't yet*

- Automate publishing on twitter, mastodon, reddit, etc...
- Add licence to the articles (CC2.0)
- Add series category
- Update infra page.
- manage tags.
- handle i18n / articles only visible within lang context. 

