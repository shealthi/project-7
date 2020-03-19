//# project-7
//simple application form
<html>
<head>
<title>Application form</title>
</head>
<body bgcolor='PINK'>
<center>
<h1>Application form</h1>
<form>
<table>
<tr>
<td>Name</td>
<td><input type='text'size=35/></td>
</tr>
<tr>
<td>ph no</td>
<td><input type='no'size=10/></td>
</tr>
<tr>
<td>email id</td>
<td><input type='email'size=35></td>
</tr>
<tr>
<td>Gender</td>
<td><input type='radio'name='g' id='m'/>male</td>
<td><input type='radio'name='g' id='f'/>female</td> 
</tr>
<tr>
<td>Qualification</td>
<td><input type='check box'name='q' id='s'/></td> 
</tr>
<tr>
<td>address</td>
<td>
<text area row='10'cols='10'>
enter address here</text area>
</td>
</tr>
<td>District</td>
<td>
<select>
<option>manglore</option>
<option>banglore</option>
<option>mumbai</option>
</select>
</td>
</tr>
<tr>
<td>
<input type='submit'value='submit'/>
</td>
<td>
<input type='reset'value='clear'/>
</td>
</tr>
</table>
</form>
</center>
</body>
</html>
