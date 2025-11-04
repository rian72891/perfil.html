<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Perfil</title>

  <style>
    /* Seletor por tag */
    body {
      /* Alterado para um azul claro (Atividade 1) */
      background-color: #e0f7fa; 
      font-family: Arial, sans-serif;
    }

    /* Seletor por ID */
    #titulo {
      color: darkblue;
      text-align: center;
    }

    /* Seletor por classe */
    .destaque {
      color: #e67e22;
      font-weight: bold;
    }

    /* Seletor agrupado */
    h2, p {
      margin-left: 20px;
    }

    /* Seletor descendente */
    div ul li {
      color: #555;
    }

    /* Novo seletor de CSS para :hover (Atividade 5) */
    div ul li:hover {
      color: blue; /* Mudar a cor do texto para azul ao passar o mouse */
      cursor: pointer; /* Adiciona um cursor de ponteiro para indicar interatividade */
    }

    /* Estilo para o Desafio extra (Atividade 6) */
    #rodape {
      margin-top: 30px;
      padding: 10px;
      text-align: center;
      background-color: darkblue;
      color: white;
      font-size: 0.9em;
      border-top: 2px solid #e67e22;
    }
  </style>
</head>

<body>
  <h1 id="titulo">Meu Perfil</h1>

  <h2>Sobre Mim</h2>
  <p>Meu nome é <span class="destaque">Rian</span> e gosto de programar.</p>

  <h2>Meus Hobbies</h2>
  <div>
    <ul>
      <li>Ouvir música</li>
      <li>Programar</li>
      <li>Assistir filmes</li>
      <li>Jogar futebol</li>
      <li>Treina calistenia</li>      
    </ul>
  </div>

  <h2>Minhas metas</h2>
  <p class="destaque">Aprender a fundo <span class="destaque">Desenvolvimento Web Full Stack</span>.</p>
  <p class="destaque">Dominar a linguagem de programação <span class="destaque">Python</span> para análise de dados.</p>
  <p class="destaque">Criar e publicar meu primeiro <span class="destaque">aplicativo móvel</span>.</p>
  
  <div id="rodape">
    <p>&copy; 2025 - Perfil em Desenvolvimento. Desafio concluído! 💪</p>
  </div>
</body>
</html>
