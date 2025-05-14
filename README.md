# Ex03 Time Table
## Date: 11.04.2025

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
<! DOCTYPE html>
<html>
<head>
<TITLE>SLOT TIMETABLE</TITLE>
</head>
<body>
<center>
<img src="C:\Users\sabuh\OneDrive\Documents\logo.jpg" height="100" width="540">
</center>
<br><br>
<table align="center" border="2" cellpadding="10" bgcolor="white" >
<caption><B>SLOT TIMETABLE- Abu Hanifa(24009356)</B></caption>
<tr bgcolor="pink">
<th bgcolor="LIGHTBLUE">DAY/TIME</th>
<th>MONDAY</th>
<th>TUESDAY</th>
<th>WEDNESDAY</th>
<TH>THURSDAY</TH>
<TH>FRIDAY</TH>
</tr>
<tr bgcolor="lavender">
<td bgcolor="orange"><b>8-10</b></td>
<td><b>RPA</b></td>
<td><b>FREE</b></td>
<td><b>DE</b></td>
<td><b>STATS</b></td>
<td><b>FREE</b></td>
</tr>
<tr bgcolor="lavender">
<td bgcolor="orange"><b>10-12</b></td>
<td><b>C</b></td>
<td><b>DE</b></td>
<td><b>WEB</b></td>
<td><b>CHEM</b></td>
<td><b>C</b></td>
</tr>
<tr bgcolor="lightgreen">
<td bgcolor="orange"><b>12-1</b><td colspan="10" align="CENTER"><b>LUNCH</b>
</tr>
<tr bgcolor="lavender">
<td bgcolor="orange"><b>1-3</b</td>
<td><b>FREE</b></td>
<td><b>FREE</b></td>
<td><b>MENTOR</b></td>
<td><b>RPA</b></td>
<td><b>WEB</b></td>
</tr>
</table><br><br>
<table align="center" border="2" cellpadding="10"><b>
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr align="center">
<td><b>1.</b></td>
<td><b>19AI414</b></td>
<Td><b>Fundamentals of Web Application(WEB)</b></Td>
</tr>
<tr>
<th><b>2.</b></th>
<th><b>19AI304</b></th>
<th><b>Fundamentals of C programming(C)</b></th>
</tr>
<tr>
<th><b>3.</b></th>
<th><b>19CY205</b></th>
<th><b>Principles of Chemistry in Engineering(CHEM)</b></th>
</tr>
<tr>
<th><b>4.</b></th>
<th><b>ECA-M</b></th>
<TH><b>Mentor Meet(MENTOR)</b></TH>
</tr>
<tr>
<th><b>5.</b></th>
<th><b>19CS565</b></th>
<th><b>Robotic Process Automation(RPA)</b></th>
</tr>
<tr>
<th><b>6.</b></th>
<th><b>19EE404</b></th>
<th><b>Digital Electronics(DE)</b></th>
</tr>
</table></b>
</body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/da9fcb55-5115-40e8-9415-0b68b9c6a2bb)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
