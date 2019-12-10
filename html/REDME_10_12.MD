<!DOCTYPE html>
<html lang="pt-br" class="h-100">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Restaurant</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.0/css/bootstrap.min.css" integrity="sha384-SI27wrMjH3ZZ89r4o+fGIJtnzkAnFs3E4qz9DIYioCQ5l9Rd/7UAa8DHcaL8jkWt" crossorigin="anonymous">
    <link rel="stylesheet" href="css/all.min.css">
    <style>
/* html, body, .container-fluid { height: 100%; } */
body { background: radial-gradient(black, white) no-repeat; }
.container-fluid { max-width: ; }
.navbar { font-size: 1.2rem; }
/* .carousel img, .row img { width: 100%; } */
.titulo { font-size: 2rem; }
h3,p1{color: whitesmoke;}
.navbar-brand{color: red;}
    </style>
</head>
<body class="h-100 " data-spy="scroll" data-target="navbar-nav" data-offset="50">
        
<a name="top" id="inicio"></a>

<!-- jumbotron-->
<div class="container-fluid bg-light h-100">
    &nbsp;
    <div class="jumbotron bg-light text-black mb-0 rounded-0 text-center">
        <h1> Venha conhecer nosso restaurante</h1>
       Variedade de pratos!
    </div>

    <!-- Menu de navegação (navbar) -->
    <nav class="navbar navbar-expand-lg bg-danger navbar-dark fixed-top">
        <!-- Brand -->
        <a class="navbar-brand text-light"><i class="fas fa-2x fa-utensils"></i></i></a>
        
        <!-- Toggler/collapsibe Button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
        </button>
        
        <!-- Navbar links -->
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#inicio"><i class="fas fa-home"></i> Início</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#Artigos"><i class=""></i> Pratos</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#Notícias"><i class='fas fa-chair' style='font-size:24px'></i> Reservas</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#Contatos"><i class="fas fa-envelope-open-text"></i> Contatos</a>
            </li>

            <!-- Dropdown -->
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown"><i class="fas fa-info-circle"></i> Sobre</a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="#"><i class="fas fa-code"></i> Sobre o site</a>
                    <a class="dropdown-item" href="#"><i class="fas fa-user-tie"></i> Sobre o autor</a>
                    <a class="dropdown-item" href="#"><i class="fas fa-user-lock"></i> Privacidade</a>
                </div>
            </li>
            </ul>

            <!-- Formulário de busca -->
            <form class="form-inline ml-auto" action="/action_page.php">
                <input class="form-control mr-sm-2" type="text" placeholder="Procurar...">
                <button class="btn btn-success" type="submit"><i class="fas fa-search"></i></button>
            </form>

        </div>
    </nav>

    <!-- Carroucel -->
    <div id="demo" class="carousel slide" data-ride="carousel">

            <!-- Indicators -->
            <ul class="carousel-indicators">
              <li data-target="#demo" data-slide-to="0" class="active"></li>
              <li data-target="#demo" data-slide-to="1"></li>
              <li data-target="#demo" data-slide-to="2"></li>
              <li data-target="#demo" data-slide-to="3"></li>
            </ul>
          
            <!-- The slideshow -->
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="img/ganso.png" alt="Los Angeles" class="w-100">
                <div class="carousel-caption">
                    <h3>Carne de ganso de 25 anos!!!</h3>
                    <p>Venha experimentar essa iguaria.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img src="img/prato2.png" alt="Chicago" class="w-100">
                <div class="carousel-caption">
                    <h4>Bife a cavalo</h4>
                    <p>Para quem gosta de simplicidade.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img src="img/prato332.png" alt="New York" class="w-100">
                <div class="carousel-caption">
                    <h3>Macarrão a bolonhesa especial</h3>
                    <p>Direto da Itália.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img src="img/prato4.png" alt="New York" class="w-100">
                <div class="carousel-caption">
                    <h3>Todos os tipos de lasanhas!</h3>
                    <p>Experimente cada variedade.</p>
                </div>
             </div>
            </div>
          
            <!-- Left and right controls -->
            <a class="carousel-control-prev" href="#demo" data-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </a>
            <a class="carousel-control-next" href="#demo" data-slide="next">
              <span class="carousel-control-next-icon"></span>
            </a>
          
        </div>

        
            <div class="col text-center">

                <div class="card text-black">
                    <div class="card-header"><h3>Nossas redes sociais</h3></div>
                    <div class="card-body text-black ">
                        <p>Conheça agente nas maiores redes sociais:</p>
                        
                            <a href="#face"><i class="fab fa-2x fa-facebook text-danger"></i></a>
                        
                            <a href="#face"><i class="fab fa-2x fa-youtube text-danger"></i></a>
                            <a href="#face"><i class="fab fa-2x fa-twitter text-danger"></i></a>
                            <a href="#face"><i class="fab fa-2x fa-github text-danger"></i></a>
                            <a href="#face"><i class="fab fa-2x fa-linkedin-in text-danger"></i></a>
                            <a href="#face"><i class="fab fa-2x fa-instagram text-danger"></i></a>
                        </ul>

                    </div>

                </div>

            </div>
        </div>

        <!-- footer -->
        <footer class="alert bg-danger text-light mt-5">
            <div class="text-center row">
                <div class="col-1"><a href="index.html"><i class="fas fa-2x fa-home text-light"></i></a></div>
                <div class="col">
                    &copy; Copyright 2019 Igor Rodrigues.
                    <small class="d-block">Todos os direitos reservados.</small>
                </div>
                <div class="col-1"><a href="#inicio"><i class="fas fa-2x fa-arrow-alt-circle-up text-light"></i></a></div>
            </div>
        </footer>

</div>


<!-- Modal do formulário de contatos -->
<div class="modal fade" id="enviado">
    <div class="modal-dialog">
        <div class="modal-content">
    
            <!-- Modal Header -->
            <div class="modal-header">
                <h4 class="modal-title">Olá!</h4>
                <button type="button" class="close" data-dismiss="modal">&times;</button>
            </div>
        
            <!-- Modal body -->
            <div class="modal-body">
                <p>Seu contato foi enviado para a equipe do <strong>Gatos de Rua</strong>.</p>
                <em>Obrigado...</em>
            </div>
        
            <!-- Modal footer -->
            <div class="modal-footer">
                <button type="button" class="btn btn-danger" data-dismiss="modal">Fechar</button>
            </div>
    
        </div>
    </div>
</div>
<!-- Fim do modal do formulário de contatos -->

<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.0/js/bootstrap.min.js" integrity="sha384-3qaqj0lc6sV/qpzrc1N5DC6i1VRn/HyX4qdPaiEFbn54VjQBEU341pvjz7Dv3n6P" crossorigin="anonymous"></script>
<script>

$(document).ready(function(){

    $(document).on('submit', '#formContato', function(){
        $("#enviado").modal();
        return false;
    });

});

</script>
</body>
</html>
