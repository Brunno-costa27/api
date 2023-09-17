# Api

## NLW IA - Construindo o back-end

Instalando as dependências do projeto

```bash
npm i typescript @types/node tsx -D
```
Instalando o fastify para utilizar na criação das rotas

```bash
npm i fastify
```
Instalando o prisma para gerenciar nosso banco de dados

```bash
npm i prisma -D
```

Inicializando o prisma 

```bash
npm prisma init --datasource-provider sqlite
```

Criando a migrate com o prisma 

```bash
npm prisma migrate dev
```

Abrindo banco de dados visual do prisma

```bash
npm prisma studio
```
Instalando dependência para fazer upload de arquivos

```bash
npm i @fastify/multipart
```

Instalando a biblioteca para validação

```bash
npm i zod
```


Instalando a biblioteca da openai

```bash
npm i openai
```

Instalando a biblioteca da dotenv para ler nossas variáveis de ambiente

```bash
npm i dotenv -D
```