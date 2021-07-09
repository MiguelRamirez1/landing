# landing
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="media/icono.jpg">
    <link rel="stylesheet" href="css/estilo.css">
    <title>HEROMI</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>
<body>
    <div class="w3-col 1 m12" id="left">
    <section class="texIzq">
        <h1>*FORMULARIO DE EMPRESA HEROMI*</h1>
        <h3>Registrese para saber los precios de los muebles
            a la venta, entrada semanalmente en su bandeja.
        </h3>
        <h4><strong>Si tiene preguntas llame al 477 520 2670</strong></h4>
    </section>
    </div>

    
    <div class="contariner-fluid">
        <div class="row">
            <div class="col-sm-6">

            </div>
            <div class="col-sm-6 ">
                <div class="p-5">
                    <h5 class="tex">Obtenga alertas de los productos de forma <b>GRATUITA</b></h5>
                    <P id="camp">Campos requeridos*</P>
                    <form action="datos_formulario.php" method="POST">
                        <input class="form-control" type="text" name="nombre" placeholder="NOMBRE*" required/>
                        <br><input class="form-control" type="email" name="correo" placeholder="CORREO ELECTRÓNICO*" required/>
                        <br><input class="form-control" type="tel" name="telefono" placeholder="TELÉFONO*" required/>
                        <br><input class="form-control" type="text" name="comentario" placeholder="COMENTARIOS O DUDAS"/>
                        <br><button class="btn btn-primary" id="boton" type="submit">REGISTRARSE</button>
                    </form>
                    <p>¿Ya te haz registrado? <a href="#">Pagina Principal</a></p>
                    <p>Al hacer clic en "Registrarse", acepta todos los Términos de uso y la Declaración de
                        privacidad del sitio web de HEROMI <br> Recibirá actualizaciones de productos y promociones de HEROMI. <br>
                        Optenga más información sobre cómo podemos comunicarmos con usted mediante sus comentarios.
                    </p>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

</body>
</html>
