<!DOCTYPE html>
<html>
<body>

<h1>Click đê</h1>

<button onclick="typeWriter()">Click me</button>

<p id="demo"></p>

<script>
var i = 0;
var txt = 'Chúc mừng sinh nhật ZZZ.(◞ꈍ∇ꈍ)◞⋆**✚⃞ྉ';
var speed = 50;

function typeWriter() {
  if (i < txt.length) {
    document.getElementById("demo").innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, speed);
  }
}
</script>

</body>
</html>
