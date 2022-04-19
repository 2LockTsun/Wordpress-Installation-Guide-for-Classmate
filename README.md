# Wordpress full installation guide

[TOC]

### XAMPP

Install [XAMPP](https://www.apachefriends.org/download.html) (Download the 8.1.4 version)<br/>
![Download XAMPP](img/XAMPP_download_page.png)

Follow the instructions and you will see "XAMPP Control Panel" after installation<br/>
![XAMPP Control Panel](img/XAMPP_control_panel.png)

Click the start Button of "Apache" and "MySQL"<br/>
![XAMPP](img/XAMPP_click_to_start_service.png)

And you should see both "Apache" and "MySQL" turns to green.<br/>
![XAMPP](img/XAMPP_running_service.png)

Go to: [localhost/phpmyadmin/](http://localhost/phpmyadmin/)
In your browser and you will see this tab<br/>
![XAMPP](img/localhost_phpmyadmin.png)

Click "新增"<br/>
![Localhost Click Create](img/localhost_phpmyadmin_click_create.png)

Type your database name and click "建立".<br/>
You should remember the database name.<br/>
![Create Database](img/localhost_phpmyadmin_create_database.png)

### Set up Wordpress

Next, download [WordPress](https://wordpress.org/download/).<br/>
![Download Wordpress](img/WP_download_page.png)

And you will get a WordPress zip file. Unzip and open it<br/>
![Unzip](img/WP_open_zip.png)

Next, open another file manager and click C drive<br/>
![Open C Drive](img/drive_open_c.png)

Click xampp<br/>
![Open XAMPP Dir](img/drive_open_xampp.png)

Click htdocs<br/>
![Open htdoc Dir](img/drive_open_htdocs.png)

Create a new folder same as your database name created earlier<br/>
For me I created `ICT`<br/>
![Create Dir](img/drive_create_folder.png)

Copy and paste EVERYTHING inside WordPress zip file to the folder<br/>
![Copy to Dir](img/drive_copy_from_zip.png)

### Start installation

Next, type<br/>
localhost/(folder name)/wp-admin<br/>
into your browser (replace (foldername) with your folder name).<br/>
Choose the language and click "continue"<br/>
![WP](img/WP_language.png)

Click "Let’s go"<br/>
![CLick Lets's go](img/WP_click_lets_go.png)

Database Name: Name of your database created before<br/>
Username: `root`<br/>
Password: `Empty`<br/>
Do not change "Database Host" and "Table Prefix"<br/>
Click submit<br/>
![WP](img/WP_database.png)

Click "Run the installation"<br/>
![WP Install](img/WP_install.png)

If you received an error, redo everything from [localhost/phpmyadmin](http://localhost/phpmyadmin)<br/>

Next, feel free to enter your<br/>
Site title, Username, Password and Your Email.<br/>
Click "Install WordPress"<br/>
![WP Install](img/WP_install_webpage.png)

Click Log in<br/>
![WP Login](img/WP_click_login.png)

Enter your Username and Password created<br/>
![WP](img/WP_login.png)

If everything goes right, you will see this page.<br/>
![Finish](img/WP_finish.png)

And everything is done<br/>
