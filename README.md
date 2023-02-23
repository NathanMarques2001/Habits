# Habits

> ### Readme em construção...
Habits Tracker
Este é um aplicativo para controlar seus hábitos diários, permitindo adicionar, concluir, editar e excluir hábitos. O progresso do seu dia é visualizado através de pequenos quadrados que ficam cada vez mais fortes à medida que você conclui seus hábitos, assim como os commits do Github.

Tecnologias usadas
Typescript
ReactJS para Web
React Native para Mobile
Prisma para o banco de dados
NodeJS para o back-end

Funcionalidades
Adicionar hábitos
Concluir hábitos
Editar hábitos
Excluir hábitos
Ver o progresso dos hábitos de cada dia
Instalação
Para instalar e executar a aplicação, siga os seguintes passos:

Clone este repositório para sua máquina local
git clone https://github.com/NathanMarques2001/Habits.git
Acesse a pasta do aplicativo
cd habits-tracker
Instale as dependências
npm install
Execute a aplicação
npm start

Rotas
Para iniciar o servidor, você precisa seguir os seguintes passos:

Instale as dependências do projeto, executando o comando npm install na pasta do projeto.
Execute o comando npm start para iniciar o servidor.
Após o servidor estar rodando, você pode acessar as seguintes rotas:
POST /habits: Essa rota é utilizada para criar um novo hábito. O corpo da requisição deve conter o título do hábito e os dias da semana em que ele deve ser realizado.
GET /day: Essa rota é utilizada para obter a lista de hábitos possíveis para o dia especificado na requisição. Ela também retorna uma lista de hábitos já realizados no dia.
PATCH /habits/:id/toggle: Essa rota é utilizada para alternar o estado de um hábito realizado ou não realizado. Ela recebe o ID do hábito como parâmetro na URL.
GET /summary: Essa rota é utilizada para obter um resumo geral dos hábitos realizados e possíveis para cada dia.

Contato
nathanbrandao1@gmail.com
