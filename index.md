<!DOCTYPE html>
<html>
<body>

<h2>My First JavaScript</h2>

<script>

   var rad;
   do {
   rad = prompt("")
   if (rad == "" || rad == null)
   break;
   
   alert("radius = " + rad + ", area = " + area(rad));
   }
   while (rad != "" && rad != null);
   
   function area(r) {     	return 3.141592654 * r * r;     }

</script>
</body>
</html> 
