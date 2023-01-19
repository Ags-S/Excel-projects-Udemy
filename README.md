<h1 align = "center"> Retirement plan calcualations </h1>
<br>
<h3> Task </h3>
<p> A company (we'll call them Potent Brewing Co.) has hired you to do some calculations on the retirement plans for their employees
<br>
The data they sent you is on the sheets Participant and 2020 Contributions
<br>
They have hired you to calculate and send them the fields on the Deliverable sheet for each employee
<br>
Details on the Deliverable fields:
<br>
<ul>
<li> <b>Full Name:</b> Last Name, First Name </li>
<li> <b>Current Age:</b> calculated by the Date of Birth </li>
<li> <b>Retirement Date:</b> 65 years after their date of birth, unless they're already over 65, in which case it is two years after their next birth date </li>
<li> <b>2020 Total Contributions - 401k:</b> sum of the employee's 401k contributions in 2020.  If they did not contribute then the total is $0. </li>
<li> <b>2020 Total Contributions - Roth:</b> sum of the employee's Roth contributions in 2020.  If they did not contribute then the total is $0. </li>
<li> <b>Eligible for Bonus:</b> Potent Brewing Co. encourages their employees to retire by giving them a bonus if they save at least $20k a year.  If employee contributed at least $20k then 1, else 0.</li>
</ul>
<br>
<br>
<h3> PROCESS </h3>
<br>
  <img src = ""> <br>
  <ul>
<li> <b>Full Name: </b> To obtain Last Name and First Name merged together I have used CONCAT combined with VLOOKUP formula</li>
<li> <b>Current Age: </b> To obtain current age calculated by the Date of Birth I have used combination of DATEDIF(MATCH(TODAY))) </li>
<li> <b>Retirement Date: </b> To calculate retirement date I have used combined IF,TODAY, EDATE, INDEX and MATCH </li>
<li> <b>2020 Total Contributions - 401k: </b>To calculate sum of the employee's 401k contributions I have used SUMIFS formula </li>
<li> <b>2020 Total Contributions - Roth: </b> To calculate sum of the employee's Roth contributions i have used SUMIFS formula. </li>
<li> <b>Eligible for Bonus: </b> To calculate if the employee is eligible for bonus I have used IF combined with SUM formula</li>
</ul>
