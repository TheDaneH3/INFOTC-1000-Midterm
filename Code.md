## My Code Projects

[Return to homepage](README.md)

***

Here is the solution to the FizzBuzz challenge from Module 7:

```
<!DOCTYPE html>
<html>

<head>
	<meta charset="UTF-8">
	<title>Fizz Buzz</title>
	<script>

		function fizzbuzz() {
			var display = document.getElementById('display');
			var displayHTML = "";
			for (i = 1; i <= 100; i++) {
				if (i % 3 === 0) {
					displayHTML += "<p>Fizz</p>";
				}
				else if (i % 5 === 0) {
					displayHTML += "<p>Buzz</p>";
				}
				else
					displayHTML += "<p>" + i + "</p>";
			}
			display.innerHTML = displayHTML
		}

	</script>

</head>

<body onload="fizzbuzz()">
	<div id="display">

	</div>
</body>

</html>
```
