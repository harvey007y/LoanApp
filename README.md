# LoanApp
<h2>Requirements</h2>
For this exercise, please create a Web-based OutSystems Application that meets the following User requirements:<br>
<ol>
<li>We need to process an applicant that would have the following information:</li>
First Name, Last Name, Phone Number, Email, Address, and Date of Birth
<li>We need 4 Screens for these inputs, Biographical Information, Personal Information, Happy Path, and Non-Happy Path. Biographical Information should include First Name, Last Name, Phone Number, & Email. Personal Information should include Address and Date of Birth. Happy Path and Non-Happy Path should contain simple “Congratulations!” and “We will be reaching out soon.” messages.</li>
<li>We need to ensure First Name and Last Name are filled out and that Email is a valid email address. Additionally, the applicant needs to be at least 18 years old and we need to limit the end-users State selection to the continental 48 states.</li>
	All these validation rules should include messaging to the User and Exception handling
<li>Phone Number should have an automatic mask to display the following format “(999) 999-9999”</li>
<li>When navigating between pages we should ensure that an external database has a record created or updated [NOTE: For the exercise, please just include notes on how you would go about this, for both an Azure SQL database and an API based operation]
<li>A user should be presented the Happy Path if:
 <ul>
 <li>Their First Name starts with A</li>
 <li>Their Last Name contains a W</li>
 <li>The last 2 digits of their Zip Code is greater than or equal to the month they were born</li>
 </ul>
  </li>
<li>Finally, we need a screen to display all applicants, available only to Administrators, that allows internal users to delete specific applications
<li>For production environments, every Friday at 9am an email should be sent to admin@lendr.online containing 2 Excel files [NOTE: For this exercise, just leave a note how the environment difference would be achieved]<ul>
 <li>Applications created in the last 7 days</li>
 <li>All Applications</li>
 </ul>
 </ol>
<br><br>
<p align="center"><strong>Loan Application using Outsystems</strong></p> 
<br /><br />

Here is a screenshot of Loan App Screen for Submitting Loan Application - Screen 1 - Biological Info:<br />
<center>
<a href="http://www.idealautomate.com/images/LoanApp1.PNG" target="_blank"><img src="http://www.idealautomate.com/images/LoanApp1.PNG" border="0" alt="Loan App Screen for Submitting Loan Application - Screen 1 - Biological Info" width="800px"/><br />(click to enlarge)</a>
 <br /><br /></center>
 
 Here is a screenshot of Loan App Screen for Submitting Loan Application - Screen 2 - Personal Info:<br />
<center>
<a href="http://www.idealautomate.com/images/LoanApp2.PNG" target="_blank"><img src="http://www.idealautomate.com/images/LoanApp2.PNG" border="0" alt="Loan App Screen for Submitting Loan Application - Screen 2 - Biological Info" width="800px"/><br />(click to enlarge)</a>
 <br /><br /></center>

 Here is a screenshot of Loan App Screen for Applicant Administration:<br />
<center>
<a href="http://www.idealautomate.com/images/LoanApp3.PNG" target="_blank"><img src="http://www.idealautomate.com/images/LoanApp3.PNG" border="0" alt="Loan App Screen for Applicant Administration" width="800px"/><br />(click to enlarge)</a>
 <br /><br /></center>
 
 Notes for how to send scheduled email attachments and how to update external database will be furnished upon request.
