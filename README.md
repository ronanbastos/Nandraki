# Nandraki.js 1.2.0
Engine game </br>

<img src="https://i.ibb.co/k6pMWgQ/index-html.png" alt="index-html" border="0"></br>

***Download engine:*** https://github.com/ronanbastos/Nandraki.js/archive/refs/heads/main.zip

***Demostração test e test2:*** 
Na pasta da engine tem arquivo test e  que tem todos os codigo de demostração:


  Test 1 html: https://github.com/ronanbastos/Nandraki.js/blob/main/nandraki-engine-js/test.html
<p>
  Test 2 html: https://github.com/ronanbastos/Nandraki.js/blob/main/nandraki-engine-js/test2.html
<p>
  Playgrand Dom : https://tironan.000webhostapp.com/test2.html
<p>
  Playgrand canvas 2D: https://tironan.000webhostapp.com/test.html
<p>
  Playgrand canvas 3D: Em andamento!  	

<p>	
# CDN 

***<script src= "https://tironan.000webhostapp.com/nandraki.js" ></script>***





# **Testar o script**  
[Testar sem inteface da engine... Crie um arquivo chamado index.html e cole o seguinte código nele]



	<!DOCTYPE html>
	<html>
	<head>

	 <script src="https://tironan.000webhostapp.com/nandraki.js"></script>

	</head>
	<body>
	<script>
	      myjogo = {
		 start : function(){

		   const txt = new Nandraki("h1","text","Ola mundo!");
		   Nandraki.create_ui(txt.obj,txt.id,"0px","100px","50px","50px");

		   const txt2 = new Nandraki("h1","text",1+1);
		   Nandraki.create_ui(txt2.obj,txt2.id,"0px","100px","50px","100px");

		 },	
	       }

	     fps=60;	
	     game.update(myjogo.start(),fps);  

	</script>
	</body>
	</html>
  
# Documentação

https://ronanbastos.github.io/Nandraki.js/

