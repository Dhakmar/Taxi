<h1>TAXI SERVICE</h1>
<img src="https://www.forumdaily.com/wp-content/uploads/2017/11/Depositphotos_10768924_m-2015.jpg" alt="">
<hr>
<h2>GOAL OF THIS PROJECT:</h2> 
Create a service for registering drivers in the taxi system and assigning drivers to cars. In this application, you can
create / read / update / delete drivers or cars, manage their relationship. <br>
Implemented N-tier architecture, the ability to authenticate by login / password and logging of the application.
<hr>
<h2>TECHNOLOGIES USED:</h2>
<ul>
  <li>Java 11</li>
  <li>Servlet</li>
  <li>JSP</li>
  <li>JSTL</li>
  <li>JDBC</li>
  <li>MySQL</li>
  <li>Custom injector</li>
  <li>Tomcat 9.0.50</li>
  <li>Maven</li>
  <li>Maven Checkstyle Plugin</li>
  <li>Log4j2</li>
  <li>HTML, CSS</li>
</ul>
<hr>
<h2>LAUNCH:</h2>
<ul>
<li> To run the project on your local machine, clone this project into your local folder and open the project in an IDE </li>
<li> Install MySQL and MySQL Workbench, to configure MySQL you can use the script from resources/init_db.sql </li>
<li> Configure connection to your database in src/main/java/taxi/util/ConnectionUtil.java: <br>
    URL TO YOUR LOCAL DB - jdbc:mysql://localhost:3306/<b>database_name</b>?useLegacyDatetimeCode=false&serverTimezone=UTC <br>
    YOUR USERNAME - MySQL username <br>
    YOUR PASSWORD - MySQL password <br>
    JDBC_DRIVER - com.mysql.cj.jdbc.Driver <br> </li>
<li> Install and configure Local Tomcat Server (set "/" in Deployment - taxi-service:war exploded - Application context) </li>
<li> Run your project, in browser you will see login page with possibility to register a new user(drier) - click register </li>
<li> Fill in empty fields on this page -> click Submit </li>
<li> Login with your username and password. </li>
</ul>
<hr>