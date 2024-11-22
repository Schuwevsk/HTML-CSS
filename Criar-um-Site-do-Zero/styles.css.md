#CSS

body {
    background: rgb(71, 21, 252); /*   Cor de fundo */
    color: white; /* Cor do texto */
    background: rgb(71, 21, 252); /*   Cor de fundo */
    color: white; /* Cor do texto */
    margin-bottom: 50px;
}

header {
    background-color: #5ab9f0; /* Fundo branco para a mensagem */
    color: #eb14d9; /* Cor do texto */
    -webkit-text-stroke: 1px white; /* Contorno do texto */
    margin-top: 12px;   /* Posição do corpo topo */
    margin-left: 435px; /* Posição do corpo esquerda */
    margin-right: 435px; /* Posição do corpo direita */
    padding-top: 3px; /* Posição do corpo para cima */
    border-radius: 15px; /* Arredondar as arestas */
    box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3); /* Sombras no container */
    font-family: "Orbitron", serif;
    font-size: 14px;
    text-align: center;
}

.structure1 {
    display: block;
    width: 46%;  /* Define a largura do conteúdo */
    margin: 0 auto;  /* Centraliza horizontalmente */
}

.structure1 img {
    position: absolute; /* Posiciona a imagem de forma absoluta */
    top: 1626px;   /* Distância do topo */
    left: 1012px;  /* Distância da esquerda */
}

.chat-container1 {
    max-width: 800px; /* Largura máxima do contêiner */
    background-color: #a936d6; /* Cor de fundo */
    padding: 15px; /* Espaçamento interno */
    border-radius: 15px; /* Arredondar as arestas */
    box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3); /* Sombras no container */
}

.chat-container2 {
    max-width: 800px; /* Largura máxima do contêiner */
    background-color: #a936d6; /* Cor de fundo */
    padding: 15px; /* Espaçamento interno */
    border-radius: 15px; /* Arredondar as arestas */
    box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3); /* Sombras no container */
}

.menssage1 {
    font-size: 19px; /* Tamanho da fonte */
    line-height: 1.5; /* Espaçamento entre linhas */
    color: #ffffff; /* Cor do texto de introdução */
    text-shadow: 
        1px 1px 0px black, /* Contorno superior e à direita */
        -1px -1px 0px black, /* Contorno inferior e à esquerda */
        1px -1px 0px black, /* Contorno superior e à esquerda */
        -1px 1px 0px black; /* Contorno inferior e à direita */
}

.menssage2 {
    font-size: 19px; /* Tamanho da fonte */
    line-height: 1.5; /* Espaçamento entre linhas */
    color: #ffffff; /* Cor do texto de introdução */
    text-shadow: 
        1px 1px 0px black, /* Contorno superior e à direita */
        -1px -1px 0px black, /* Contorno inferior e à esquerda */
        1px -1px 0px black, /* Contorno superior e à esquerda */
        -1px 1px 0px black; /* Contorno inferior e à direita */
}

.structure2 {
    background-color: #6118c0; /* Cor de fundo */
    border-radius: 15px; /* Arredondar as arestas */
    box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.3); /* Sombras no container */
    margin-top: 50px;
    margin-left: 10px;
    margin-right: 10px;
    padding-left: 20px;
    padding-right: 20px;
    padding-bottom: 10px;
    justify-content: center;  /* Centraliza horizontalmente */
    align-items: center;  /* Centraliza verticalmente */
}

.structure2 h2 {
    font-size: 19px;
    color: #ffffff;
    text-align: center;
    font-family: "Orbitron", serif;
}

.videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
    border-radius: 14px;
}

.videos img {
    opacity: 0.5;
    height: 200px;
}

.videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}
