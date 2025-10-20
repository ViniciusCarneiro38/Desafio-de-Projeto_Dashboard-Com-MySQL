## Readme – Desafio de Projeto - Criando um Dashboard corporativo com integração com MySQL e Azure ## 

Não foi possível usar a Azure, mesmo com a tentativa de 3 contas diferentes. Desta forma, fiz a inserção em SGBD MySQL e inseri os dados da base informada. A partir daí, foi feita a importação para o PowerBI. 

Da Análise de Dados e alterações:

1)	Em Dept_Locations foi inserido o nome de quem é a pessoa responsável;
2)	Em Employee, foi colocada a coluna com o nome completo da pessoa, separação do Estado do endereço completo, salary ajustado para número decimal fixo ($) – o único nulo (não retirado) é o gerente acima de todos os funcionários;
3)	Criada a tabela EmployeeWorksWhere para mostrar o local onde o funcionário trabalha;
4)	Criada a tabela EmployeeAndMgr para mostrar quais pessoas estão subordinadas a quem;
5)	Criação da tabela DeptAndLocation para mesclar nome e localização do departamento; Utilizada a mescla, pois existiria erro em atribuir Headquarters e Research para Houston, uma vez que também há Research em duas outras localidades;
6)	Análise da tabela WorksOn, onde foi inserida a coluna com o nome da pessoa e projeto, além da análise de pessoas sobrecarregadas e subutilizadas;
7)	Verificação de Erros após remoção de colunas não utilizadas ou sem relações;
