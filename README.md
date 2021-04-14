# MoveInSync
In the above table, Id should be auto-generated whenever a new user gets added using ‘Add User’.. Id should start from 1 and gets incremented every time. Time should be the current timestamp when the new user gets added. ● The table will be empty initially. ● When the user clicks on the “Add User” button, open a form in the popup which asks mentioned details from the user. ○ Name (Text field) ○ City (Dropdown, Values - Bengaluru, Chennai, Delhi, Mumbai) ○ Degree (Text field) ● After clicking the Save button in the form, closes the popup and adds a new entry to the table.



=========HTML SCRIPT===============


<!DOCTYPE html>
<html>
<head>
	<title>MoveeInSync Assignment</title>
    <script src="./index.js"></script>
	<link rel="stylesheet" href="./index.css">
	



</head>
<body>
	<button onclick="adduser()">Add User</button>
	<table  id="show">
		<thead>
			<tr>
				<th>Name </th>
				<th>Id </th>
				<th>City </th>
				<th>Degree </th>
				<th>Timestamp</th>
			</tr>
		</thead>
	</table>
	

	
		<table id="form">
			<thead>
				<tr>
					<th>Name</th>
					<td><input type="text" name="fname" id="fname"></td>
				</tr>
			</thead>
			<tbody>
				<tr>
					<th>City</th>
					<td>
						<select id="city">
							<option value="Benguluru">Benguluru</option>
							<option value="Chennai">Chennai</option>
							<option value="Delhi">Delhi</option>
							<option value="Mumbai">Mumbai</option>
						</select></td>
				</tr>
				<tr>
					<th>Degree</th>
					<td><input type="text" name="degree" id="degree"></td>
				</tr>
				
				<tr id="btna">
					<td colspan="2"><input type="button" name="button" id="btn" value="Submit" onclick="AddRow()"></td>
				</tr>
			</tbody>
		</table>


		
	

</body>
</html>


===================================CSS SCRIPT ================================================
                                                                  

                                                              
input {
  display: block;
  border: 2px solid #ccc;
  padding: 10px;
  margin-bottom: 10px;
  width: 90%;
  border-radius: 5px;
}
#btn {
  width: auto;
}
#show {
  border: solid black 1px;
  border-collapse: collapse;
}

#show th {
  border: 1px solid black;
  background-color: #95a5a6;
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 0.03em;
}
#show td {
  border: 1px solid black;
  background-color: #ffffff;
  box-shadow: 0px 0px 9px 0px rgba(0, 0, 0, 0.1);
}

#add {
  padding: 10px;
  align-items: center;
  margin-left: 200px;
  width: 80px;
  border-radius: 5px;
}
#form {
  display: none;
  width: 200px;
  border: 2px solid #ccc;
  padding: 30px;
  background: #75cfb8;
  background-image: url("../image/7.jpeg");
  border-radius: 25px;
  margin-top: 250px;
  margin-left: 500px;
  align-items: center;
  
  
  
  
  
  
  

