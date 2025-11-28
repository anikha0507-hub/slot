# Ex02 Time Table
## Date: 28.11.2025

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
    <body>
        <img src="logo.png" width="900" height="300">
        <table border="2" cellspacing="10" cellpadding="4">
            <caption>Slot-TimeTable</caption>
            <tr bgcolor="lightblue">
                <th>Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="pink">
                <td>8-10</td>
                <td>FREESLOT</td>
                <td>PYPGM</td>
                <td>FREESLOT</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREESLOT</td>
            </tr>
            <tr bgcolor="pink">
                <td>10-12</td>
                <td>FREESLOT</td>
                <td>ENG</td>
                <td>PYPGM</td>
                <td>ENG</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="pink">
                <td>12-1</td>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr bgcolor="pink">
                <td>1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MM</td>
                <td>ENG</td>
                <td>FREESLOT</td>
                <td>FREESLOT</td>
            </tr>
        </table>
        <br>
        <table border="1" cellspacing="10" cellpadding="4">
            <tr>
                <th>S.No</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming(PYPGM)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English(ENG)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>ECA-M</td>
                <td>Mentor Meet(MM)</td>
            </tr>
            
        
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-11-28 084036.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
