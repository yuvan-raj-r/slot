# Ex02 Time Table
## Date:27-11-2025

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
        <title>slot Timetable</title>
    </head>
    <body>
        <center>
        <img src="/static/logo.png" height="150" width="600">
        </center>
        <br>
        <table align="center" width="700" cellspacing="4" cellpadding="4" border="6" bgcolor="orange">            
    <caption><b>SLOT TIME TABLE - YUVAN RAJ R(25014899)</b></caption>
        <tr align="center">
            <th bgcolor="cyan">Date/Time</th>
            <th bgcolor="cyan">Monday</th>
            <th bgcolor="cyan">Tuesday</th>
            <th bgcolor="cyan">Wednesday</th>
            <th bgcolor="cyan">Thursday</th>
            <th bgcolor="cyan">Friday</th>
            <th bgcolor="cyan">saturday</th>
        </tr>
     <tr align="center">
            <td bgcolor="cyan">8-10</td>
            <td>Free slot</td>
            <td>C PROG</td>
            <td colspan="2" align="center">Free slot</td>
            <td>WEB</td>
            <td>PS</td>
        </tr>
        <tr align="center" >
            <td bgcolor="cyan">10-12</td>
            <td>C PROG</td>
            <td>Free slot</td>
            <td>PS</td>
            <td>Free slot</td>
            <td colspan="2" align="center">WEB</td>
        </tr>
        <tr  align="center">
            <td bgcolor="cyan">12-1</td>
            <td colspan="6" align="center">L U N C H</td>
        </tr>
        <tr align="center">
            <td bgcolor="cyan">1-3</td>
            <td colspan="2" align="center">WEB</td>
            <td>MM</td>
            <td>PS</td>
            <td>Free slot</td>
            <td>PS</td>
        </tr>
        <tr align="center">
            <td bgcolor="cyan">3-5</td>
            <td>Free slot</td>
            <td colspan="3" align="center">C PROG</td>
            <td colspan="2" align="center">Free slot</td> 
        </tr>
        </table>
        <br>
        <table align="center" cellspacing="3" cellpadding="4" border="8">
            <tr align="center">
                <th>S.no</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME </th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td align="center">Fundamentals of WEB application development(WEB)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td align="center">Fundamentals of c programming(C PROG)</td>  
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EN105</td>
                <td align="center">Public Speaking(PS)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">ECA-M</td>
                <td align="center">Mentor Meet(MM)</td>
            </tr>
            </table>
        </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2025-11-27 201117.jpg>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
