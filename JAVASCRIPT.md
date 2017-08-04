* step 1:
```
<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>

<p id="demo">JavaScript can change the style of an HTML element.</p>

<script>
function myFunction() {
    document.getElementById("demo").style.fontSize = "25px"; 
    document.getElementById("demo").style.color = "red";
    document.getElementById("demo").style.backgroundColor = "yellow";        
}
</script>

<button type="button" onclick="myFunction()">Click Me!</button>

</body>
</html>
```
* step 2:
```
<!DOCTYPE html>
<html>
<body>

<img id="image" src="smiley.gif" width="304" height="228">

<script>
document.getElementById("image").src = "pic_mountain.jpg";
</script>

</body>
</html>
```
