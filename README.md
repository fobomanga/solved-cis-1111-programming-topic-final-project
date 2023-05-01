Download Link: https://assignmentchef.com/product/solved-cis-1111-programming-topic-final-project
<br>
Design and develop a program that uses the data in four arrays of data to compute and display payroll information, the final Step in the program should write the payroll information to a backup file. The arrays are as follows:

<ul>

 <li>empID: an array of seven integers to hold employee identification numbers. The array should be initialized to the following numbers:</li>

</ul>

5658845 4520125 7895122 8777542 845277 1302850 7580489,

<ul>

 <li>hours: an array of seven integers to hold the number of hours worked by each employee</li>

 <li>payRate: an array of seven doubles to hold each employee’s hourly pay rate</li>

 <li>wages: an array of seven doubles to hold each employee’s gross wages</li>

</ul>

The program should relate the data in each array through the subscripts. For example, the number in element O of the hour’s array should be the number of hours worked by the employee whose identification number is stored in element O of the emplD array. That employee’s pay rate should be stored in element O of the payRate array.

Develop functions to perform the following:

<ul>

 <li>Function getEmpIoyeeOata should display each employee number and ask the user to enter the hours that employee worked and the hourly pay rate. DO not accept negative values for hours worked or a pay rate less than $15.00. At least two employees should have worked more than 40 hours, Or overtime, during the week. This data should be stored in the appropriate arrays.</li>

 <li>Function calculatePay should calculate the gross pay for each employee (hours times pay rate) and store the gross pay in the wages array. The gross pay for at least two employees should include overtime pay.</li>

</ul>

After the data has been entered for all the employees and the gross pay for each employee has been calculated, the program should properly label and display each employee’s identification number, hours worked, pay rate, and wages. Add an additional column to your Output that marks employees whose gross pay included overtime pay. Place two asterisks (• •) in this column.

The last step in the program should write the all the payroll data to a backup file named ‘PayrollOataBackup.txt’. This file should contain seven rows of data, one for each employee. The data for each employee should not include his or her gross pay.

Additional Requirements:

<ol>

 <li>All console window output must be labeled and easy to read.</li>

 <li>Liberal program comments are expected.</li>

</ol>

3_ You may use any we have studied during this course.