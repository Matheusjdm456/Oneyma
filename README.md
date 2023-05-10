<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" />
    <title>Grid</title>


    <style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;800&display=swap');


p{
    font-size: 20px;
    color: #affc41;
    top: 450px;
}
    body{
    font-family: 'Inter', sans-serif;
    box-sizing: border-box;
    background-color: #031B29;
    margin: 0px;
    padding: 0px;
} 

.container{
    display: grid;
    grid-template-columns: auto auto;
}


.box1{
   background-color: rgb(0, 0, 0) ; 
   color: #affc41;
   border:5px solid #0E1BAA;
   border-radius: 5px;
   text-align: center;
   width: 700px;
   height: 500px;
  
}


.new-container{
    display: grid;
    grid-template-columns: auto auto; 
}

.Lobo{
   background-color: rgb(0, 0, 0) ; 
   color: #affc41;
   border:5px solid #0E1BAA;
   border-radius: 5px;
   text-align: center;
   width: 400px;
   height: 500px;
}


.box3{
    background-color: rgb(0, 0, 0) ; 
   color: #affc41;
   border:5px solid #0E1BAA;
   border-radius: 5px;
   text-align: center;
   width: 400px;
   height: 500px; 
}

hr {
  display: block;
  margin-top: 1.5em;
  margin-bottom: 1.5em;
  margin-left: auto;
  margin-right: auto;
  border-style: inset;
  border-width: 10px;
}

h1{
    color: #affc41;
}

h3{
    color: #affc41;
}

.header{
    list-style: none;
}

a{
    color: #affc41;
}


    </style>
</head>
<body>

    <header class="header">
        <a href="https://www.youtube.com/watch?v=HL30U8PM66c">Masqueico.com</a><br>
        <br><a href="https://deadshot.io/">.IO</a>
        <nav>
        </nav>
    </header>
    <h1>Lendas</h1>
    <h3>Welcome to the Mato.</h3>
    <hr>
    <div class="container">
  <div class="box1">
       <P>Ney 10<br>
        <br>Neymar da Silva Santos Júnior é um futebolista brasileiro que atua como atacante. Atualmente joga pelo Paris Saint-Germain e pela Seleção Brasileira. É considerado o principal futebolista brasileiro da atualidade e um dos melhores futebolistas do mundo.<br>
        A boatos que dizem que ele bate em mulheres.
        <hr>
        <img src="ben.png">
  </div>  
 
  <div class="new-container">
    <div class="Lobo">
        <p>O Pidão</p>
        <br>O LOBISOMEM PIDÃO: Toda noite ele passa na praça pedindo farinha na cumbuca Pede pede pede que só a porra enche o saco esse bicho pidão.<br><br>
        <br>
        <hr>
        <img src="pidao.jpg">
    </div> 
    <div class="box3">
        <p>Bom de Guerra</p>
        <br>Não existe descrição para esse tipo de ser.<br><br><br><br><br>
        <hr>
        <img src="BDG.jpg">
    </div>
</div>
</div>
<div class="Thor">
   <p>Uma luta que você não pode vencer se torna uma obsessão. O verdadeiro guerreiro não precisa de espada. Riqueza demais traz infortúnio. É isso que significa entrar em guerra comigo.</p> 
  <p>Thorfinn.</p>
  <p>Escute bem Thorffin: Você não tem inimigos. Ninguém tem inimigos. Não existe ninguém que precise machucar.</p>
</div>
</div> 
</body>
</html>
