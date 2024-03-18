# Ex03 Time Table
## Date:
13/03/2024

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

## PROGRAM:
```
html>
    <head>
        <title>
            MY TIME TABLE
        </title>
    </head>
        </head>
        <body align="center">
            <img src="logo.png" height="200" width="1000">
        </body>
<table align="center" border="1">
    <caption>SLOT TIMETABLE-SARANYA S(212223220101)</caption>
    <tr bgcolor="lightblue">
        <th>DAY/TIME</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr>
        <td bgcolor="lightblue">8-10</td>
        <td bgcolor="cyan">BFA</td>
        <td bgcolor="purple">DE</td>
        <td bgcolor="white">FWAD</td>
        <td bgcolor="purple">DE</td>
        <td bgcolor="pink">Free slot</td>
        <td bgcolor="lightyellow">CSOC</td>
    </tr>
    <tr>
        <td bgcolor="lightblue">10-12</td>
        <td bgcolor="grey">EBD</td>
        <td bgcolor="white">FWAD</td>
        <td bgcolor="orange">PQM</td>
        <td bgcolor="pink">Free Slot</td>
        <td bgcolor="#D6EEEE">FOCP</td>
        <td bgcolor="pink">Free Slot</td>
    </tr>
    <tr colspan="6" bgcolor="peach">
        <td bgcolor="lightblue">12-01</td>
        <td colspan="7" align="center">Lunch</td>
    </tr>
    <tr>
        <td bgcolor="lightblue">01-03</td>
        <td bgcolor="white">FWAD</td>
        <td bgcolor="pink">Free Slot</td>
        <td bgcolor="pink">Free Slot</td>
        <td bgcolor="lightorange">CD</td>
        <td bgcolor="pink">Free slot</td>
        <td bgcolor="orange">PQM</td>
    </tr>
    <tr>
        <td bgcolor="lightblue">03-05</td>
        <td bgcolor="#D6EEEE">FOCP</td>
        <td bgcolor="lightorange">CD</td>
        <td bgcolor="pink">Free Slot</td>
        <td bgcolor="grey">EBD</td>
        <td bgcolor="cyan">BAF</td>
        <td bgcolor="pink">Free Slot</td>
    </tr>
<br>
<br>
</table>
<table align="center" border="1" bgcolor="#D6EEEE">
<tr>
     <th>S.NO</th>
     <th>SLOT NO</th>
     <th>SLOT NAME</th>
</tr>
<tr>
    <td>1.</td>
    <td>19AI304</td>
    <td>Fundamental of C programming </td>
</tr>
<tr>
    <td>2.</td>
    <td>19AI414</td>
    <td>Fundamental of web application development</td>
</tr>
<tr> 
    <td>3.</td>
    <td>19CS409</td>
    <td>Compiler Design</td>
</tr>
<tr>
     <td>4.</td>
    <td>19CS542</td>
    <td>Embedded Board Design</td>
</tr>s
<tr>
    <td>5.</td>
    <td>19EE404</td>
    <td>Digital Electronics</td>
</tr>
<tr>
    <td>6.</td>
    <td>19EY702</td>
    <td>Creative Skills for Communication</td>
</tr>
<tr>
    <td>7.</td>
    <td>19MA222</td>
    <td>Probability and Queueing Model</td>
</tr>
<tr>
    <td>8.</td>
    <td>19MS154</td>
    <td>Basic Financial Accounting</td>
</tr>
</html>
```

## OUTPUT
![alt text](<My time table.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
