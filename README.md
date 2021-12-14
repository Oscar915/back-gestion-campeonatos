<!DOCTYPE html> 
<html lang="en"><!D
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <link rel="stylesheet" href="css/bootstrap-grid.min.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=devise-width">
    <meta name="robots" content="Diseño de paginas,uninorte">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campeonato de futbol </title>
    <link rel="stylesheet" href="CSS/estilos.CSS">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
    crossorigin="anonymous"></script>
    <meta
      name="description"
      content="Web site created using create-react-app"
    />
    <link rel="apple-touch-icon" href="%PUBLIC_URL%/logo192.png" />
    
    -->
    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
   
    
  </head>
  <body>
    
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    <script src="js/bootstrap.bundle.min.js"></script>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>

    
    <header>

        <img src="Imagenes/campeonato.jpg" width="250" height="200" alt=" flexbox2"> <br>
        <br>
        <br>
        <nav>
          <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="d-flex">
              <div class="dropdown me-1">
                <button type="button" class="btn btn-secondary dropdown-toggle" id="dropdownMenuOffset"
                  data-bs-toggle="dropdown" aria-expanded="false" data-bs-offset="10,20">
                  Inicio
                </button>
                <ul class="dropdown-menu" aria-labelledby="dropdownMenuOffset">
                  <li><a class="dropdown-item" href="Inicio.html">Inicio</a></li>
    
    
                </ul>
              </div>
              <div class="d-flex">
                <div class="dropdown me-1">
                  <button type="button" class="btn btn-secondary dropdown-toggle" id="dropdownMenuOffset"
                    data-bs-toggle="dropdown" aria-expanded="false" data-bs-offset="10,20">
                    Login
                  </button>
                  <ul class="dropdown-menu" aria-labelledby="dropdownMenuOffset">
                    <li><a class="dropdown-item" href="Login.html">Login</a></li>
                   
    
                  </ul>
                </div>
                <div class="btn-group">
                  <button type="button" class="btn btn-secondary">UsuarioInterno</button>
                  <button type="button" class="btn btn-secondary dropdown-toggle dropdown-toggle-split"
                    id="dropdownMenuReference" data-bs-toggle="dropdown" aria-expanded="false" data-bs-reference="parent">
                    <span class="visually-hidden">Toggle Dropdown</span>
                  </button>
                  <ul class="dropdown-menu" aria-labelledby="dropdownMenuReference">
                    <li><a class="dropdown-item" href="Usuariointerno.html">UsuarioInterno</a></li>
                    
    
                    <li>
                      <hr class="dropdown-divider">
                    </li>
    
                  </ul>
                </div>
                <div class="btn-group">
                  <button type="button" class="btn btn-secondary">UsuarioExterno</button>
                  <button type="button" class="btn btn-secondary dropdown-toggle dropdown-toggle-split"
                    id="dropdownMenuReference" data-bs-toggle="dropdown" aria-expanded="false" data-bs-reference="parent">
                    <span class="visually-hidden">Toggle Dropdown</span>
                  </button>
                  <ul class="dropdown-menu" aria-labelledby="dropdownMenuReference">
                    <li><a class="dropdown-item" href="Usuarioexterno.html">UsuarioExterno</a></li>
    
    
                    <li>
                      <hr class="dropdown-divider">
                    </li>
    
                  </ul>
                </div>
                <div class="btn-group">
                  <button type="button" class="btn btn-secondary">UsuarioAdministrativo</button>
                  <button type="button" class="btn btn-secondary dropdown-toggle dropdown-toggle-split"
                    id="dropdownMenuReference" data-bs-toggle="dropdown" aria-expanded="false" data-bs-reference="parent">
                    <span class="visually-hidden">Toggle Dropdown</span>
                  </button>
                  <ul class="dropdown-menu" aria-labelledby="dropdownMenuReference">
                    <li><a class="dropdown-item" href="Usuarioadministrativo.html">UsuarioAdministrativo</a></li>
                    
    
    
                    <li>
                      <hr class="dropdown-divider">
                    </li>
    
                  </ul>
                </div>
              </div>
          </nav>
        </nav>
    
      </header>
    
    
        <div class="contenedor">
          <div class="row">
            <aside class="col-4">
                
            
    
                
                
                
            </aside>
    
    
    
            <section class="col-8">
    
                <form name = "formulario Registro" onsubmit= "return validad();" method="post"> 


                    <img src="Imagenes/Usuario.jpg" width="200" height="180" alt=" Usuario1"> <label> Calendario  :</label>
                    <input type="datetime-local" id="enviar" name="enviar"> 
                    <br>
                    <br>
    
                    <h1>LOGIN</h1>
                    <br>
                    <p>
                      <label>    Correo :   </label>
                      <input type="text" id="1" name="campo1">
                    </p>
                    <p>
                      <label>     Confirmar correo:   </label>
                      <input type="text" id="2" name="campo2">
                    </p>
                
                    <p>
                      <label>    Contraseña:   </label>
                      <input type="password" id="3" name="campo3">
                    </p>
                
                    <p>
                      <label>   Confirmar contraseña:   </label>
                      <input type="password" id="4" name="campo4">
                    </p>
                
                    <p>
                      <label>     Nombre:   </label>
                      <input type="text" id="5" name="campo5">
                    </p>
                
                    <p>
                      <label>      Apellidos:    </label>
                      <input type="text" id="6" name="campo6">
                    </p>
                
                    <p>
                      <label>     Departamento:   </label>
                      <input type="text" id="7" name="campo7">
                    </p>
                
                    <p>
                      <label>      Ciudad:    </label>
                      <input type="text" id="8" name="campo8">
                    </p>
                
                    <p>
                      <label> Dirreccion:</label>
                      <input type="text" id="9" name="campo9">
                    </p>
                
                    <p>
                      <label>      Celular:    </label>
                      <input type="text" id="10" name="campo10">
                    </p>
                
                    <label>   Aceptar Terminos y Condiciones   </label>
                    <input type="checkbox" id="tv" name="tv">
                
                
                    <p>
                      <label>      Registrarse:    </label>
                      <input type="submit" id="enviar" name="enviar">
                    </p>
                
                
                
                
                
                </form>
        
  </body>
</html> 
