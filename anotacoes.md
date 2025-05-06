06/05 - ANALISE E PROJETO DE SISTEMAS (APS)
~> TEMA: Criação de uma arquitetura básica para sistemas pequenos

Projeto: Cadastro de clientes

Tipo de arquitetura: Monolítica

[Interface (Componentes Visuais)]
                ↓
[Lógica de Negócio (Funções/Estados)]
                ↓
[Acesso a Dados (LocalStorage, ou API locais/simulados)]
---
Interface: JSX visível ao usuário.
Lógica de Negócio: validções, manipulação, de dados, regras.
Acesso aos Dados: estados (useState()) ou comunicação com serviços/API.
---
Componentes:
FormularioCliente, ListaCliente, ListaClientes, App.
Lógica; evitar cadastro com campos vazios. Evistar emails duplicados
Armazenar dados temporariamente no estado.
