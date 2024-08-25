# cakephp-setup

### Instructions on how to bake in cakephp

```bash
# Create a cakephp app
composer create-project --prefer-dist cakephp/app MyCakePhpApp
```

<br>

```bash
# Navigate to app directory
cd MyCakePhpApp
```

<br>

Modify this section in `/config/app_local.php` to include your username and password for database (i.e. admin, supersecretpassword)

```php
'username' => 'databaseusername',
'password' => 'databasepassword',

'database' => 'databasename',

```

<br>

```bash
# Baking commands for WINDOWS to see all
.\bin\cake bake all

# Baking commands for MAC to see all
bin/cake bake all
```

<br>

```bash
# Bake individual table for WINDOWS
.\bin\cake bake all tablename

# Bake individual table for MAC
bin/cake bake all tablename
```

### The Gitflow - Connor
## Cloning
<br>

```bash
# Cloning using git bash
git clone https://gitlab.com/repository
```
<br>

```bash
# Move into your new repository
cd repository
```

<br>

## Adding, committing, and pushing
# I will break this down into seperate commands, but also provide a one line command to add, commit, and push.

```bash
git add filename # to add a specific file
# or
git add . # to add all new files.
```

<br>

```bash
# A commit message is needed with Git Bash, otherwise the commit will fail.
git commit -m "Message"
```

<br>

```bash
# Push it to the cloud!
git push
```

<br>

```bash
# Here is the command to do all at once:
git add . && git commit -m "Commit Message" && git push
```

<br>

## Branching and Merging

<br>

```bash
# To branch, do the following:

git branch branchName

git checkout branchName

git --set-upstream branchname

# or
git branch branchName && git checkout branchName && git --set-upstream branchname
```

<br>

```bash
# To merge, do the following
git checkout main
git fetch
git pull
git merge branchName
git push

# or

git checkout main && git fetch && git pull && git merge branchName && git push
```
