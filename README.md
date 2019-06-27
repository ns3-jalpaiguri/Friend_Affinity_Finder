Steps to run the Web Application, Friend_Affinity_Finder:
  1. Download and Install <b>WAMP Server</b> (between Version 2 to 3)
  2. Click on the WAMP Symbol in system tray and open the <b>httpd.conf</b> file inside Apache and write the following code under
     <Directory “c:/wamp/www/”> <br>
     <b>AddHandler cgi-script .cgi .py<br>
     Options Indexes FollowSymLinks ExecCGI</b> <br>
     ![alt text](screen.jpeg)
     This enables the Python CGI for Back-End Development
  3. Download the application file, <b>friend_affinity_finder.zip</b> and extract its contents in the <b>www</b> folder inside <b>wamp</b>
     which will be installed in the path mentioned during installation
  4. In the .py files: <b>/go/register.py</b>, <b>/go/login.py</b> and <b>/display/run.py</b>, change the path of python.exe at the very        beginning of the files
     as: <br>
     <b>#!PATH</b> <br>
     By default PATH is given as <b>C:\Users\USER\AppData\Local\Programs\Python\Python37\python.exe</b>
  5. Go to a web browser and type <b>localhost/friend_affinity_finder</b> in the Address Bar and press Enter
   
  
