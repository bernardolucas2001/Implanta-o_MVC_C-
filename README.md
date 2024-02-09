Descrição da Atividade:
A clínica veterinária LH-Pet lhe solicitou que inicie o desenvolvimento de um projeto Web .NET com arquitetura MVC. Inicialmente a aplicação não terá banco de dados, as futuramente a empresa migrará toda a sua base de dados para o novo sistema.

Primeiramente, você deve iniciar a estruturação de uma aplicação web .NET com arquitetura MVC. Após essa fase, o sistema será adequado para persistência com banco de dados. Assim, você será o responsável por criar os dois primeiros models (Cliente e Fornecedor) do sistema, que se referem aos Clientes e Fornecedores da empresa.

Para complementar a implementação você deverá criar objetos do tipo Cliente e Fornecedor no controller (HomeController) criado pelo template de projeto da Microsoft e “popular” esses objetos com atributos. Ao final exiba as listas de Clientes e Fornecedores utilizando o template Index.cshtml desenvolvido pela equipe front-end da empresa.

Entendendo o MVC: é um padrão de arquitetura de software organizado em Camadas. Um dos principais objetivos é separar a interface das regras e do modelo de negócios. Cada camada assume responsabilidades no sistema A aplicação é dividida em três camadas principais:
Model - Responsável pela implementação (tipos, tamanhos, comportamentos etc.), acesso e manipulação da fonte de dados;
View - Responsável pela interface apresentada ao usuário;
Controller - É responsável pela lógica de negócios do sistema. É uma espécie de “maestro” do sistema.

![image](https://github.com/bernardolucas2001/Implanta-o_MVC_C-/assets/83489813/2077d8a0-fae4-458e-ab03-34ccc7d06182)
Figura 1 - Visão sistêmica


![image](https://github.com/bernardolucas2001/Implanta-o_MVC_C-/assets/83489813/5f8362d1-4537-495d-8257-10c4e5c7cd34)
Figura 2 - MVC acessando banco

