<!DOCTYPE html>

<HTML>
<head>
  <title> Formulário </title>
</head>

<body>
 <form action="/pagina-processa-dados-do-form" mothod="post">
  <fieldset>
	<legend> Dados Gerais </legend>
	<label for="nome">Nome:</label>
	<input type="text" minlength="3" id="nome"/>
	<label for="data_de_nascimento"> Data de nascimento: </label>
	<input type="text" id="data_de_nascimento"/>	
	<label for="CPF"> CPF: </label>
	<input type="text" minlength="11" id="cpf"/>

 </fieldset>
 
 <fieldset>
	<legend> Endereço </legend>
	<label for="tipo_endereço"> Tipo </label>
	<select id="tipo_endereço">
		<option value="">Selecione</option>
		<option value="">Rua</option>
		<option value="">Estrada</option>
		<option value="">Rodovia</option>
		<option value="">Outros </option>
	</select>
	<label for="logradouro_endereço"> Logradouro: </label>
	<input type="text" id="logradouro_endereço"/>
	<label for="numero_endereço"> Endereço: </label>
	<input type="text" id="numero_endereço" />
	<label for="complemento_endereço"> Endereço: </label>
	<input type="text" id="complemento_endereço" />
	
</fieldset>

<fieldset>
	<legend> Fale Conosco </legend>
	<label for="msg"> Mensagem </label>
	<textarea type="text" id="msg"></textarea>
	
</fieldset>

<fieldset>
	<button type="submit"> Enviar sua mensagem </button>
	<button type="reset"> Limpa o Formulário </button>

</fieldset>
</form>
</body>
</HTML>
