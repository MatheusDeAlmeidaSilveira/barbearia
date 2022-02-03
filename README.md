# barbearia
página de barbearia
#_______________________
<h1> Barbearia </h1>
<img src="https://media.discordapp.net/attachments/938820170871361576/938820315482566706/barbearia200.jpg"></img>
<h2> Sobre a Barbearia </h2>
   <p>Localiza na cidade X, a <strong>Barbearia</strong> traz para o mercado, boa qualidade para o seu cabelo e barba. Fundada em XXXX, a Barbearia conquista novos clientes a cada dia.</p> 
   <p id="missao"> <em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>
   <p>Oferecemos profissionais experientes e atentos às mudanças no mundo da moda.</p>
   <h3 class="titulo-centralizado">Benefícios</h3>
      <ul>
        <li class="itens">Atendimento aos Clientes</li>
        <li class="itens">Espaço diferenciado</li>
        <li class="itens">Qualidade</li>
        <li class="itens">Profissionais Qualificados</li> 
      </ul>
<img src="https://media.discordapp.net/attachments/938820170871361576/938820315763605534/barber300.jpeg" class="imagembeneficios">

#_________código abaixo______________
XXXXX
XXXXX
XXXXX
XXXXX
XXXXX

#________HTML_________

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <tittle></tittle> 
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <h1 class="titulo-principal">Barbearia</h1>
    </header>
    <img id="banner" src="imagens/barbearia200.jpg" alt="Barbearia">
    <div class="principal">
        <h2 class="titulo-centralizado"> Sobre a Barbearia </h2>

        <p>Localiza na cidade X, a <strong>Barbearia</strong> traz para o mercado, boa qualidade para o seu cabelo e barba. Fundada em XXXX, a Barbearia conquista novos clientes a cada dia.</p>

        <p id="missao"> <em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

        <p>Oferecemos profissionais experientes e atentos às mudanças no mundo da moda.</p>
    </div>

    <div class="beneficios">
        <h3 class="titulo-centralizado">Benefícios</h3>

        <ul>
            <li class="itens">Atendimento aos Clientes</li>
            <li class="itens">Espaço diferenciado</li>
            <li class="itens">Qualidade</li>
            <li class="itens">Profissionais Qualificados</li>
        </ul>

        <img src="imagens/barber300.jpeg" alt="barber" class="imagembeneficios">
    </div>

</body>
</html>

#__________CSS____________

body {
    background-color: rgb(39, 38, 38);
    color: rgb(240, 240, 240);
}

#banner {
    width: 50%;
}

.principal {
    background-color: rgb(39, 38, 38);
    padding: 30px;
}

.titulo-principal {
    padding: 20px;
}

.titulo-centralizado {
    text-align: center;
}

p {
    text-align: center;
}

#missao {
    font-size: 20px;
}

em strong {
    color: darkviolet;
}

.itens {
    font-size: italic;
}


.beneficios {
    font-size: italic;
    padding: 20px;
}

h2 {
    text-align: center;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}

.imagembeneficios {
    width: 50%;
}
