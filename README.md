# Dropdown-menu
seek help. want to know why java codes do not work. I want to create a dependant dropdown menu. but cannot get the output. can anyone here tell me what I am supposed to do here please


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>1Dependant Dropdown Menu</title>

  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  
  </head>
 <script type = "text/javascript">
  var cars={
  sedan:['Honda1', 'Honda2', 'Honda3', 'Honda4', 'Honda5',],
  sedan:['Boleroa1', 'waza2', 'wazanda3', 'Hajshsjnda4', 'Honsjhdjshdda5',],
  sedan:['ccconda1', 'cconda2', 'Hsdsdsonda3', 'Honsdsdsda4', 'vvv5',],
}

var main=document.getElementById('main_menu');
var sub=document.getElementById('sub_menu');

main.addEventListener('change', function(){
	var selected_option = cars[this.value];
	
while (sub_options.length > 0){
	sub_options.remove(0);
}

array.from(selected_options).forEach(function(el){
	let option = new option(el el);
	sub.appendChild();
</script>
  <body>
  
    <div class="container mt-5">
	  <div class="row">
	    <div class="col-md-3">
		  <h5>Chakula byenye Unataka</h5>
		</div>
     <div class="col-md-3">
       <select name="car" id="main_menu" class="custom-select">
         <option value="Suv">Suv</option>
         <option value="Sedan">Sedan</option>
         <option value="4x4">4x4</option>
         <option value="truck">Truck</option>
       </select>
     </div>
     <div class="col-md-3"></div>
       <select name="carname" id="sub_menu" class="custom-select">
       </select>
   </div>
   </div>
