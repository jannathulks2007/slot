# Ex02 Time Table
## Date:25/11/25

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>Slot table</title>
    </head>
    <body>
        <img src="logo.png" width="700px" height="125px">
        <h2>SLOT TIME TABLE - JANNATHUL SHABAN.A (25015672)</h2>
        <table border="1" cellspacing="2" cellpadding="5" bgcolor="lavender" width="700px" height="auto">
            <tr bgcolor="pink">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th bgcolor="pink">8-10</th>
                <td>Free Slot</td>
                <td>Python</td>
                <td>FWAD</td>
                <td>Free Slot</td>
                <td>Python</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th bgcolor="pink">10-12</th>
                <td colspan="3" align="center">FWAD</td>
                <td colspan="3" align="center">Free Slot</td>
            </tr>
            <tr>
                <th bgcolor="pink">12-1</th>
                <td colspan="6" align="center">Lunch Break</td>
            </tr>
            <tr>
                <th bgcolor="pink">1-3</th>
                <td>Free Slot</td>
                <td>C.English</td>
                <td>Free Slot</td>
                <td>Python</td>
                <td>C.English</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <th bgcolor="pink">3-5</th>
                <td colspan="2" align="center">Python</td>
                <td colspan="2" align="center">C.English</td>
                <td colspan="2" align="center">Free Slot</td>
            </tr>
        </table>
        <br><br>
        <table border="1" cellspacing="2" cellpadding="5" width="550px" height="150">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals Of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN101</td>
                <td>Communicative English (C.English)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI301</td>
                <td>Phython Programming (Phython)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-11-25 210121.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
