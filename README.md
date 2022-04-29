# PHP-intro
<!DOCTYPE html>
<html>
  <head>
    <title>Hello World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <p>Formulario para inscricao</p>
        <form action="index.php" method="POST">
          <p>Seu nome: <input type="text" name="nome"/></p>
          <p>Idade: <input type="text" name="idade"></p>
          <input type="submit" value="Enviar">
          <input type="reset" value="Resetar">
        </form>
  </body>
</html>
<?php
    $nome = $_POST["nome"];
    $idade = $_POST["idade"];
    var_dump ($nome);
    var_dump($idade);
?>
