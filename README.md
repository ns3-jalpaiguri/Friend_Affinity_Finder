Steps to run the Web Application, Friend_Affinity_Finder:
  1. Download and Install WAMP Server (between Version 2 to 3)
  2. Open the httpd.conf file under Apache and write the following code under <Directory “c:/wamp/www/”>
      AddHandler cgi-script .cgi .py
      Options Indexes FollowSymLinks ExecCGI
     This enables the Python CGI for Back-End Development
  3. Download the application file, friend_affinity_finder.zip and extract its contents in the www folder under wamp which will be
     installed in the path mentioned during installation
  4. Go to a web browser and type "localhost/friend_affinity_finder" and press Enter
   
  
