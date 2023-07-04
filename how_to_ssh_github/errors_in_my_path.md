# Errors
## check your remote
when you do
```
git remote -v
```
you should see
```
origin	git@github.com/<repo_name>.git (fetch)
origin	git@github.com/<repo_name>.git (push)
```
if you did a lot of edit then the best way is
```
$ git remote rm origin # or name that u got at top left 
$ git remote add origin git@github.com:ReubenReny03/Web_Dev_odinproject.git # your git hub ssh link