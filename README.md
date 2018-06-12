## GitHub Forking Status

Hello. You have forked and cloned my repo. Now you can edit the repository in any way. If you want to make sure this repo is capable of receiving updates, follow the steps below:

1. Add the original repo's information (done)
In your terminal, type:
```bash
git remote add upstream https://github.com/adhire/github-forking-demo.git
```

2. Check to see if the connection was created (done)
In your terminal, type: 
```bash
git remote -v
```
..* If you see your repo and my repo, move to step 3. If not, ask for help.

3. Fetch the updates from the original repo (the repo you forked) In your terminal, type: 
```bash
git fetch upstream
```

4. Checkout to your master branch and merge the upstream/master. In your terminal, type: 
```bash
git checkout master
git merge upstream/master
```

Any time the original branch makes an update, you can follow steps 3 and 4. If you want to push your local changes to your GitHub repo, you simply run these commands in order: 
```bash
git add .
git commit -m "some commit message"
git push origin master
```