# evalucion-css
CSS y Diseño Web Responsive > Evaluación Final
<html>
<head>
	<meta name="viewport" content="width=device-width, user-scalable=no,initial-scale=1.0">
	<title>Comenzando con la fotografía</title>
	<<link href="https://fonts.googleapis.com/css?family=Dancing+Script&display=swap" rel="stylesheet"> 
	<link rel="stylesheet" href="css/estilos.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<div class="contenido">
	
	
	  <div class="confotr">
	    <h1>
		  Comenzando con la fotografía
	    </h1>
	  
		  <nav>
			  <ul class="menu">
			    <li><a href="index.html" style="text-decoration: none;">Inicio</a></li>
			    <li><a href="paisajes.html">Paisajes</a></li>
			    <li><a href="retratos.html">Retratos</a></li>
			   </ul>
		  </nav>
	  </div>
	

	
<section id="conten1">
  <div class="imagen1">
	<img src="imagenes/fotografo-realizo-un-book.jpg" >
  </div>
</section>


  
  

  <div class="container" align="center">

    <section class="columna-1">
    	<a href="paisajes.html">
    	<img src="imagenes/fotografia-01.jpg" >
    	<p style="color: #000; font-size: 18px;">Paisajes</p>
    	</a>
    </section>

    <section class="columna-2">
    	<a href="retratos.html">
    	<img src="imagenes/fotografia-02.jpg" >
    	<p style="color: #000; font-size: 18px;">Retratos</p>
    	</a>
    </section>

  </div>
  


<footer>
	<div class="contafooter">

    		<section><h4>Contacto</h4>
    						  <p>medios-86@hotmail.com
    						  <br>057 312 8764546</p>
    		</section>

    		<section><h4>Términaos</h4>
    						  <p>Términos y Condiciones de
    						  <br>Uso del Sitio Web</p>
    		</section>

		    <section id="redessociales"><h4>Redes Sociales</h4>
		    		<a href="https://www.facebook.com/">
		    		<img src="imagenes/icon-facebook.png"></a>
		    		<a href="https://www.instagram.com/">
		    		<img src="imagenes/icon-instagram.png"></a>
		    		<a href="https://www.youtube.com/">
		    		<img src="imagenes/icon-youtube.png"></a>
		    </section>

    		<section id="espaabajo"><h4>Derechos</h4>
    				 <p>johnvargas©Copyright 2020</p>
    		</section>

  	</div>
</footer>
</div>

<style>
body {
	margin: 20px;
	background-color: #02010a;
	font-family: 'Dancing Script', cursive;
  animation-duration: 1.5s;
  animation-name: slidein;
}

@keyframes slidein {
    from {
        margin-top: 150%;
        }
 
    to {
        margin-top: -5%;
        }
}

.contenido{
	width: 900px;
	margin: auto;
}

@media screen and (max-width: 900px) {
            .contenido{
               max-width: 100%;
            }
         }

.row {
  display: flex;
}

.menu {
  display: flex;
  justify-content: right;
  margin: 0 auto;
  list-style: none;
}

.menu li {
  width: 80px;
  height: 30px;
  text-align: center;
}
 .menu a {
   font-size: 16px;
   color: #fff;
   text-shadow: 2px 2px #02010a;
  }

@media screen and (max-width: 900px) {
        .menu {
        float: none;
        width: 100%;
        position: relative;
			  top: 25px;
			  left: -30%;
        }
}

.confotr {
    flex: 50%;
    background-color: #5b7989;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    padding-left: 20px;
  	padding-top: 20px;
  	padding-bottom: 20px;
  	padding-right: 20px;
}

.confotr h1{
	color: #FFFFFF;
	font-size: 24px;
	margin-bottom: -20px;
	text-shadow: 2px 2px #02010a;
}

.imagen1{
	background-color: #82c3a6;
	padding-top: 30px;
	padding-bottom: 30px;
}

