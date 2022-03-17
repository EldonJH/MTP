# Code

This is a block of code from the FizzBuzz assignment

---

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
	var result = "";
	for (i = 1; i < 101; i++) {
		if (i % 15 == 0){
			result = "FizzBuzz";
		}else if (i % 3 == 0){
			result = "Fizz";
		}else if (i % 5== 0){
			result = "Buzz";
		}else {
			result = i;
		}
		displayHTML += "<p>" + result + "</p>";
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
  
---

- [Homepage](README.md)
- [About me](AboutMe.md)
- [Image 1](Image1.md)
- [Image 2](Image2.md)
- [Helpful Links](HelpfulLinks.md)
