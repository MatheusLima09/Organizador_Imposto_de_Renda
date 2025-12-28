# Organizador_Imposto_de_Renda
<p>
Esta ferramenta propõe auxiliar na organização da declaração de imposto de renda. Ela foi criada no Excel, possui um menu principal à esquerda das worksheets com botões, feitos com as própria células das worksheets, que permitem navegar pelas três páginas principais (três worksheets principais): TITULAR, INFORMES, NOTAS. 
</p>

<h2>TITULAR</h2>

<p>
A página TITULAR é aonde o usuário irá informar seus dados pessoais: Nome, CPF, data de nascimento, título de eleitor, cônjugue, endereço (rua, rua abreviada e CEP), telefone, celular, e-mail, alteração da entrega anterior, dependente cônjugue e residente do exterior, os três últimos dados possuem uma caixa de opções para preencher com SIM ou NÃO. Para avançar para a próxima página, a "INFORMES", basta clicar no botão escrito "PRÓXIMO ->" logo abaixo da tabela ou no botão escrito "INFORMES" no menu à esquerda.  
</p>

<h2>INFORMES</h2>

<p>
Na página INFORMES, o usuário poderá selecionar três bancos do qual ele possa possuir uma conta, cada tabela possui três campos: BANCO - para selecionar, com uma caixa de opções de bancos selecionados, o banco que ele usa; VALOR ATUAL - preencher com o saldo bancário atual na conta; ANEXO - para escrever o nome de um documento pdf a anexar. Acima das tabelas dos bancos, a uma linha para calcular o valor total do saldo bancário dos três bancos, para isso foi utilizado a fórmula SOMA() do Excel.<br>
Para avançar para a próxima página, a "NOTAS", basta clicar no botão escrito "PRÓXIMO ->" logo abaixo da tabela ou no botão escrito "NOTAS" no menu à esquerda, para retornar à página "TITULAR", basta clicar no botão escrito "<- ANTERIOR", também abaixo da tabela, logo ao lado do botão "PRÓXIMO ->" ou no botão escrito "TITULAR" no menu à esquerda.
</p>

<h2>NOTAS</h2>

<p>
A página NOTAS serve para o usuário digitar a entrada de receita mensal. As informações serão inseridas na tabela de registros "ENTRADAS", criada com o auxílio da função Inserir -> Tabela do Excel, preenchendo os campos de DATA, CATEGORIA E VALOR.
<br>O campo de DATA será preenchido com o mês e o ano da entrada de receita. O campo de CATEGORIA será preenchido selecionando os valores preestabelecidos na caixa de seleção (HOLERITE, CNPJ e FREELANCE). NO campo VALOR, o usuário digitará o valor gerado de receita no mês por essa atividade.
<br>Caso seja necessário retornar à página anterior, o usuário pode clicar no botão escrito "<- ANTERIOR" logo acima da tabela "ENTRADAS" ou no botão "INFORMES" no menu à esquerda, ou então, no botão "TITULAR" caso deseje voltar à pagina inicial.
</p>

<h2>Informações Importantes</h2>
<p>
-Este projeto foi feito no Excel online, portanto, a formatação pode estar ligeiramente diferente do esperado no aplicativo do Excel. Para isso, confira as prints das worksheets e de outras imagens utilizadas na pasta /imagens
<br>-Quaisquer dados, infomações, ou registros das pessoas utilizados de exemplo no projeto são FICTÍCIOS.
<br>-A worksheet "TABELAS" possui uma tabela de apoio com todos os bancos selecionados para criar as caixas de seleção de bancos da página "INFORMES". Essa worksheet não faz parte das telas principais do aplicativo.
</p>
