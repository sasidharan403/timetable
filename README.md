# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>

   <body>
      <img src=./logo.png>
      <table border = "1" cellspacing="1" bordercolor="PURPLE" bgcolor="LIGHTGREY">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
           <th colspan="2">Reference Number:</th>
           <th colspan="2">21002965</th>
           <th colspan="2">Name:</th>
           <th colspan="2">S.Harish Kumar</th>
         </tr>
         <tr>
           <th>DAYS</h>
          <th>08:00-09:00</th>
          <th>09:00-10:00</th>
          <th>10:00-11:00</th>
          <th>11:00-12:00</th>
         
          <th rowspan="6">lunch break</th>
            <th>01:00-02:00</th>
            <th>02:00-03:00</th>
         </tr>
          <tr>
             <td>MONDAY</td>
             <td>19EY703/Anbukannan</td>
             <td>19EY703/Anbukannan</td>
             <td>19MA221/Jaba Jasphin E.T</td>
             <td>19MA221/Jaba Jasphin E.T</td>
             <td align="center">19MA220/Jaba Jasphin E.T</td>
             <td align="center">19MA220/Jaba Jasphin E.T</td>
         </tr>
          <tr>
             <td>TUESDAY</td>
             <td>19AI402/Karthik Govindaraju</td>
             <td>19AI402/Karthik Govindaraju</td>
             <td>19AI303/Sridhar</td>
             <td>19AI303/Sridhar</td>
             <td align="center">19AI302/SellaKumar S</td>
             <td align="center">19AI302/SellaKumar S</td>
         </tr>
         <tr>
             <td>WEDNESDAY</td>
             <td>19AI401/Karthik Govindaraju</td>
             <td>19AI401/Karthik Govindaraju</td>
             <td>19MA220/Jaba Jashpin</td>
             <td>19MA220/Jaba Jashpin</td>
             <td align="center">-</td>
             <td align="center">-</td>
         </tr>
         <tr>
             <td>TURSDAY</td>
             <td>19AI303/Sridhar</td>
             <td>19AI303/Sridhar</td>
             <td>19AI301/Jaba Jashpin</td>
             <td>19AI301/Jaba Jashpin</td>
             <td align="center">19AI302/Sridhar</td>
             <td align="center">19AI302/Sridhar</td>
         </tr>
          <tr>
             <td>FRIDAY</td>
             <td>19AI401/Karthik Govindaraju</td>
             <td>19AI401/Karthik Govindaraju</td>
             <td>19AI301/Jaba Jashpin</td>
             <td>19AI301/Jaba Jashpin</td>
             <td align="center">-</td>
             <td align="center">-</td>
         </tr>
 
         
      </table>
      1. 19EY703-System of Numerical and Logical
      2. 19MA220-Mathematics for Artificial Intelligence
      3. 19MA221-Linear Algebra Laboratory
      4. 19AI301-Python Programming
      5. 19AI302-Engineering Design and Modeling
      6. 19AI303-Engineerng Mechanics and Product
     
   </body>
</html>
~~~
# OUTPUT