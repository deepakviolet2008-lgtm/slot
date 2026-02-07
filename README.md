# Ex02 Time Table
## Date:07.02.2026

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
        <title>Time Table</title>
    </head>
    <body align="center">
        <img src="logo.png"  align="center" width="1141" height="231">
<table align="center" border="4" cellspacing="5" cellpadding="5">
<caption><B>SLOT TIME TABLE - DEEPAK B(25018314)</B></caption>
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
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">FWAD</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">Free</td>
  </tr>
  <tr>
    <th bgcolor="pink">10-12</th>
    <td bgcolor="sky blue">FWAD</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">FWAD</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">CE</td>
  </tr>
  <tr>
    <th bgcolor="pink">12-1</th>
    <td align="center" colspan="6"  bgcolor="sky blue">LUNCH</td>
  </tr>
  <tr>
    <th bgcolor="pink">1-3</th>
    <td bgcolor="sky blue">ML</td>
    <td bgcolor="sky blue">ML</td>
    <td bgcolor="sky blue">MM</td>
    <td bgcolor="sky blue">CE</td>
    <td bgcolor="sky blue">FWAD</td>
    <td bgcolor="sky blue">FWAD</td>
  </tr>
  <tr>
    <th bgcolor="pink">3-5</th>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">CE</td>
    <td bgcolor="sky blue">Free</td>
    <td bgcolor="sky blue">CE</td>
    <td bgcolor="sky blue">Free</td>
  </tr>
</table>
<br>
<br>
<table align="center" cellspacing="5" cellpadding="5" border="4">
  <tr bgcolor="pink">
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
  </tr>
  <tr bgcolor="sky blue">
    <td>1.</td>
    <td>19AI414</td>
    <td>FUNDAMENTALS OF WEB DEVELOPMENT(FWAD)</td>
    </tr>
  <tr bgcolor="sky blue">
    <td>2.</td>
    <td>19EN101</td>
    <td>COMMUNICATIVE ENGLISH(CE)</td>
  </tr>
  <tr bgcolor="sky blue">
    <td>3.</td>
    <td>19AI410</td>
    <td>INTRODUCTION TO MACHINE LEARING(ML)</td>
    <tr bgcolor="sky blue">
    <td>4.</td>
    <td>ECA-M</td>
    <td>MENTOR MEET(MM)</td>
  </tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
