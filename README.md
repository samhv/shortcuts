# Shortcuts

Bash shortcuts for Git, RoR and Heroku.

## Installing

You have not installed shortcuts (damn, can not use shorcuts for install), then you need to: cloned the project, move to folder and install:

```
$ git clone git@github.com:samhv/shortcuts.git
$ cd shortcuts
$ sudo ./install
```

##Updating

Just do:

```
$sudo update_shortcuts
```

##Uninstalling

Just do:

```
$sudo delete_shortcuts
```

##Bash Shortcuts:
```
$old_command (what does new_command do?)
```
```
$new_command
```

###Git Shortcuts:
------------------
```
$git add -A
$git commit -m "added this feature"
$git push some_branch
```
```
$ph "added this feature" some_branch
```
------------------
```
$git pull some_branch
```
```
$pll some_branch
```
------------------
```
$git branch some_branch
```
```
$b some_branch
```
------------------
```
$git commit -m "added this feature"
```
```
$cm "added this feature"
```
------------------
```
$git checkout some_branch
```
```
$co some_branch 
```
------------------
```
$git branch some_branch
$git checkout some_branch
```
```
$bco some_branch
```
------------------
```
$git merge some_branch
```
```
$mg some_branch
```
------------------
```
$git log
```
```
$lg
```
------------------
```
$git push origin some_branch
```
```
$pho some_branch
```
------------------
```
$git push origin some_branch
```
```
$pllo some_branch
```
------------------

###Rails Shortcuts
------------------
```
$rake db:create
```
```
$new_db
```
------------------
```
$rake db:drop
```
```
$drop_db
```
------------------
```
rake db:drop
rake db:create
rake db:migrate
```
```
$reset_db
```
------------------
```
rake db:migrate
```
```
$migrate
```
------------------
```
$rails generate ...
```
```
$rg ...
```
------------------
```
$rails generate model ...
```
```
$rgmod ...
```
------------------
```
$rails generate migration ...
```
```
$rgmig ...
```
------------------
```
$rails generate controller ...
```
```
$rgcon ...
```
------------------

###Heroku Shortcuts
------------------
```
$git push heroku master
```
```
$hph
```
------------------
```
$heroku run ...
```
```
$hr ...
```
------------------
```
$heroku logs
```
```
$hl
```
------------------

##Inspiration

This project is heavily inspired in a lot of others shortcuts-project. But besides simple abbreviations, the idea is make shortcuts that provide routines that we do all time when we are developing and it should be automatic, for example, among other things, all has happened to us that we started a project in rails and then we realize that we do not specify that the database is postgress and then we have to make the change at hand?. I would love to do "$change_db_to pg" and that did the job for me every time I passed it (currently this isn't implemented D:).

##Contributing

1. Create your feature branch ($bco my-new-shorcut)
2. Works in that
3. Commit your changes and push to the branch ($pho "added this shorcut" my-new-shorcut)
5. Create new Pull Request