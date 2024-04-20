## 💻 Api Daily Diet

Projeto backend em NodeJS, desenvolvido para uma API REST. Trata-se de uma api de um app de dieta e controle de refeições.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Veja **[clone](https://github.com/EngJao89/nodejs-api-rest-challenge.git)** para saber como clonar o repositório para sua máquina.

### 🔧 Instalação

Para rodar o projeto após clonar na sua máquina. Será necessário seguir as etapas a seguir.

Comece com seu empacotador padrão:

```
npm install
```

Ou utilize:

```
yarn install
```

Após instalar as dependencias suba o container do docker com PostgreSQL rode:

```
docker compose up
```

Após subir o container do docker, faça as migrações do banco rode:

```
npx prisma migrate dev
```

Ao terminar siga a proxima etapa para rodar o projeto:

Para rodar o projeto:

```
npm run dev
```

Ou utilize:

```
yarn dev
```
