# SkynetEvolution
Criação de site para mostrar meu trabalho com html css e Java. 
<!DOCTYPE html>
<html>

<head>
  <title>Formulário de Cadastro de Empresas</title>
  <link rel="stylesheet" href="styles.css">
  <script src="script.js"></script>
</head>

<body>

  <form action="processa.php" method="POST">
    <fieldset>
      <legend>Dados da empresa</legend>
      <div class="form-group">
        <label for="nome">Nome </label>
        <input type="text" id="nome" name="nome" required>
      </div>
      <div class="form-group">
        <label for="data">Data de criação da empresa (dd/mm/aaaa):</label>
        <input type="date" id="data" name="data" required>
      </div>
      <div class="form-group">
        <label for="cnpj">CNPJ:</label>
        <input type="NUMBER" id="cnpj" name="cnpj" required>
      </div>
      <div class="form-group">
        <label for="representante">Representante legal:</label>
        <input type="text" id="representante" name="representante" required>
      </div>
      <div class="form-group">
        <label for="ramo">Ramo de atuação:</label>
        <input type="text" id="ramo" name="ramo" required>
      </div>
      <div class="form-group">
        <label for="tema">Tema de negócio: </label>

        <select id="tema" name="tema">
          <option value="alimentacao">Alimentação</option />
  </form>

  <option value="educacao">Educação</option>
  <option value="saude">Saúde</option>
  <option value="tecnologia">Tecnologia</option>
  <option value="outro">Outro</option>
  </select>
  </div>
  <form>
    <option value="outro">Outro</option>
    <textarea name="mensagem"></textarea>

    <div id="outro-negocio" style="display: none;" class="form-group">
      <label for="outro-nome">Outras:</label>
      <input type="text" id="outro-nome" name="outro-nome">
    </div>

    <fieldset>
      <legend>Proposta de negócio</legend>
      <div class="form-group">

        <textarea id="proposta" name="proposta" rows="10" cols="50" required></textarea>
      </div>
      <div class="form-group">
        <label for="arquivo">Anexar um arquivo:</label>
        <input type="file" id="arquivo" name="arquivo">
        <span id="arquivo-info">Nenhum arquivo escolhido</span>
      </div>
    </fieldset>

    <fieldset>
      <legend>Contato para discussão da proposta</legend>
      <div class="form-group">
        <label for="contato-nome">Nome:</label>
        <input type="text" id="contato-nome" name="contato-nome" required>
      </div>
      <div class="form-group">
        <label for="contato-email">Email:</label>
        <input type="email" id="contato-email" name="contato-email" required>
      </div>
      <div class="form-group">
        <label for="contato-telefone">Telefone:</label>
        <input type="tel" id="contato-telefone" name="contato-telefone" required>
      </div>
    </fieldset>

    <button id="meuBotao">Enviar</button>

</body>

</html>
