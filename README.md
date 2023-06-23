<!DOCTYPE html>
<html>
<head>
	<title>Performance Improvement Plan</title>
	<style>
		.container {
			max-width: 1000px;
			margin: 0 auto;
			padding: 20px;
			box-sizing: border-box;
			font-family: Arial, sans-serif;
			font-size: 16px;
			line-height: 1.5;
			color: #333;
		}

		h1, h2 {
			text-align: center;
			margin-top: 0;
		}

		form {
			margin-top: 20px;
		}

		label {
			display: block;
			margin-bottom: 5px;
			font-weight: bold;
		}

		select, input[type="text"], input[type="date"], textarea {
			display: block;
			width: 100%;
			padding: 8px;
			box-sizing: border-box;
			margin-bottom: 10px;
			border: 1px solid #ccc;
			border-radius: 4px;
			font-size: 16px;
			line-height: 1.5;
		}

		textarea {
			resize: vertical;
			height: 150px;
		}

		table {
			width: 100%;
			border-collapse: collapse;
			margin-bottom: 20px;
		}

		th, td {
			padding: 8px;
			border: 1px solid #ccc;
			text-align: left;
		}

		th {
			background-color: #eee;
			font-weight: bold;
		}

		.row {
			display: flex;
			flex-wrap: wrap;
			margin-bottom: 10px;
		}

		.col-25 {
			flex: 25%;
			box-sizing: border-box;
			padding: 0 10px;
		}

		.col-50 {
			flex: 50%;
			box-sizing: border-box;
			padding: 0 10px;
		}

		.col-25 select {
			width: 100%;
			height: 40px;
			padding: 8px;
			font-size: 16px;
			line-height: 1.5;
			border-radius: 4px;
			border: 1px solid #ccc;
			background-color: #fff;
			-webkit-appearance: none;
			-moz-appearance: none;
			appearance: none;
			background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32' width='32' height='32' fill='%23333'%3E%3Cpath d='M2.4 10.8l13.6 12.8c.4.4 1 .4 1.4 0l13.6-12.8c.4-.4.4-1 0-1.4s-1-.4-1.4 0L16 22.2 3.8 9.4c-.4-.4-1-.4-1.4 0s-.4 1 0 1.4z'/%3E%3C/svg%3E");
			background-repeat: no-repeat;
			background-position: right 8px center;
			background-size: 20px 20px;
			cursor: pointer;
		}

		.col-25 select::-ms-expand {
			display: none;
		}

		.col-25 select:hover, .col-25 select:focus {
			border-color: #999;
		}

		.col-75 input[type="submit"] {
			background-color: #4caf50;
			color: #fff;
			border: none;
			border-radius: 4px;
			padding: 10px 20px;
			cursor: pointer;
			font-size: 16px;
			line-height: 1.5;
			float: right;
		}

		.col-75 input[type="submit"]:hover {
			background-color: #3e8e41;
		}

		.signature {
			display: flex;
			flex-wrap: wrap;
		justify-content: space-between;
			margin-top: 20px;
		}

		.signature label {
			flex: 1;
			margin-right: 10px;
		}

		.signature input[type="text"] {
			flex: 2;
		}
	</style>
</head>
<body>
	<div class="container">
		<h1>Performance Improvement Plan</h1>
		<form>
			<div class="row">
				<div class="col-25">
					<label for="employee">Employee name:</label>
					<select name="employee" id="employee">
						<option value="">Select employee</option>
						<option value="John Smith">John Smith</option>
						<option value="Jane Doe">Jane Doe</option>
						<option value="Bob Johnson">Bob Johnson</option>
					</select>
				</div>
				<div class="col-25">
					<label for="supervisor">Supervisor/Manager name:</label>
					<select name="supervisor" id="supervisor">
						<option value="">Select supervisor/manager</option>
						<option value="Sarah Brown">Sarah Brown</option>
						<option value="Tom Wilson">Tom Wilson</option>
						<option value="Emily Davis">Emily Davis</option>
					</select>
				</div>
				<div class="col-50">
					<label for="department">Department:</label>
					<select name="department" id="department">
						<option value="">Select department</option>
						<option value="Sales">Sales</option>
						<option value="Marketing">Marketing</option>
						<option value="Finance">Finance</option>
					</select>
				</div>
			</div>
			<div class="row">
				<div class="col-25">
					<label for="job-title">Job title:</label>
					<input type="text" name="job-title" id="job-title" placeholder="Enter job title">
				</div>
				<div class="col-25">
					<label for="start-date">Start date:</label>
					<input type="date" name="start-date" id="start-date">
				</div>
				<div class="col-50">
					<label for="end-date">Agreed end date:</label>
					<input type="date" name="end-date" id="end-date">
				</div>
			</div>
			<h2>Role expectations</h2>
			<p>What is the acceptable performance expected of the employee in this role?</p>
			<textarea name="role-expectations" rows="5"></textarea>
			<h2>Areas of concern</h2>
			<p>In what areas of performance has the employee not met expectations, and what are the root causes of the issues?</p>
			<textarea name="areas-of-concern" rows="5"></textarea>
            <h2>Improvement Goals</h2>
            <table>
                <tr>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td></td>
                    <td></td>
                </tr>
            </table>
			<h2>Action plan</h2>
<p>Outline activities that are going to help achieve the improvement goals.</p>
<table>
	<thead>
		<tr>
			<th>Goal</th>
			<th>Activity</th>
			<th>Start date</th>
			<th>Deadline</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><input type="text" name="goal1"></td>
			<td><textarea name="activity1" rows="5"></textarea></td>
			<td><input type="date" name="start-date1"></td>
			<td><input type="date" name="deadline1"></td>
		</tr>
		<tr>
			<td><input type="text" name="goal2"></td>
			<td><textarea name="activity2" rows="5"></textarea></td>
			<td><input type="date" name="start-date2"></td>
			<td><input type="date" name="deadline2"></td>
		</tr>
		<tr>
			<td><input type="text" name="goal3"></td>
			<td><textarea name="activity3" rows="5"></textarea></td>
			<td><input type="date" name="start-date3"></td>
			<td><input type="date" name="deadline3"></td>
		</tr>
	</tbody>
</table>

<h2>Progress tracking</h2>
<p>How is the employee doing in achieving their improvement goals?</p>
<table>
	<thead>
		<tr>
			<th>Goal</th>
			<th>Status and comments</th>
			<th>Date of check</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><input type="text" name="goal1"></td>
			<td><textarea name="status1" rows="5"></textarea></td>
			<td><input type="date" name="date1"></td>
		</tr>
		<tr>
			<td><input type="text" name="goal2"></td>
			<td><textarea name="status2" rows="5"></textarea></td>
			<td><input type="date" name="date2"></td>
		</tr>
		<tr>
			<td><input type="text" name="goal3"></td>
			<td><textarea name="status3" rows="5"></textarea></td>
			<td><input type="date" name="date3"></td>
		</tr>
	</tbody>
</table>
<h2>Signatures</h2>
<table>
	<tr>
		<td><input type="checkbox" name="agreement" required></td>
		<td><label for="agreement">I have read and agree to follow all the items listed above for performance improvement.</label></td>
	</tr>
	<tr>
		<td>Employee:</td>
		<td><input type="text" name="employee-signature"></td>
	</tr>
	<tr>
		<td>Supervisor/Manager:</td>
		<td><input type="text" name="supervisor-signature"></td>
	</tr>
</table>

<br>

<button type="submit">Submit Form</button>
