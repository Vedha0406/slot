# Ex03 Time Table
## Date:03/04/2024

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
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.jpeg" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIMETABLE - G.VEDHASHREE (23011692)</b></caption>
<tr align="center">
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
	<th bgcolor="yellow">Friday</th>
    <th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="yellow">8-10</th>
	<td>Creative skills</td>
	<td>FREE</td>
	<td>French</td>
	<td>Web development</td>
	<td>Web development</td>
    <td>Python with linear algebra</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">10-12</th>
	<td>FREE</td>
	<td>Python with linear algebra</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>Fundamentals of C</td>
    <td>FREE</td>
    
</tr>
<tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">1-3</th>
	<td>Chemistry</td>
	<td>French</td>
	<td>Communicative English</td>
	<td>FREE</td>
	<td>Python with linear algebra</td>
    <td>FREE</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">3-5</th>
	<td>Fundamentals of C</td>
	<td>Web development</td>
	<td>Python with linear algebra</td>
	<td>Python with linear algebra</td>
	<td>Communicative English</td>
    <td>Chemistry</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI301C</td>
<td>Python with linear algebra</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Web development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td>Communicative English</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Chemistry</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY702</td>
<td>Creative skills</td>
</tr>
<tr>
 <td align="center">6.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EN611C</td>
<td>French</td>
</tr>
</table>
</body>
</html>


## OUTPUT
![image](https://github.com/Vedha0406/slot/assets/150884870/bc56f4fc-a7f1-4465-8636-4a9ab413198d)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
