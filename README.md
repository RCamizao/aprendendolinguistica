<!DOCTYPE html>
<html lang="en">
<tittle>Início</tittle>

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
</head>

<!-- corpo da Homem Page-->
<body>
<link rel="stylesheet" href="style-home.css">
<script src="home.js"></script>

<!-- Cria o Menu -->
<div class="tab">
    <button class="tablinks" onclick="openTab(event, 'first')" id="defaultOpen">Elementos da Linguística</button>
    <button class="tablinks" onclick="openTab(event, 'second')" id="defaultOpen">Introdução aos Estudos Literários</button>
    <button class="tablinks" onclick="openTab(event, 'third')" id="defaultOpen">Poética</button>
    <button class="tablinks" onclick="openTab(event, 'third')" id="defaultOpen">Programação</button>
  </div>
  
  <!-- Conteúdo da Primeira Aba -->
  <div id="first" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times</span>
    <h5>First Tab</h5>
    <p>Conteúdo da primeira aba...</p>
  </div>
  
  <!-- Conteúdo da Segunda Aba -->
  <div id="second" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times</span>
    <h6>Second Tab</h6>
    <p>Conteúdo da segunda aba...</p> 
  </div>
  
  <!-- Conteúdo da Terceira Aba -->
  <div id="third" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times</span>
    <h3>Third Tab</h3>
    <p>Conteúdo da terceira aba...</p>
  </div>

<div id="conteudo">
 </div>

 <div id="menu">
   <ul>
     <li><a href="link1.htm">Elementos da Linguística</a></li>
     <li><a href="link2.htm">Introdução aos Estudos Literários</a></li>
     <li><a href="link3.htm">Estudos da Língua Portuguesa</a></li>
     <li><a href="link4.htm">Poética</a></li>
     <li><a href="link5.htm">Programação</a></li>
   </ul>
 </div>

<h1>Estudos do Português e outras linguagens</h1>
<div class="primeiro-bloco"><p class="container1" class="has-text-align-left">A ideia desse post é explorar conceitos presentes no texto "A Comunicação Humana", de <a href="https://pt.wikipedia.org/wiki/Diana_Luz_Pessoa_de_Barros" target="_blank"> Diana Luz Pessoa de Barros</a>(WIKIPÉDIA), publicado na antologia <em>"<a href="https://edisciplinas.usp.br/pluginfile.php/2550517/mod_label/intro/NEGR%C3%83O_EstruturaDaSentenca.pdf">Introdução à Linguística I</a>"</em>, São Paulo, 2012, pela editora Contexto; e utilizado como bibliografia na disciplina Elementos de Linguística I na Faculdade de Filosofia, Letras e Ciências Humanas da Universidade de São Paulo.</p>
    <p><em>"Ao ouvir de professores universitários portugueses, em um congresso na Espanha, que tinham feito a viagem de Portugal à Espanha de caminhonete, um brasileiro surpreendeu-se muito, até saber que, naquele subcódigo, caminhonete é o mesmo que ônibus.</em>"</p>
    </div>
   
<h2 class="segundo-bloco">A Língua como Instrumento de Comunicação</h2>
<p class="segundo-bloco">Se você não sabe quem foi Ferdinand de Saussure, não tem problema: segundo o site <a href="https://www.ebiografia.com/ferdinand_de_saussure/" target="_blank
    ">ebiografia.com</a>, Saussure (1857-1913) foi um linguista suíço e é considerado um fundador da linguística como ciência moderna. Ok, mas qual o contexto?</p>

</body>
</html>

