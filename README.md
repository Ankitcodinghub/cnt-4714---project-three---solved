# cnt-4714---project-three---solved
**TO GET THIS SOLUTION VISIT:** [CNT 4714 – Project Three  – Solved](https://www.ankitcodinghub.com/product/cnt-4714-project-three-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;68773&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CNT 4714 – Project Three &nbsp;– Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<strong>Title:</strong>&nbsp; “Project Three: Developing A Three-Tier Distributed Web-Based Application”

<strong>Objectives:</strong>&nbsp; To incorporate many of the techniques you’ve learned so far this semester into a distributed three-tier web-based application which uses servlets and JSP technology running on a Tomcat container/server to access and maintain a persistent MySQL database using JDBC.

&nbsp;

<strong>Description:</strong>&nbsp; In this assignment you will utilize a suppliers/parts/jobs/shipments database (creation/population script available on the course assignment page) as the back-end database. Front-end access to this database by the client will occur through a single page displayed in the client’s web browser. The schema of the backend database consists of Three tables with the following schemas for each table:

&nbsp;

suppliers (<u>snum</u>, sname, status, city)&nbsp; //information about suppliers&nbsp; parts (<u>pnum</u>, pname, color, weight, city)&nbsp; //information about parts&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; jobs (<u>jnum</u>, jname, numworkers, city)&nbsp; //information about jobs

shipments (<u>snum, pnum, jnum</u>, quantity)&nbsp; //suppliers ship parts to jobs in specific quantities

&nbsp;

The first-tier (client-level front-end) of your application will be a JSP page that allows the client to enter SQL commands into a window (i.e. a form) and submit them to the server application for processing.&nbsp; The front-end (<strong>and only the front-end</strong>) will utilize JSP technology.&nbsp;&nbsp; The client front-end will provide the user a simple form in which they will enter a SQL command (any DML, DDL, or DCL command could theoretically be entered by the user, however we will restrict to queries, insert, update, replace, and delete commands).&nbsp; The front-end will provide only two buttons for the user, an Execute button that will cause the execution of the SQL command they enter, and a Reset button that simply clears any content in the form input area.&nbsp; The client front-end will run on any web-based browser that you would like to use.&nbsp; You can elect to have a default query or not, it is entirely your decision.&nbsp; The application will connect to the backend database as a root user client.

&nbsp;

The second-tier servlet, in addition to handling the SQL command interface will also implement the business/application logic.&nbsp; This logic will increment by 5, the status of a supplier anytime that supplier is involved in the insertion/update of a shipment record in which the quantity is greater than or equal to 100.&nbsp; Note that any update of quantity &gt;= 100 will affect any supplier involved in a shipment with a quantity &gt;= 100.&nbsp; The example screen shots illustrate this case.&nbsp; An insert of a shipment tuple (S5, P6, J7, 400) will cause the status of every supplier who has a shipment with a quantity of 100 or greater to be increased by 5.&nbsp; In other words, even if a supplier’s shipment is not directly affected by the update, their status will be affected if they have any shipment with quantity &gt;= 100.&nbsp; <strong>(See page 11 for a bonus problem that implements a modified version of this business rule.)</strong>&nbsp; The business logic of the second tier will reside in the servlet on the Tomcat web-application server (server-side application).&nbsp; This means that the business logic is not to be implemented in the DBMS via a trigger.

&nbsp;

The third-tier (back-end) is the persistent MySQL database described above and is under control of the MySQL DBMS server.&nbsp; All you need to do with the database is run the creation/population script.&nbsp; See the important note below concerning when/how to re-run this script for your final submission.

&nbsp;

<strong>References:&nbsp; </strong>

Notes:&nbsp; Lecture Notes for MySQL installation and use.&nbsp; Documentation for MySQL available at: <u>http://www.mysql.com</u>. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; More &nbsp; information &nbsp;&nbsp;&nbsp; on &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; JDBC can &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; be &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; found &nbsp; at: <u>http://www.oracle.com/technetwork/java/javase/jdbc/index.html</u> .&nbsp; More information on Tomcat can be found at <u>http://tomcat.apache.org</u>.&nbsp; Lecture Notes for Servlets.&nbsp;&nbsp;&nbsp; Lecture Notes for JSPs.

&nbsp;

<strong>Restrictions: </strong>

Your source file shall begin with comments containing the following information:

<strong>/*&nbsp; Name:&nbsp;&nbsp; </strong>

<h2>&nbsp;&nbsp;&nbsp;&nbsp; Course: CNT 4714&nbsp; Project Three&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Assignment title:&nbsp; A Three-Tier Distributed Web-Based Application</h2>
<strong>Input Specification:</strong>&nbsp; The suppliers/part/jobs/shipments database that is created/populated by the script project3dbscript.sql, is the back-end to this application.&nbsp; All other input comes from the frontend client submitted to the application server based servlet entered as either queries or updates to this database.&nbsp; The set of commands that you are to execute against this database are included in the project3commands.sql file available on the course homework page.&nbsp; I do not expect your frontend to execute the script.&nbsp; You’ll need to execute the commands in this script one at a time in your application (copy and paste!).&nbsp; I’ve put them into a script file for convenience and so that you can run the script in the MySQL Workbench if you’d like to compare/see the result sets for each user command.

&nbsp;

<strong>Output Specification:&nbsp; </strong>All output is generated by the servlet and should appear in the user’s browser as a text/html page presented to the user.&nbsp; <strong>IMPORTANT:</strong> Be sure to re-run the project3 database creation/population script before you begin creating your screen shots for submission.&nbsp; By doing so you will ensure that the database is in its initial state so that all update operations will produce the values we are expecting to see in your result outputs.

&nbsp;

<strong>Deliverables: </strong>

<ul>
<li>You should submit your entire Project3 webapp folder from Tomcat for this program. If you submit the entire folder, then all of the files necessary to execute your web application will be included with the directory structure intact.&nbsp; Submit this via WebCourses no later than <strong>11:59pm Sunday August 1, 2021</strong>.</li>
<li>The following 16 screen shots must be submitted along with your webapps folder. (You can include the screenshots in the top-level of your webapps folder if you’d like, just be sure to include a note that you’ve done so.)
<ol>
<li>Command 1</li>
<li>Command 2A</li>
<li>Command 2B – output may vary here based on bonus or non-bonus implemention d. Command 2C</li>
<li>Command 3A – should show business logic not being triggered</li>
<li>Command 3B</li>
<li>Command 3C – should show business logic being triggered but no status updates h. Command 3D</li>
<li>Command 4</li>
<li>Command 5A</li>
<li>Command 5B – output may vary here based on bonus or non-bonus implementation l. Command 5C</li>
<li>Command 5D</li>
<li>Command 6</li>
<li>Command 7 – should show error message from catch of SQLException</li>
<li>Command 8 – should show statement executed ok, but business logic not triggered</li>
</ol>
</li>
</ul>
&nbsp;

<strong>Additional Information:</strong>

Be very careful when setting up the directory structures required for the web applications running under your server (Tomcat 10.0.7 or later).&nbsp; See the course notes on servlets for the exact directory structure that must be developed.

&nbsp;

<strong>Important:</strong>&nbsp; Please name your webapp: <strong>Project3.&nbsp; </strong>Let the TAs know if you are doing the bonus problem by attaching a note to your WebCourses submission.

&nbsp;

<strong>Schematic Overview of Project Components: </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Some screen shots illustrating the application. </strong>

<strong>&nbsp;</strong>

Main client screen (initial configuration using a default query string):

&nbsp;

&nbsp;

Client simply clicks the “Execute Command” button and the SQL command in the form is executed:

&nbsp;

&nbsp;

&nbsp;

Same screen but shifted downward to show all rows returned in result.

&nbsp;

&nbsp;

Client makes a mistake entering an SQL command:

&nbsp;

<sup>&nbsp;</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; MySQL indicating the problem with <sub>&nbsp; </sub>the operation.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Inserts and updates may cause changes to the supplier status field (business logic is triggered) as shown below:

&nbsp;

Client issues the following insert command:

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Alert message when an update to the quantity field in the shipments table has caused an update of a supplier’s status in the supplier table.&nbsp; Note that in my application, I used this alert message any time the business logic was tested even if it did not trigger any updates.&nbsp; This means that this message would appear with different values even if no rows are updated (examples below).

&nbsp;

&nbsp;

After executing update command (the previous insert), client runs select * from suppliers.

&nbsp;

&nbsp;

Example of an update command that does not trigger the business logic.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Example of an update that triggers the business logic but results in no changes to any suppliers’ status.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<strong>BONUS PROBLEM:&nbsp; 15 points </strong>

&nbsp;

Instead of allowing any update/insert of a quantity &gt;= 100 to affect any supplier with a shipment involving a quantity &gt;= 100, adjust the business logic portion of your application so that an insert/update of a quantity greater than 100, causes a change to the status of only those suppliers directly affected by the update.&nbsp; For example, using the case shown above, when inserting the row (S5, P6, J7, 400) into the shipments table, only the status of supplier S5 should be increased by 5 (see screen shot below).&nbsp; However, an update such as: UPDATE shipments SET quantity = quantity + 50 WHERE pnum = “P3”, would increase by 5 the status of every supplier who ships part P3 in a quantity &gt;= 100 after the update has been issued.

&nbsp;

NOTE: If you elect to do the bonus problem, submit only this version of your application.&nbsp; Do not also submit the non-bonus problem version.&nbsp; Let the TAs know if you’ve elected to do the bonus problem or not.

&nbsp;

I will provide many hints for the bonus during the Q&amp;A sessions for this project.

&nbsp;

With the correct business logic in place…issue the original insert command as above:

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/07/654.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Immediately after issuing the update (insert above), the user reruns the select * from suppliers query:

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/07/445.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">
