<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio</title>
</head>
<body>

  <header>
    <h1>Portfólio</h1>
    <img src="Matheus.png" width="170" alt="Foto de Matheus" />
  </header>

  <main>
    <section>
      <h2>Sobre mim:</h2>
      <p>Me chamo Matheus Iury Bezerra Abreu. Sou um jovem de 18 anos que busca aprender, melhorar e saber mais sobre a área de tecnologia.</p>
      <p>Quero criar um futuro para mim na área de tecnologia e encontrar uma maneira de ter uma vida equilibrada entre o tempo livre e o trabalho.</p>
    </section>

    <section>
      <h2>Minha experiência</h2>
      <ul>
        <li>Inglês Intermediário em formação</li>
        <li>Ensino Médio Completo</li>
        <li>Informática Básica</li>
        <li>Faculdade de Ciência da Computação em formação</li>
      </ul>
    </section>

    <section>
      <h2>Minhas Qualidades</h2>
      <ol>
        <li>Organizado</li>
        <li>Facilidade de aprender</li>
        <li>Cooperativo</li>
        <li>Dedicado</li>
      </ol>
    </section>

    <section>
      <h2>Assuntos Pessoais</h2>
      <ol>
        <li>Coisas que eu gosto:
          <ul>
            <li>Sushi</li>
            <li>Jogos</li>
            <li>Viajar</li>
          </ul>
        </li>
        <li>Coisas que eu não gosto:
          <ul>
            <li>Sons de algo raspando</li>
            <li>Cheiros fortes</li>
            <li>Comidas azedas</li>
          </ul>
        </li>
      </ol>
    </section>

    <section>
      <h2>Entre em Contato</h2>
      <form action="#" method="post">
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome" placeholder="Digite seu nome"><br><br>
      
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" placeholder="exemplo@email.com"><br><br>
      
        <label for="idade">Idade:</label><br>
        <input type="number" id="idade" name="idade" min="10" max="100"><br><br>
      
        <label>Interesse:</label><br>
        <input type="radio" id="site" name="interesse" value="site">
        <label for="site">Site</label><br><br>
        <input type="radio" id="mentoria" name="interesse" value="mentoria">
        <label for="mentoria">Mentoria</label><br><br>
      
        <input type="submit" value="Enviar">
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Matheus Iury. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
