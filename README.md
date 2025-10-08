
# Ex03 Time Table
## Date:06.10.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```

<html> 
    <head>
        <title>My CAMU Schedule</title>
        </head>
    
           
    <body style="background-color: rosybrown">
        <center>
            <img src="/static/logo.png" width="800" height="100">
        </center>
        <br>
        <br>
            
                <center>
              <caption>SLOT TIME TABLE-DIVYA PRIYA (25018016) </caption>
        <style>
            table,th,td{
                text-align: center;
                border-color: yellowgreen;
                border: 3px solid black;    
                height: 30px;
                width: auto;
                vertical-align: center;
                scroll-behavior: smooth;
            }
        </style>
        <table>
            <tr>
            <th style="background-color: tan;">Day/Time</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">MON</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">TUE</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">WED</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">THU</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">FRI</th>
            
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">8-10</th>
            <td style="background-color: olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">Web Application</td>
            <td style="background-color: olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">Data Science</td>
            <td style="background-color: olivedrab;">Web Application</td>

        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">10-12</th>
            <td style="background-color: olivedrab;">Python</td>
            <td style="background-color: olivedrab;">Data Science</td>
            <td style="background-color: olivedrab;">Web Application</td>
            <td style="background-color: olivedrab;">Python</td>
            <td style="background-color: olivedrab;">Data Science</td>
            
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">12-1</th>
            <td style="background-color: olivedrab;" colspan="6">LUNCH</td>
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">1-3</th>
            <td style="background-color: olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">Data Science</td>
            <td style="background-color:olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">FREE SLOT <SLOT></SLOT></td> 
            <td style="background-color: olivedrab;">Data Science</td>
            
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">3-5</th>
            <td style="background-color: olivedrab;">Web Application</td>
            <td style="background-color: olivedrab;">Web Application</td>
            <td style="background-color: olivedrab;">Python</td>
            <td style="background-color: olivedrab;">Python</td>
            <td style="background-color: olivedrab;">Python</td>
        </tr>
        </table>

<br><br>

    <!-- Fagkoder og fagnavn -->
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lightgrey">
        <caption><b>SUBJECT DETAILS</b></caption>
        <tr align="center">
            <th>Sl.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19AI301</td>
            <td>Python Programming(PP)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19AI403</td>
            <td>DATA SCIEDNCE(DS)</td>
        </tr>
       
    </table>
</body>
</html>
```

## OUTPUT
![alt text](<../Screenshot 2025-10-08 140820.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.


           
      
```

## OUTPUT
![alt text](<Screenshot 2025-10-06 213855.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