.imagen1 img{
	display:block;
  margin:auto;
	width: 80%;
	box-shadow: 2px 2px 8px #002010;
	
}

.conten1 {
	display: flex;
	flex-direction: column;
}

.container {
  display: -webkit-flex;
  display: flex;
  -webkit-flex-flow: row wrap;
  flex-flow: row wrap;
  padding-top: 30px;
  background-color: #d5c75f;
}

.container img{
  width: 80%;
  border: 1px solid black;
  box-shadow: 2px 2px 8px #002010;
}

.columna-1{
	padding-bottom: 40px;
	transition: all 0.5s ease;
}

.columna-1:hover{
	transform: rotate(10deg);
}

.columna-2{
	padding-bottom: 40px;
	transition: all 0.5s ease;
}

.columna-2:hover{
	transform:translate(20px, -5px);
}

.columna-2 img:hover{
	box-shadow: 2px 2px 8px #82c3a6;
}

.columna-1, 

.columna-2,

.columna-3,

.columna-4,

.columna-5, {

  width: 100%;

}



footer {
	color: #000000;
	text-align: center;
	background-color: #C6d5c5;
  border-radius: 0px 0px 10px 10px;
  -moz-border-radius: 0px 0px 10px 10px;
  -webkit-border-radius: 0px 0px 10px 10px;
  border: 0px solid #000000;
}

.contafooter{
	display: flex;
  flex-flow: row;
  margin-left: auto;
  margin-right: auto;
}

.contafooter section{
  padding: 10px 0px 10px 0px;
  margin-left: auto;
  margin-right: auto;
}

.contafooter h4{
  font-size: 20px;
  font-weight: bold;
}

.contafooter p{
  font-size: 14px;
  margin-top: -25px;
}

.columna1, 

.columna2, 

.columna3, 

.columna4,

.columna5,

.columna6, {

  width: 100%;

}

@media (max-width: 900px) {

  .columna1 { width: 50%; }

  .columna2 { width: 50%; }

  .columna3 { width: 50%; }

  .columna4 { width: 50%; }
  
  .columna5 { width: 50%; } {

    width: 33.3%;

  }

 .contafooter {
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
    
  }

}


@media (min-width: 900px) {

  .columna-1 { width: 50%; }

  .columna-2 { width: 50%; }

  .columna-3 { width: 30%; }

  .columna-4 { width: 30%; }

  .columna-5 { width: 30%; }
  {
    width: 33.3%;
  }

}

#redessociales img{
    width: 30px;
    position: relative;
    top: -20px;

}





.container-gal {
  display: -webkit-flex;
  display: flex;
  -webkit-flex-flow: row wrap;
  flex-flow: row wrap;
  padding-top: 30px;
  background-color: #d5c75f;
}

.container-gal img{
  width: 100%;
  border: 1px solid black;
  box-shadow: 2px 2px 8px #002010;
}

.columna-3{
  padding-bottom: 20px;
  margin-left: 20px;
}

.columna-4{
  padding-bottom: 20px;
  margin-left: 20px;
}

.columna-5{
  padding-bottom: 20px;
  margin-left: 20px;
}

@media (max-width: 900px) {

.columna-3{
  margin-left: auto;
  margin-right: auto;
  }

.columna-4{
  margin-left: auto;
  margin-right: auto;
  }

.columna-5{
  margin-left: auto;
  margin-right: auto;
  }

.container-gal img {
    width: 80%;
 }

.container-gal {
    padding-top: 15px;
    padding-bottom: 0px;
 }

 .contafooter section{
  padding: 0px;
  }

  #espaabajo{
    padding-bottom: 15px;
  }
}

#imagen1 img{
  -webkit-filter: blur(10px);
  filter: blur(10px);
  
}

#imagen2 img{
  -webkit-filter: grayscale(100%);
  filter: grayscale(100%);
}

#imagen3 img{
  -webkit-filter: sepia(90%);
  filter: sepia(90%);
}


</style>

</body>
</html>
