<!DOCTYPE html>
<html>
<head>
<title>Joucul me</title>
</head>
<body>

<h1>Puncte: <span id="score">0</span></h1>

<button onclick="addPoint()">Apasă pentru punct</button>

<br><br>
<!-- Buton Discord -->
<a href="https://discord.gg/wktxRNyKs" target="_blank">Intră pe Discord!</a>

<script>
let score = 0;

function addPoint(){
  score++;
  document.getElementById("score").innerText = score;
}
</script>

</body>
</html>
