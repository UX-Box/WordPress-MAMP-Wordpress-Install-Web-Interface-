# WordPress MAMP Wordpress Install Web Interface
Install the latest version of wordpress from your browser using localhost. This web app will guide you to get your local dev site up and running in matter of seconds. 


### Features
	1. Get Latest version of wordpress
	2. Setup Wordpress
	3. Create Database
	4. Create wp-config.php file
	5. Install Wordpress
		* Create and Point Virtual Host ex: example.dev/
		* Point your install to the virtual host
	6. Site Manager - Manage all your sites in one place
	8. App requirement check
	9. That is it for now
	10. Wordpress Structure rewrite (Better security)
		* Change wp-content folder name
		* Change wp-uploads dir name
		* Change plugins dir name
		* More secure .htaccess (coming soon)

### Videos and Demos 

[![Application Site Manager Demo](https://raw.githubusercontent.com/michelve/WordPress-MAMP-Wordpress-Install-Web-Interface-/master/core/images/video-sitemanager.png)](https://www.youtube.com/watch?v=VENQ6TzOGQU "Application Site Manager Demo")

[![Application Preview and Demo](https://raw.githubusercontent.com/michelve/WordPress-MAMP-Wordpress-Install-Web-Interface-/master/core/images/preview.png)](https://www.youtube.com/watch?v=VD76l3K2P2o "Application Preview and Demo")


### Requirements 
see the documentation.html file for more detailed steps and guide 


	1. MAMP if you don't have MAMP you can grab the latest version from: 
		* https://www.mamp.info/en/downloads/ (you don't need the PRO version)
		* MAC OS X

	2. Use a text editor to open the main Apache configuration file, httpd.conf, which is located at
		* **Applications/MAMP/conf/apache/httpd.conf**

	3. Scroll to the bottom of the file and locate the following lines (around 524–525):

		`Virtual Hosts`

		`#Include /Applications/MAMP/conf/apache/extra/httpd-vhosts.conf`

	4. **Remove the hash** (pound #) sign from the beginning of the line that begins with Include:

		`Virtual Hosts`

		`Include /Applications/MAMP/conf/apache/extra/httpd-vhosts.conf`

	5. **Save the file**, Restart MAMP, and then open the web app from you browser.
		* Make sure to copy or clone the web app inside your localhost root folder

	6. See the documentation.html for further help.



### How to use
	* use the documentation.html file 

	1. Move the web app into the localhost folder 
	2. Access the localhost from your favorite web browser and access the folder you just copied
	3. Follow the installation instructions and fill all the required information
	4. After the install is completed it will prompt you to re-start MAMP - after you can continue with the installation
	5. please note this in early stages if you have any issues please let me know


### Screen-shots

<img src="https://raw.githubusercontent.com/michelve/WordPress-MAMP-Wordpress-Install-Web-Interface-/master/core/images/screenshot-1.jpg"/>
<img src="https://raw.githubusercontent.com/michelve/WordPress-MAMP-Wordpress-Install-Web-Interface-/master/core/images/screenshot-2.jpg"/>
<img src="https://raw.githubusercontent.com/michelve/WordPress-MAMP-Wordpress-Install-Web-Interface-/master/core/images/screenshot-3.jpg"/>