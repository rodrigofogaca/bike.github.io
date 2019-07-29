# bike.github.io
<!DOCTYPE html>
<html>
<head>
	<title>VintageBike</title>
	<link rel="icon" href="img/icon1.png">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">

    <!-- HTML5Shiv -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
    <![endif]-->

	<link rel="stylesheet" type="text/css" href="css/estilo.css">	
  </head>
<body id="fundo">

	<!--Inicio-->

    <header class="fixed-top">
      <nav class=" navbar-expand-md ">
      	 <div class="container "><!--inicio container-->

      	<!--logo-->
			<a href="index.html">
				<img class="logo" src="img/logo2.png">
			</a>
		</div>
		
      <!--menu hamburger-->    
      <button  class="navbar-toggler float-right"  data-toggle="collapse" data-target="#nav-principal">
        <i class="fas fa-bars" style="color: #A0522D" ></i>
     </button>
    
		 <!--Navegação-->	
			<div class="collapse navbar-collapse" id="nav-principal">
	          <ul class="navbar-nav ml-auto">
	            <li><a href="index.html">Home</a></li>
	            <li><a href="modelos.html">Modelos</a></li> <!--abrira a pagian de modelos-->
	            <li><a href="historia.html">História</a></li>
	            <li><a href="fotos.html">Fotos</a></li>
	          </ul>
	        </div>
	   	 </nav>   	 
      </header><!--Fim do cabeçalho-->



		<section>
  		      	<!--Inicio carrossel-->
              <div class="carrossel">
			         <div id="carousel-spotify" class="carousel slide" data-ride="carousel">

			          <div class="carousel-inner"><!--inner-->
			            
			            <div class="carousel-item active">
			              <img src="img/bg1.jpeg" class="img-fluid foto1">
                    <div class="close-caption">
			            </div>
                </div>

			            <div class="carousel-item">
			              <img src="img/bg2.jpg" class="img-fluid foto2">
			            </div>

			            <div class="carousel-item">
			              <img src="img/bg3.jpg" class="img-fluid foto3" width="1400">
			            </div>

			            <div class="carousel-item">
			              <img src="img/bg4.jpg" class="img-fluid foto4">              
			            </div>
			          </div><!--fim inner-->

			          <!--Controles do carrosel-->
			          <a href="#carousel-spotify" class="carousel-control-prev" data-slide="prev">
			            <i class="fas fa-angle-left fa-2x"></i>
			          </a>

			          <a href="#carousel-spotify" class="carousel-control-next" data-slide="next">
			            <i class="fas fa-angle-right fa-2x"></i>
			          </a>

			       </div>
			      </div>
			    </div><!--fim row-->
        </section>

        <br>
        <br>
  
        <section>             
        
           	<div class="caixa">
                 <a href="modelos.html"><img src="img/venda1.jpg" class="item" ><p class="ml-5">Feminina Ceci</p></a>    
                 <a href="modelos.html"><img src="img/venda2.jpg" class="item"><p class="ml-5">Modelo Blitz</p></a>
                 <a href="modelos.html"><img src="img/venda3.jpg" class="item img-fluid d-none d-sm-block d-md-block"><p class="ml-5 d-none d-sm-block d-md-block">Gamma Cruizer</p></a><!--d-none d-md-block esconde a foto quando em telas menores md-->
                 <a href="modelos.html"><img src="img/venda4.jpg" class="item img-fluid d-none d-sm-block d-md-block"><p class="ml-5 d-none d-sm-block d-md-block">Modelo XDS Nadine</p></a> 
                </div>

            <div class="caixa">
               <a href="modelos.html"><img src="img/venda13.jpg" class="item"><p class="ml-5">Retrô Canadense</p></a>
               <a href="modelos.html"><img src="img/venda14.jpg" class="item"><p class="ml-5">Speed Vintage</p></a>
               <a href="modelos.html"><img src="img/venda7.jpg" class="item img-fluid d-none d-sm-block d-md-block" ><p class="ml-5 d-none d-sm-block d-md-block">Retrô Tiffany</p></a>
               <a href="modelos.html"><img src="img/venda8.jpg" class="item img-fluid d-none d-sm-block d-md-block"><p class="ml-5 d-none d-sm-block d-md-block">Feminina Groove</p></a>
              </div>
          </section>

          <article><!--caixa de informaçao-->
            <div class="jumbotron">
              <div class="container">
               <ul class="list-unstyled">
                   <li class="media border-bottom pb-2">
                      <img src="img/primeira.jpg" width="250" class="mr-2 align-self-start">
                      <div class="media-body">
                        <h5 class="display-7">Curiosidade</h5>
                        <p class="lea">
                          Chegada da bicicleta no Brasil
                        </p><hr>

                        <p>
                          No final do século XIX, a bicicleta chegou ao Brasil vinda da Europa. Os primeiros relatos de sua existência em território brasileiro são no Paraná, mais precisamente em Curitiba, cidade que recebeu muitos imigrantes europeus desde a segunda metade do século XIX, e em São Paulo.
                          Em Curitiba, em 1895, já existia um clube de ciclistas... 
                          
                        </p>


                        <br>
                         <a class="btn btn-primary btn-lg" target="blanck" href="https://pt.wikipedia.org/wiki/Bicicleta">Leia mais</a>
                      </div>
                    </li>
                  </ul>  
                </div>               
              </div>              
          </article>

           <!--botão sobe para o topo--> 
           <a class="btn btn-light float-right" href="index.html">
           <i class="fas fa-angle-up"></i>
         </a>
           <!--rodapé-->
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-md-2">
        	<a href="index.html"><img src="img/bkfooter2.png" width="70" class="ml-1 mt-3 bike2"></a>
         </div>
          <div class="col-2 col-sm-2 col-md-2">
            <h4>COMPANY</h4>
            <ul class="navbar-nav">
              <li><a href="">Sobre</a></li>
              <li><a href="">Empregos</a></li>
              <li><a href="">Imprensa</a></li>
              <li><a href="">Novidades</a></li>
            </ul>
          </div>
          <div class="col-md-2">
           <h4>COMUNIDADES</h4>
           <ul class="navbar-nav">
              <li><a href="">Artistas</a></li>
              <li><a href="">desenvolvedores</a></li>
              <li><a href="">marcas</a></li>
            </ul>
          </div>
          <div class="col-md-2">
           <h4>LINKS UTEIS</h4>
           <ul class="navbar-nav">
              <li><a href="">Ajuda</a></li>
              <li><a href="">Presentes</a></li>
              <li><a href="">player da web</a></li>
            </ul>
          </div>
          <div class="col-md-4">
            <ul>
              <li>
                <a href=""><img src="img/facebook.png"></a>
              </li>
              <li>
                <a href=""><img src="img/twitter.png"></a>
              </li>
              <li>
                <a href=""><img src="img/instagram.png"></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
      
  </footer>
   </div><!--fim container-->


<!-- JavaScript (Opcional) -->
    <!-- jQuery primeiro, depois Popper.js, depois Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

  </body>
</html>

