#Robo criado para realizar o teste da Spread Tecnologia 
Etapas do robô:

Para cada registro da coluna “CPF” efetuar os tratamentos:

•	Acessar o site no link https://validadordecpf.clevert.com.br/v-cpf.php;

•	Informar o CPF e verificar o seu retorno, caso seja falso excluir a linha do registro;

•	Excluir a linha de CPFs duplicados entre os registros

Para cada registro da coluna “Codigo_Produto” efetuar os tratamentos:

•	Validar que os códigos estão dentro do intervalo (50 a 650);

•	Excluir todas as linhas dos registros divergentes da regra acima;

Para cada registro da coluna “Quantidade” efetuar os tratamentos:

•	Remover os espaços em branco para todos os registros;

•	Validar se o valor é ímpar;

•	Excluir a linha do registro com quantidade ímpar;

Efetuar os tratamentos finais com os dados acima:

•	Classificar a coluna “Nome” em ordem alfabética ascendente;

•	Criar um arquivo CSV com todos os dados tratados;

•	 O nome do arquivo deve conter o seguinte padrão: “Dados_Tratados.csv”;

