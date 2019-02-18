# Instructions:

clone this repo or

create project:

```tiddlywiki [projectname] --init server```

run start.sh to start server.

run build.sh to build index.

If you have a domain you want to direct to, put CNAME into the output folder.

## Deploying

1. Build index on change
2. Commit changes to master branch and push

```git push -u origin master```

3. create gh-pages subtree and push

```git subtree push --prefix myjournal/output origin gh-pages```


Notes: 
* keep gh-pages branch up to date with master to prevent conflicts.
* gh-pages takes time to update, clear cache to get instant update
