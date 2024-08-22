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
