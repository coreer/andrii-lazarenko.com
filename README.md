Project is hosted on github

With case Deployment of Project Pages From gh-pages branch.

```
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Initializing gh-pages branch"
git push upstream gh-pages
git checkout master
```

