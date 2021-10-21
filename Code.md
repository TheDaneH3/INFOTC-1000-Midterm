## My Code Projects

[Return to homepage](README.md)

***

Here is my solution to the FizzBuzz challenge from Module 7:

```html
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

***

Here is my solution for the Object Position Calculation challenge from Module 6:

```python
print("Please enter the following values in a decimal format.\n")

init_pos = float(input("Enter the object's initial position: "))
init_vel = float(input("Enter the object's initial velocity: "))
acceleration = float(input("Enter the object's acceleration: " ))
elapsed_time = float(input("Enter how much time has passed: "))

final_vel = init_pos + (init_vel * elapsed_time) + (0.5 * acceleration * elapsed_time ** 2)

print("\nThe object's final position is: ", final_vel)
print("\nPress Enter to exit")
```
