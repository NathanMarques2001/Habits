# Habits

Este é um aplicativo para controlar seus hábitos diários, permitindo adicionar, concluir, editar e excluir hábitos. O progresso do seu dia é visualizado através de pequenos quadrados que ficam cada vez mais fortes à medida que você conclui seus hábitos, assim como os commits do Github.

> ## Tecnologias usadas

- Typescript
- ReactJS para Web
- React Native para Mobile
- Prisma para o banco de dados
- NodeJS para o back-end

> ## Funcionalidades

- Adicionar hábitos
- Concluir hábitos
- Editar hábitos
- Excluir hábitos
- Ver o progresso dos hábitos de cada dia

> ## Instalação
Para instalar e executar a aplicação, siga os seguintes passos:

1. Clone este repositório para sua máquina local
```
git clone https://github.com/NathanMarques2001/Habits.git
```

2. Acesse a pasta do aplicativo
```
cd habits
```

3. Instale as dependências
```
npm install
```

> ## Servidor

Para iniciar o servidor, você precisa seguir os seguintes passos:

1. Acesse a pasta do servidor
```
cd Server
```

2. Inicie o servidor
```
npm start
```

> ## Rotas

Após o servidor estar rodando, você pode acessar as seguintes rotas:

- `/habits` - POST - Essa rota é utilizada para criar um novo hábito.
- `/day` - GET - Essa rota é utilizada para obter a lista de hábitos possíveis para um dia especificado na requisição.

- `/summary` - GET - Essa rota é utilizada para obter um resumo geral dos hábitos realizados e possíveis para cada dia.

- `/habits/:id/toggle` - PATCH - Essa rota é utilizada para alternar o estado de um hábito realizado ou não realizado.

> ## Contato
nathanbrandao1@gmail.com
