<script>
   let tempC=$state(0)
   let tempF=$derived((tempC*9/5)+32)

</script>
<label>Temp in C</label>
<input type="number" bind:value={tempC}><br>
<label>Temp in F</label>
<h1>{tempF}</h1>
