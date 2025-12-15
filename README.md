<!DOCTYPE DOCTYPE html>
<html>
<title>Pounds to kilograms Weight converter</title>
<body>

<h2>Weight converter</h2>

<p>Type a value in the pounds field to convert
the value to kilograms :</p>

<p>
<label>Pounds</label>
<input id="inputPounds" type="number"
placeholder="Pounds"
oninput="weightConverter(this.value)"
onchange="weightConverter(this.value)">
</p>

<p>Kilograms: <span id="outputKilograms"></span></p>

<script>
function weightConverter(valNum) {
    document.getElementById("outputKilograms").innerHTML = valNum / 2.2046;
}
</script>

</body>
</html>
