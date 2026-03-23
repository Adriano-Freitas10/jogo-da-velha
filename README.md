<!DOCTYPE html>
 <html>

 <head>

 <title> Estruturas de condições </title>
 <meta charset="UTF8">


 <script type="text/javascript" src="js/jogodavelha.js"></script>

 


 </head>
 <body onload="iniciar()"></body>

    <div id="board"></div><br>

    linha: <input type="number" min="1" max="3" id="linha"><br>
    coluna: <input type="number" min="1" max="3" id="coluna"><br>

    <button onclick="jogar()"></button><br><br>

    <div id="aviso">Vez do jogador: 1</div>

 </body>
 </html>
