# Yoga-Class-registration-system
A yoga class registration system is a software application that enables users to sign up for yoga classes and manage their registrations. It typically allows users to view available classes, choose the class they want to attend, and provide their personal information to register. 
*HTML Code for Yoga Class Registration Form*
Here's a basic HTML code for a yoga class registration form:

```
<!DOCTYPE html>
<html>
<head>
	<title>Yoga Class Registration</title>
	<style>
		body {
			font-family: Arial, sans-serif;
		}
		.container {
			width: 50%;
			margin: 40px auto;
			padding: 20px;
			background-color: #f9f9f9;
			border: 1px solid #ddd;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		label {
			display: block;
			margin-bottom: 10px;
		}
		input[type="text"], input[type="email"], input[type="tel"] {
			width: 100%;
			height: 40px;
			margin-bottom: 20px;
			padding: 10px;
			border: 1px solid #ccc;
		}
		select {
			width: 100%;
			height: 40px;
			margin-bottom: 20px;
			padding: 10px;
			border: 1px solid #ccc;
		}
		input[type="submit"] {
			background-color: #4CAF50;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}
		input[type="submit"]:hover {
			background-color: #3e8e41;
		}
	</style>
</head>
<body>
	<div class="container">
		<h2>Yoga Class Registration</h2>
		<form>
			<label for="name">Name:</label>
			<input type="text" id="name" name="name" required>
			
			<label for="email">Email:</label>
			<input type="email" id="email" name="email" required>
			
			<label for="phone">Phone:</label>
			<input type="tel" id="phone" name="phone" required>
			
			<label for="class-type">Class Type:</label>
			<select id="class-type" name="class-type">
				<option value="">Select Class Type</option>
				<option value="hatha">Hatha Yoga</option>
				<option value="vinyasa">Vinyasa Yoga</option>
				<option value="restorative">Restorative Yoga</option>
			</select>
			
			<label for="class-time">Class Time:</label>
			<select id="class-time" name="class-time">
				<option value="">Select Class Time</option>
				<option value="morning">Morning (6:00 AM - 7:00 AM)</option>
				<option value="evening">Evening (6:00 PM - 7:00 PM)</option>
			</select>
			
			<input type="submit" value="Register">
		</form>
	</div>
</body>
</html>
```

*Features:*
- *Name, Email, and Phone fields*: Collect user's basic information.
- *Class Type and Class Time dropdowns*: Allow users to select their preferred yoga class type and time.
- *Submit button*: Registers the user for the selected yoga class.

*Customization:*
You can customize the form by adding or removing fields, modifying the styles, and adding JavaScript validation to suit your requirements.
