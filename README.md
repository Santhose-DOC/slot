# Ex03 Time Table
## Date: 18/04/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Time Table</title>
</head>
<body>
    <center>
        <img src="logo.png" height="100" width="540">
    </center>
    <br>
    <p align="center" style="font-size: 15px;"><b>SLOT TIME TABLE-SANTHOSE AROCKIARAJ (24900171)</b></p>
    <table  align="center" width="800" style="font-size:20px;" cellpadding="5">
        <tr bgcolor="nyan" align="center">
            <th width="100">Day/Time</th>
            <th width="100">Monday</th>
            <th width="100">Tuesday</th>
            <th width="100">Wednesday</th>
            <th width="100">Thursday</th>
            <th width="100">Friday</th>
            <th width="100">Saturday</th>
        </tr>
        <tr bgcolor="yellow" align="center">
            <td bgcolor="nyan"><b>8 - 10</b></td>
            <td>Machine Learning</td>
            <td>Java Prog</td>
            <td>Advance C Prog</td>
            <td>Web Application</td>
            <td>Data Science</td>
            <td>A.I</td>
        </tr>
        <tr bgcolor="yellow" align="center">
            <td bgcolor="nyan"><b>10 - 12</b></td>
            <td>Java Prog</td>
            <td>Java Prog</td>
            <td>Java Prog</td>
            <td>Java Prog</td>
            <td>Java Prog</td>
            <td>Machine Learning</td>
        </tr>
        </tr>
        <tr bgcolor="yellow" align="center">
            <td bgcolor="nyan"> <b>12 - 1</b></td>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr bgcolor="yellow" align="center">
            <td bgcolor="nyan"><b>1 - 3</b></td>
            <td>Java Prog</td>
            <td>Java Prog</td>
            <td>Mentor Hour</td>
            <td>Java Prog</td>
            <td>Java Prog</td>
            <td>Data Science</td>
        </tr>
        <tr bgcolor="yellow" align="center">
            <td bgcolor="nyan"><b>3 - 5</b></td>
            <td>Web Application</td>
            <td>Data Science</td>
            <td>A.I</td>
            <td>A.I</td>
            <td>Machine Learning</td>
            <td>Web Application</td>
        </tr>
    <br>

    </table>

    <br>
    <br>
    <style>
        table, th, td {
        border: 1px solid black;
      }
      </style>

    <table align="center" width="700" style="font-size:20px;">
        <tr align="center">
            <th width="100">S.no</th>
            <th width="100">Subject Code</th>
            <th width="500">Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Development</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19AI405</td>
            <td>Fundamentals of Artificial Intelligence</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19AI410</td>
            <td>Introduction to Machine Learning</td>
        </tr>
        <tr align="center">
            <td>4.</td>
            <td>19AI304</td>
            <td>Fundamental of C Programming</td>
        </tr>
        <tr align="center">
            <td>5.</td>
            <td>19AI403</td>
            <td>Introduction to Data Science</td>
        </tr>
        <tr align="center">
            <td>6.</td>
            <td>19AI302</td>
            <td>Engineering Design and Modelling</td>
        </tr>
        <tr align="center">
            <td>7.</td>
            <td>19PH814</td>
            <td>Physics for Quantum Computing</td>
        </tr>
        <tr align="center">
            <td>8.</td>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
        <tr align="center">
            <td>9.</td>
            <td>19EE305</td>
            <td>Basic Electrical, Electronics and Measurement Engineering</td>
        </tr>
        <tr align="center">
            <td>10.</td>
            <td>19EY709</td>
            <td>Reasoning Ability</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-04-18 204846-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
