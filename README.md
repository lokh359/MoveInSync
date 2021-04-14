# MoveInSync
In the above table, Id should be auto-generated whenever a new user gets added using ‘Add User’.. Id should start from 1 and gets incremented every time. Time should be the current timestamp when the new user gets added. ● The table will be empty initially. ● When the user clicks on the “Add User” button, open a form in the popup which asks mentioned details from the user. ○ Name (Text field) ○ City (Dropdown, Values - Bengaluru, Chennai, Delhi, Mumbai) ○ Degree (Text field) ● After clicking the Save button in the form, closes the popup and adds a new entry to the table.
<!DOCTYPE html>
<html>
<head>
	<title>Assignent oF MovieSync</title>
</head>
<body>
	<script type="text/javascript">
		function display() {
			var name=document.form1.name.value;
			alert("name "+name);
			// body...
		}
	</script>
		<form name="form1">
		Add User:<input type="text" name="name"/>
		<input type="button" onclick ="display()" value="print name"/>
		</form>
	<table border=3 align="CENTER" bgcolor="cyan">

	<tr>
		<th>Name</th>
		<th>Id</th>
		<th>City</th>
		<th>Degree</th>
		<th>TimeStamp</th>
	</tr>
	<tr>
		<td>MovieSync</td>
		<td>1</td>
		<td>
			<select>
				<option selected="selected" value="">Select any one</option>
				<option value="Bengaluru">Banglore</option>
			<option value="Chennai">Chennai</option>
			<option value="Mumbai">Mumbai</option>
			<option value="Delhi">Delhi</option>
		</select>

		</td>
		<td><input type="text" name=""></td>
		<td><input type="datetime-local" id="birthdaytime" name="birthdaytime"></td>
	</tr>
</table>

</body>
</html>
