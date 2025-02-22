# FSW-Donalds  

Projeto realizado durante a 7a Full Stack Week. Se consiste em uma página de **auto checkout para pedidos de fast food**, desenvolvido com um design **mobile-first** para melhor experiência em dispositivos móveis. O sistema permite criar pedidos, adicionar ao carrinho e finalizar compras utilizando um CPF. Os pedidos ficam armazenados e podem ser consultados ao informar o CPF do usuário. O status do pedido (**feito, processando, finalizado**) é gerenciado no banco de dados.

## Tecnologias Principais

O projeto foi desenvolvido com as seguintes tecnologias:  

- Next.js 
- Prisma ORM
- PostgreSQL
- React
- Tailwind
- Shadcn  
- Zod

## Banco de Dados  

O projeto utiliza **Prisma ORM** para gerenciar a persistência de dados. A ferramenta interage com o serviço do banco PostgreSQL hospedado na plataforma [Neon](https://neon.tech/).

![Image](https://github.com/user-attachments/assets/50a6aef2-873c-432d-b4a6-756bfe8f1461)

## Funcionalidades

- Criar pedidos e adicionar produtos ao carrinho
- Realizar pedidos pela interface, informando CPF
- Consultar histórico e status de pedidos pelo CPF

## Imagens

![Image](https://github.com/user-attachments/assets/8ecc4605-2075-4a8e-9fe7-43d952c3ff8d)

![Image](https://github.com/user-attachments/assets/74e50b7d-a11e-48d5-8e69-0f2f91911f70)

![Image](https://github.com/user-attachments/assets/797b857a-2633-4666-9273-0f28b053b397)

![Image](https://github.com/user-attachments/assets/f74c0406-b614-451a-873d-394d41f94c2c)

## Como Rodar o Projeto 

###  Clone o repositório
```sh
git clone --branch aula_5 --single-branch https://github.com/lucaslpdacosta/fsw-project.git
```

###  Crie um arquivo .env na raiz do projeto. Substitua "******" por valores reais:
```sh
DATABASE_URL=******
```

###  Instale as dependências:
```sh
npm install
```

###  Inicie o servidor com o script:
```sh
npm run dev
```

###  Acesse a URL:
```sh
http://localhost:3000/fsw-donalds
```

## Caso queira conferir a versão com deploy feito na Vercel:

- Escaneie o QR Code:

![Image](https://github.com/user-attachments/assets/75420611-72cc-4bd3-aa63-9113ae864ec8)

- Ou acesse este [Link](https://fsw-project.vercel.app/fsw-donalds).
