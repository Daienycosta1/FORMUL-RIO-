<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Formulário</title>
    </head>
        <body>
            <form action="/pagina-processa-dados-do-form" method="post">
                <fieldset>
                    <legend> Dados Gerais </legend>
                    <label for="nome">Nome:</label>
                    <input type="text" minlength="3" id="nome"/>
                    <label for="data_de_nascimento"> Data de nascimento: </label>
                    <input type="text" id="data_de_nascimento"/>
                    <label for="CPF"> CPF: </label>
                    <input type="text" minlength="11" id="cpf"/>
                </fieldset>
            </form>
        </body>
</html>
