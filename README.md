# group-solarpanel 
Set up the git repository on Github
When you create it, you can tick the box to add a read me file.

You can invite people under settings > Collaborator > Manage access

Add everyones email address or Github username there.

They should receive an email granting them access.

Check to see everyone has access to the repo.

You should all take a local clone of the remote.

You can do this in github desktop or on the command line / terminal. 

git clone urlgoeshere

Https:
```
git clone https://github.com/movi1/group-solarpanel.git
```

SSH:
```
git clone git@github.com:movi1/group-solarpanel.git
```


First of all let’s set up the basic structure on the main branch:
- HTML
- CSS
- JS

Note that this is the only time we will be touching this branch for now, afterwards you will be creating a develop branch and this will be your working/changing branch.

Choose someone to do this locally and then push it to the main branch.

Choose someone (maybe the same person as before or someone else) to add a new branch locally called  develop.

Then publish this branch to the remote. You can do this in github desktop.

Now everyone else should be able to do git pull or git fetch and see the new branch locally.

![My Image](./img/readme/git-setup-rules.PNG)