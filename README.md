<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
  <title>Imobiliaria formulario</title>

  <!-- Bootstrap -->
  <link href="css/bootstrap.min.css" rel="stylesheet">

  <link rel="stylesheet" type="text/css" href="css/main.css">

  <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
  <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->
    </head>
    <body>
      <header>
        <div class="container-fluid">
          <h1>Formulario de pesquisa:</h1>
        </div>
      </header>
      <div class="main">
        <div class="container-fluid">
          <!-- Nav tabs -->
          <ul class="nav nav-tabs" role="tablist">
            <li role="presentation" class="active"><a href="#imVenda" aria-controls="imvVenda" role="tab" data-toggle="tab">Imóveis à venda</a></li>
            <li role="presentation"><a href="#imvAlugar" aria-controls="profile" role="tab" data-toggle="tab">Imóveis para Alugar</a></li>
            <li role="presentation"><a href="#lancamento" aria-controls="lancamento" role="tab" data-toggle="tab">Lançamento</a></li>
            <li role="presentation"><a href="#bCodigo" aria-controls="bCodigo" role="tab" data-toggle="tab">Buscar Código</a></li>
          </ul>

          <!-- Tab panes -->
          <div class="tab-content">
            <div role="tabpanel" class="tab-pane active" id="imVenda">
              <!-- coluna vendas -->
              <div class="coluna">
                <select class="form-control" name="tipImovel">
                  <option>Apartamentos</option>
                  <option>Área</option>
                  <option>Casa</option>
                  <option>Casa em Condominio</option>
                  <option>Coberturas</option>
                  <option>flat</option>
                  <option>Galpão</option>
                  <option>Loja</option>
                  <option>Predio Comercial</option>
                  <option>Sala</option>
                  <option>Sitio</option>
                  <option>Terreno</option>

                </select>
              </div>
              <!-- end coluna vendas -->
              <!-- coluna vendas -->
              <div class="coluna">
                <select class="form-control" name="cidade">
                  <option>Aruja</option>
                  <option>Barueri</option>
                  <option>Cabo Frio</option>
                  <option>Cotia</option>
                  <option>Ilhabela</option>
                  <option>Jandira</option>
                  <option>Mairinque</option>
                  <option>Santana de Parnaiba</option>
                  <option>São Paulo</option>
                  <option>São Roque</option>                </select>
                </div>
                <!-- end coluna vendas -->
                <!-- coluna vendas -->
                <div class="coluna">
                  <select class="form-control" name="bairro">
                    <option>1</option>
                    <option>2</option>
                    <option>3</option>
                    <option>4</option>
                    <option>5</option>
                  </select>
                </div>
                <!-- end coluna vendas -->
                <!-- coluna vendas -->
                <div class="coluna">
                  <select class="form-control" name="dormitorio">
                    <option>1</option>
                    <option>2</option>
                    <option>3</option>
                    <option>4</option>
                    <option>5</option>
                  </select>
                </div>
                <!-- end coluna vendas -->
                <!-- coluna vendas -->
                <div class="coluna">
                  <select class="form-control" name="garagem">
                    <option>1</option>
                    <option>2</option>
                    <option>3</option>
                    <option>4</option>
                    <option>5</option>
                  </select>
                </div>
                <!-- end coluna vendas -->
                <!-- coluna vendas -->
                <div class="coluna">
                  <select class="form-control" name="valorVenda">
                    <option>1</option>
                    <option>2</option>
                    <option>3</option>
                    <option>4</option>
                    <option>5</option>
                  </select>
                </div>
                <!-- end coluna vendas -->
              </div>
              <div role="tabpanel" class="tab-pane" id="imvAlugar">...</div>
              <div role="tabpanel" class="tab-pane" id="lancamento">...</div>
              <div role="tabpanel" class="tab-pane" id="bCodigo">...</div>
            </div>
          </div>  
        </div>


        <!-- inicio do formulario de pesquisa -->
        




        <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <!-- Include all compiled plugins (below), or include individual files as needed -->
        <script src="js/bootstrap.min.js"></script>
        <script type="text/javascript">
         $('#myTabs a').click(function (e) {
          e.preventDefault()
          $(this).tab('show')
        })

        $('#myTabs a[href="#imvAlugar"]').tab('show') // Select tab by name
        $('#myTabs a:first').tab('show') // Select first tab
        $('#myTabs a:last').tab('show') // Select last tab
        $('#myTabs li:eq(2) a').tab('show') // Select third tab (0-indexed)
      </script>    

    </body>
    </html>
