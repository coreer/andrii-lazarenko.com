Project is hosted on github

Link with theme
```
git submodule add https://github.com/coreer/hugo-initio.git themes/hugo-initio
```


With case Deployment of Project Pages From gh-pages branch.

```
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Initializing gh-pages branch"
git push origin gh-pages
git checkout master
```

Lets put public pages in separated branch
```
git worktree add -B gh-pages public origin/gh-pages
```