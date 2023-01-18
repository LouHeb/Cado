<html><center>
  
 <script> function goToPage(e) { let url="https://raw.githubusercontent.com/LouHeb/Cado/main/"+e.target.value+".jpg"; console.log(url); window.open(url, '_blank'); } </script>

  
<font size="+2">Quel est ton mot magique ?</font><br>
<font size="-1">(pas de majuscules ni d'accents puis appuie sur entrée)</font><br>
<br>
  
<input onchange="goToPage(event)">
  
</center></html>
