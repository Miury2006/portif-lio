<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio</title>
</head>
<body>

  <header>
    <h1>Portfólio</h1>
    <figure>
      <img src="Matheus.png" width="200" alt="Foto de Matheus" />
      <figcaption><strong>Matheus Iury Bezerra Abreu</strong></figcaption>
    </figure>
  </header>

  <main>
    <section>
      <h2>Sobre Mim</h2>
      <p>Me chamo Matheus Iury Bezerra Abreu. Tenho 18 anos e sou apaixonado por tecnologia. Estou sempre em busca de aprendizado, evolução e novas descobertas nessa área.</p>
      <p>Meu objetivo é construir uma carreira sólida em tecnologia, mantendo um equilíbrio saudável entre trabalho e vida pessoal.</p>
    </section>
    <section>
      <h2>Experiência</h2>
      <ul>
        <li>Inglês intermediário (em formação)</li>
        <li>Ensino Médio completo</li>
        <li>Conhecimento em Informática Básica</li>
        <li>Graduando em Ciência da Computação</li>
      </ul>
    </section>
    <section>
      <h2>Qualidades</h2>
      <ul>
        <li>Organizado</li>
        <li>Aprendizado rápido</li>
        <li>Colaborativo</li>
        <li>Dedicado</li>
      </ul>
    </section>
    <section>
      <h2>Preferências Pessoais</h2>
      <h3>Gosto de:</h3>
      <ul>
        <li>Sushi</li>
        <li>Jogos</li>
        <li>Dormir</li>
        <li>Viajar</li>
      </ul>
      <h3>Não gosto de:</h3>
      <ul>
        <li>Sons de algo raspando</li>
        <li>Cheiros fortes</li>
        <li>Barulhos muito altos</li>
        <li>Comidas azedas</li>
      </ul>
    </section>
    <section>
      <h2>Contato</h2>
      <form action="#" method="post">
        <label for="nome">Nome:</label><br />
        <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required /><br /><br />
        <label for="email">E-mail:</label><br />
        <input type="email" id="email" name="email" placeholder="exemplo@email.com" required /><br /><br />
        <label for="idade">Idade:</label><br />
        <input type="number" id="idade" name="idade" min="10" max="100" /><br /><br />
        <fieldset>
          <legend>Interesse:</legend>
          <input type="radio" id="site" name="interesse" value="site" />
          <label for="site">Site</label><br />
          <input type="radio" id="mentoria" name="interesse" value="mentoria" />
          <label for="mentoria">Mentoria</label>
        </fieldset><br />
        <input type="submit" value="Enviar" />
      </form>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Matheus Iury. Todos os direitos reservados.</p>
    <p>Contato direto: <strong>miury4529@gmail.com</strong></p>
  </footer>

</body>
</html>
