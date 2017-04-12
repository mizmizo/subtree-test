## git subtree test ##

This is test repository for using working branch as default, master branch as sub module for publication or something.

When you update something in subtree-dir on Local working branch, you can push only files under subtree-dir to master as follows.
It's maybe useful for working and publish documents in a same repository for github pages.

```
git add XXX ## on working branch
git commit
git push origin working
git subtree push -P ./subtree-dir/ origin master
```
