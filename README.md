
💸 Controle de Finanças

Aplicação web para controle de finanças pessoais, permitindo o cadastro, exibição e busca de transações financeiras. O objetivo é proporcionar uma interface simples e funcional para gerenciar entradas e saídas de dinheiro.




🚀 Funcionalidades: 


Cadastro de Transações: Registre entradas e saídas de dinheiro com descrição, valor e categoria.

Exibição de Transações: Veja todas as transações registradas em uma tabela com filtro de busca.

Resumo Financeiro: Veja um resumo das entradas, saídas e o saldo total de todas as transações.

Busca de Transações: Busque transações específicas por descrição ou categoria.

Modal de Cadastro: Interface intuitiva para adicionar novas transações.





🧰 Tecnologias Utilizadas:



React: Biblioteca JavaScript para construção da interface.

TypeScript: Tipagem estática para maior segurança no desenvolvimento.

Styled Components: Estilização de componentes usando CSS-in-JS.

Context API: Gerenciamento global de estado para as transações.

React Hook Form: Gerenciamento de formulários de forma simples e eficiente.

Zod: Validação de dados no lado do cliente.

Axios: Comunicação com a API para persistência de dados.

Phosphor-React: Ícones para uma interface mais interativa.

Radix UI: Componente de modal acessível para cadastro de novas transações.

📦 Como Rodar o Projeto Localmente:

Clone o repositório: 

git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

Para utiilizar o banco de dados JSON SERVER, utilizar :
npx json-server server.json


Instale as dependências:
npm install

Inicie o servidor de desenvolvimento:
npm start

🎨 Como Funciona:

A aplicação consiste em duas principais seções:

Cadastro de Transações: Utilize o modal para cadastrar uma nova transação (entrada ou saída). Cada transação possui uma descrição, categoria, valor e tipo.

Visualização das Transações: As transações são listadas em uma tabela, onde é possível visualizar as descrições, valores, categorias e datas das transações.

Resumo Financeiro: Um resumo exibe os totais de entradas, saídas e o saldo atual.





🌱 Aprendizados:




Context API: Utilizada para gerenciar o estado global das transações de forma eficiente.

Formulários com React Hook Form: Facilitou a criação de formulários controlados com validação simples.

Styled Components: Permitiu criar estilos reutilizáveis e de fácil manutenção.

Zod: Utilizado para validação de dados no formulário de uma maneira intuitiva e concisa.

![controllfinance](https://github.com/user-attachments/assets/8e94b360-c004-499f-99a2-604cef2a4439)
