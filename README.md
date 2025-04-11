# Ex03 Time Table
## Date:
11.04.2025

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
<html>
<head>
  <title>Abu Hanifa - Timetable</title>
  <style>
    table {
      border-collapse: collapse;
    }
    th {
      background-color: #4CAF50;
      color: white;
    }
    td {
      text-align: center;
    }
    tr:nth-child(even) td {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>

  <!-- Image at the top -->
  <img src="c:\Users\admin\Downloads\logo.png" height="100" width="400" alt="Logo">

  <h2>Abu Hanifa - Slot Timetable</h2>

  <table border="1" cellpadding="10" cellspacing="0">
    <tr>
      <th>Day / Time</th>
      <th>8 - 10</th>
      <th>10 - 12</th>
      <th>12 - 1</th>
      <th>1 - 3</th>
      <th>3 - 5</th>
    </tr>
    <tr>
      <td>Monday</td>
      <td>FREE SLOT</td>
      <td>GER</td>
      <td rowspan="5">LUNCH</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr>
      <td>Tuesday</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
      <td>MAT</td>
      <td>GER</td>
    </tr>
    <tr>
      <td>Wednesday</td>
      <td>FWAD</td>
      <td>FWAD</td>
      <td>MAT</td>
      <td>CHE</td>
    </tr>
    <tr>
      <td>Thursday</td>
      <td>PHY</td>
      <td>FWAD</td>
      <td>MAT</td>
      <td>CHE</td>
    </tr>
    <tr>
      <td>Friday</td>
      <td>CHE</td>
      <td>PHY</td>
      <td>SS</td>
      <td>FWAD</td>
    </tr>
  </table>

  <h3>Subject Details</h3>

  <table border="1" cellpadding="10" cellspacing="0">
    <tr>
      <th>S. No</th>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr><td>1</td><td>19AI414</td><td>Fundamentals of Web Application Development (FWAD)</td></tr>
    <tr><td>2</td><td>19EN612</td><td>German Basic (GER)</td></tr>
    <tr><td>3</td><td>19PH206</td><td>Physics for Information Technology (PHY)</td></tr>
    <tr><td>4</td><td>19CY205</td><td>Principles of Chemistry in Engineering (CHE)</td></tr>
    <tr><td>5</td><td>19MA201</td><td>Calculus and Matrix Algebra (MAT)</td></tr>
    <tr><td>6</td><td>19EY701</td><td>Soft Skills (SS)</td></tr>
  </table>

</body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/0cdddd9f-620d-4bdb-b776-19f9dd5428e3)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
