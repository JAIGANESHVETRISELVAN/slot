# Ex03 Time Table
## Date:18/03/2024

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
    <title>Timetable</title>
</head>
<body>
    <img src="logo.png" width="1300" height="150">
    <h1>JAIGANESH V(212221040063)</h1>
	<table border='3' cellspacing="4" cellpadding='3' bgcolor="cyan" >
		<tr bgcolor="yellow">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
			<th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
		</tr>
		<tr>
			<td bgcolor="yellow">8-10</td>
			<td colspan="3" align="center">FREE SLOT</td>
			<td>PHY</td>
            <td>CHE</td>
		</tr>

		<tr>
            <td bgcolor="yellow">10-12</td>
			<td>GER</td>
			<td>FREE SLOT</td>
			<td>FWAD</td>
            <td>FWAD</td>
			<td>PHY</td>
		</tr>

		<tr>
            <td bgcolor="yellow">12-1</td>
			<td colspan="5" align="center">LUNCH</td>
			
		</tr>
		<tr>
            <td bgcolor="yellow">1-3</td>
			<td colspan="2" align="center">FREE SLOT</td>
			<td>MAT</td>
			<td>MAT</td>
			<td>SS</td>
		</tr>
		<tr>
            <td bgcolor="yellow">3-5</td>
			<td colspan="2" align="center">FREE SLOT</td>
			<td>GER</td>
			<td>CHE</td>
			<td>FWAD</td>
		</tr>
	</table>
    <table border='3' cellspacing="4" cellpadding='3'>
		<tr >
			<th>S.NO</th>
			<th>Subject code</th>
			<th>Subject Name</th>
			
		</tr>
		<tr>
			<td>1.</td>
			<td>19AI414</td>
            <td>Fundamentals of Web Apllication Development</td>
		</tr>

		<tr>
            <td>2.</td>
			<td>19EN612</td>
            <td>German Basic(GER)</td>
		</tr>

		<tr>
            <td>3.</td>
			<td>19PH206</td>
            <td>Physics for Information Technology(PHY)</td>
			
		</tr>
		<tr>
            <td>4.</td>
			<td>19CY205</td>
            <td>Principles of chemistry in Engineering(CHE)</td>
		</tr>
		<tr>
            <td>5.</td>
			<td>19MA201</td>
            <td>Calculus and Matrix Algebra(MAT)</td>
		</tr>
        <tr>
            <td>6.</td>
			<td>19EY701</td>
            <td>Soft Skills(ss)</td>
		</tr>
	</table>
	</body>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-13 100419.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
