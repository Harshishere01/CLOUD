# AWS
creating vm by using aws 
1. make a aws account
2. search EC2
3. launch instance
4. name the instance
5. choose free tire
6. create private key
7. download the key , save it to desktop
8. select ssh and http
10.launch the instance 
11. go to see all instances there you will find the public ip
12. open the ip in another tab (it will not open because nothing is in there)
13. download install putty
14. go to session , enter the ip adress in the new host name 
15. go to ssh the go auth , expand auth
16. click credentials
17. browse private key and open the private key you downloaded
18. go to session and open it
19. your vm is now created
20. install 


  TO OPEN A WEB SERVER---<br/>
1.TYPE ON GOOGLE HOW TO INSTALL WEB SERVER IN YOUR OS WHICH YOU HAVE SELECTED.<br/>
2.NOW DOWNLOAD ANY WEB SERVER LIKE APACHE2ETC.<br/>
3.FROM THAT INSTALL APACHE2 IN YOUR VM<br/>
TYPE : >>sudo apt update<br/>
       >>sudo apt install apache2<br/>
<br/>
---PRESS ENTER AND WEB SERVER WILL START INSTALLING----<br/>
4.TO SEE THE WEB SERVER GO TO GOOGLE OPEN NEW TAB AND ENTER YOU IP ADDRESS . YOU WILL SEE THE APACHE2 WEB SERVER.<br/>
-----------TO SEE HI ON SERVER ---------------<br/>
1.ENTER THE FOLLOWING COMMAND<br/>
  >>cd{ENTER SPACE}/var/www/html/<br/>
  >>ls<br/>
  >>YOU WILL SEE<br/>
  >>index.html<br/>
  ------TO REMOVE SUDO-----------<br/>
  >>sudo su<br/>
  --------NOW SUDO IS REMOVED--------<br/>
<br/>
  -------REMOVE THE APACHE2 SERVER -----------<br/>
  >>rm index.html<br/>
  ------THEN ENTER--------<br/>
  >>vi index.html<br/>
  ------PRESS {i} -------<br/>
  ----------ENTER----------<br/>
  >><html>  hi   </html><br/>
  ------NOW PRESS THESE KEY-------<br/>
  >>ctrl+c<br/>
  <br/>
  -------REMOVE THE APACHE2 SERVER -----------<br/>
  >>rm index.html<br/>
  ------THEN ENTER--------<br/>
  >>vi index.html<br/>
  ------PRESS {i} -------<br/>
  ----------ENTER----------<br/>
  >><html>  hi   </html><br/>
  ------NOW PRESS THESE KEY-------<br/>
  >>ctrl+c<br/>
  >>shift+";"<br/>
  >>wq<br/>
  -------PRESS ENTER -------<br/>
  NOW GO TO GOOGLE AND ENTER THE IP ADDRESS YOU WILL SEE HII<br/>
  ---------------------------------------------------------------------------------------------------------------------<br/>
<br/>
<br/>
<br/>
<br/>


               1  rm index.html
    2  ls
    3  vi index.html
    4  history
root@ip-172-31-84-226:/var/www/html#

