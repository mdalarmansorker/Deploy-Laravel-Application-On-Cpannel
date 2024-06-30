# How To Deploy Laravel Application on Cpannel
### Step 1:
Create build file for production by running this command.
```sh
npm run build
```
### Step 2:
For tailwind copy the files from tailwind folder and paste it in the root directory. And for bootstrap copy the files from bootstrap folder and paste it on the root directory.
Note: If you installed both bootstrap and tailwind then this method won't work. 
### Step 3:
Compress the laravel application folder into zip file and upload it on the root folder of the domain. By default its the public_html folder. Then unzip it there and move the all files on the root folder of this domain/sub domain. 
### Step 4:
Export the sql database from phpmyadmin. Then go the cpannel's SQL Database option and create a database and a user for the database. Select user for the database and also copy the username and password for letter use on .env file of your project. Then go to the "phpmyadmin" option and select the database then import the sql file..
### Step 5:
Edit the .env file and update the database name, username, and password.
