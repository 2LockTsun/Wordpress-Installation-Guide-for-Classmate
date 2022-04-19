# Wordpress full installation guide

[TOC]

### XAMPP

Install [XAMPP](https://www.apachefriends.org/download.html) (Download the 8.1.4 version)
![Download XAMPP](img/XAMPP_download_page.png)

Follow the instructions and you will see "XAMPP Control Panel" after installation
![XAMPP Control Panel](img/XAMPP_control_panel.png)

Click the start Button of "Apache" and "MySQL"
![XAMPP](img/XAMPP_click_to_start_service.png)

And you should see both "Apache" and "MySQL" turns to green.
![XAMPP](img/XAMPP_running_service.png)

Go to: [localhost/phpmyadmin/](http://localhost/phpmyadmin/)
In your browser and you will see this tab
![XAMPP](img/localhost_phpmyadmin.png)

Click "新增"
![Localhost Click Create](img/localhost_phpmyadmin_click_create.png)

Type your database name and click "建立".
You should remember the database name.
![Create Database](img/localhost_phpmyadmin_create_database.png)

### Set up Wordpress

Next, download [WordPress](https://wordpress.org/download/).
![Download Wordpress](img/WP_download_page.png)

And you will get a WordPress zip file. Unzip and open it
![Unzip](img/WP_open_zip.png)

Next, open another file manager and click C drive
![Open C Drive](img/drive_open_c.png)

Click xampp
![Open XAMPP Dir](img/drive_open_xampp.png)

Click htdocs
![Open htdoc Dir](img/drive_open_htdocs.png)

Create a new folder same as your database name created earlier
For me I created `ICT`
![Create Dir](img/drive_create_folder.png)

Copy and paste EVERYTHING inside WordPress zip file to the folder
![Copy to Dir](img/drive_copy_from_zip.png)

### Start installation

Next, type
localhost/(folder name)/wp-admin
into your browser (replace (foldername) with your folder name).
Choose the language and click "continue"
![WP](img/WP_language.png)

Click "Let’s go"
![CLick Lets's go](img/WP_click_lets_go.png)

Database Name: Name of your database created before
Username: `root`
Password: `Empty`
Do not change "Database Host" and "Table Prefix"
Click submit
![WP](img/WP_database.png)

Click "Run the installation"
![WP Install](img/WP_install.png)

If you received an error, redo everything from [localhost/phpmyadmin](http://localhost/phpmyadmin)

Next, feel free to enter your
Site title, Username, Password and Your Email.
Click "Install WordPress"
![WP Install](img/WP_install_webpage.png)

Click Log in
![WP Login](img/WP_click_login.png)

Enter your Username and Password created
![WP](img/WP_login.png)

If everything goes right, you will see this page.
![Finish](img/WP_finish.png)

And everything is done
