<h1>TEST PLAN AND OUTPUT:</h1>




<h2>HIGH LEVEL TEST PLAN:</h2>




<!DOCTYPE html>

</head>
<body>
	<table>
		<thead>
			<tr>
				<th>TEST ID</th>
				<th>DESCRIPTION</th>
				<th>EXPECTED INPUT</th>
				<th>EXPECTED OUTPUT</th>
				<th>ACTUAL OUTPUT</th>
				<th>TYPE OF TEST</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>H_01&nbsp;</td>
				<td>&nbsp;check if the code is working perfectly as expected, by considiringvthe test cases.</td>
				<td>Valid Input&nbsp;</td>
				<td>Correct Output&nbsp;</td>
				<td>Correct Output&nbsp;</td>
				<td>Done By Manual Testing.&nbsp;</td>
			</tr>
			<tr>
				<td>H_02</td>
				<td>check if the system handles the boundary conditions.</td>
				<td>&nbsp;Invalid Input</td>
				<td>&nbsp;Termination</td>
				<td><span style="font-style: normal; font-weight: 400;">&nbsp;Termination</span>&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Done By Manual Testing.</span>&nbsp;</td>
			</tr>
			<tr>
				<td>H_03&nbsp;</td>
				<td>check for the flow control jumping.&nbsp;</td>
				<td>Only For Valid Input&nbsp;</td>
				<td>&nbsp;Jumping Correctly</td>
				<td><span style="font-style: normal; font-weight: 400;">Jumping Correctly</span>&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Done By Manual Testing.</span>&nbsp;</td>
			</tr>
			<tr>
				<td>H_04&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">check for the flow control jumping.</span>&nbsp;</td>
				<td>&nbsp;Only For Invalid Output</td>
				<td>&nbsp;Terminating</td>
				<td><span style="font-style: normal; font-weight: 400;">Terminating</span>&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Done By Manual Testing.</span><br></td>
			</tr>
		</tbody>
	</table>
</body>
</html>





<h2>LOW LEVEL TEST PLAN:</h2>



<!DOCTYPE html>

	
</head>
<body>
	<table>
		<thead>
			<tr>
				<th>TEST ID</th>
				<th>DESCRIPTION</th>
				<th>EXPECTED INPUT</th>
				<th>EXPECTED OUTPUT</th>
				<th>ACTUAL OUTPUT</th>
				<th>TYPE OF TEST</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>L_01</td>
				<td>Addition</td>
				<td>Int Value</td>
				<td>Int Output</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span></td>
				<td>Unit Test</td>
			</tr>
			<tr>
				<td>L_02</td>
				<td>Addition</td>
				<td>&nbsp;Float Value</td>
				<td>Termination&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_03</td>
				<td>Subtraction</td>
				<td>&nbsp;Int Value</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td>&nbsp;Int Output</td>
				<td><span style="font-style: normal; font-weight: 400;">Unit Test</span>&nbsp;</td>
			</tr>
			<tr>
				<td>L_04</td>
				<td>Subtraction</td>
				<td>&nbsp;Float Value</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Unit Test</span>&nbsp;</td>
			</tr>
			<tr>
				<td>L_05</td>
				<td>&nbsp;Multiplication</td>
				<td>&nbsp;Int Value</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_06</td>
				<td>&nbsp;Multiplication</td>
				<td>&nbsp;Float Value</td>
				<td>&nbsp;Termination&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td><span style="font-style: normal; font-weight: 400;">L_07</span>&nbsp;</td>
				<td>Division&nbsp;</td>
				<td>&nbsp;Int Value</td>
				<td>&nbsp;Int Output</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_08</td>
				<td>Division</td>
				<td><span style="font-style: normal; font-weight: 400;">Float Value</span>&nbsp;</td>
				<td>&nbsp;Termination&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_09</td>
				<td>Power&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Value</span>&nbsp;</td>
				<td>&nbsp;Int Output</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_10</td>
				<td>Power</td>
				<td><span style="font-style: normal; font-weight: 400;">Float Value</span>&nbsp;</td>
				<td>&nbsp;Termination&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_11</td>
				<td>Modulus&nbsp;</td>
				<td>&nbsp;Int Value</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td>&nbsp;Int Output</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_12</td>
				<td>Modulus&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Float Value</span>&nbsp;</td>
				<td>&nbsp;Termination&nbsp;</td>
				<td>&nbsp;Termination&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_13</td>
				<td>Factorial</td>
				<td>&nbsp;Int Value</td>
				<td>&nbsp;Int Output</td>
				<td><span style="font-style: normal; font-weight: 400;">Int Output</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
			<tr>
				<td>L_14</td>
				<td>Factoria</td>
				<td><span style="font-style: normal; font-weight: 400;">Float Value</span>&nbsp;</td>
				<td>&nbsp;Termination&nbsp;</td>
				<td><span style="font-style: normal; font-weight: 400;">Termination&nbsp;</span>&nbsp;</td>
				<td>&nbsp;Unit Test</td>
			</tr>
		</tbody>
	</table>
</body>
</html>


* Added all the files which are related to test plan and test output.
