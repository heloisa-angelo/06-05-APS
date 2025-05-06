06/05 - ANALISE E PROJETO DE SISTEMAS (APS)
~> TEMA: Criação de uma arquitetura básica para sistemas pequenos

Projeto: Cadastro de clientes

Tipo de arquitetura: Monolítica

[Interface (Componentes Visuais)]
                ↓
[Lógica de Negócio (Funções/Estados)]
                ↓
[Acesso a Dados (LocalStorage, ou API locais/simulados)]
___
Interface: JSX visível ao usuário.
Lógica de Negócio: validções, manipulação, de dados, regras.
Acesso aos Dados: estados (useState()) ou comunicação com serviços/API.
___
Componentes:
FormularioCliente, ListaCliente, ListaClientes, App.
Lógica; evitar cadastro com campos vazios. Evistar emails duplicados
Armazenar dados temporariamente no estado.
___
Próximo passo: 
-Refatorar o código
-Correção de bugs
-Aplicar boas práticas
-Separar os componenntes por função (formulário, lista, item, etc)
-Criar funções reutilizáveis e separadas da interface
-Usar estado local (useState)para simular banco de dados amis específico
-Evitar colocar regras dentro do  JSX diretamente
-Comentar código quando necesário
___
