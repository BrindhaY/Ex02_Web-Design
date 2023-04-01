# Ex.02 Implementation of Lists
## AIM
  To create list of Departments in an Institution.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Create an ordered list using ```<ol>``` tag.

### STEP-3
  List the Departments using ```<li>``` tag.

### STEP-4
  Create an unordered list using ```<ul>``` tag for nesting lists.

### STEP-5
  Open the file in a browser and verify the output.
  
## CODE
<!DOCTYPE html>
<html>
<head>
	<title>HTML List Example</title>
</head>
<body>
	<h1>List Example</h1>
	<ol>
		<li>Department of Mathematics</li>
		<li>Department of Computer Science</li>
		<li>Department of Physics</li>
	</ol>
	<ul>
		<li>Department of Biology</li>
		<li>Department of Chemistry
			<ul>
				<li>Physical Chemistry</li>
				<li>Analytical Chemistry</li>
				<li>Organic Chemistry</li>
			</ul>
		</li>
		<li>Department of English</li>
	</ul>
</body>
</html>

## OUTPUT
![Screenshot (19)](https://user-images.githubusercontent.com/127816765/229271544-80c4b215-b7d5-4728-95ea-61e0a79c23f9.png)

## RESULT
  List of Departments in an Institution is created successfully.
