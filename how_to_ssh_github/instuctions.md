# SSH GitHub from terminal
it is better if u do it with a fresh install of git 
# Step 1
### To setup username:
```
git config --global user.name "Your Name"
```
### To setup email:
```
git config --global user.email "yourname@example.com"
```
### Change the default branch for Git using this command
```
git config --global init.defaultBranch main
```
{we are doing this cause earlier github used to have its main brach name as master but now its main so we need to setup the default brach }
### To enable colorful output with git
```
git config --global color.ui auto
```
### reconciliation behavior to merging
```
git config --global pull.rebase false
```
{not sure what it does but helps in the project}
### Check if name and email are correct
```
git config --get user.name

git config --get user.email
```

### THE SSH KEY SETUP
First run this
```
ls ~/.ssh/id_ed25519.pub
```
and check if u have a ed25519 ssh key

if you get a response stating "No such files Found" then

```
ssh-keygen -t ed25519 -C <youremail>
```
Then just press <b>enter</b> and keep a password if you like we can also keep it empty

Now try
```
cat ~/.ssh/id_ed25519.pub
```
then copy the string that to 

GitHub >> Settings >> SSH and GPG keys >> paste the ssh

to check type
```
git remote -v
```
you should get a response like
```
> origin  https://github.com/OWNER/REPOSITORY.git (fetch)
> origin  https://github.com/OWNER/REPOSITORY.git (push)
```