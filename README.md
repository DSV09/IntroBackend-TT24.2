# IntroBackend-TT24.2
Códigos da aula sobre introdução ao backend e models, contendo:
* Exemplo de criação de models no arquivo schema.prisma
* Aplicação completa com a estrutura vista na aula

# Iniciando ambiente
Depois de instalar o Node e PostgreSQL como especificado em aula, abra o pgAdmin (que é instalado como padrão com o PostgreSQL) e crie o banco de dados como especificado em aula.

# Configurando
Vá no arquivo .env na variável `DATABASE_URL` e mude: 
* `<Senha>` Pela senha do seu usuário do banco de dados (que você criou ao instalar o postgreSQL)
* `<NomeDatabase>` Pelo nome do banco de dados que você criou no pgAdmin (no nosso exemplo era IntBackendDB)

# Instalando
Execute no diretório raiz do projeto (mesmo diretório que o arquivo `package.json`) o comando:
**npm install**

Para criar o schema do banco de dados conforme o schema.prisma execute o comando:
**npx prisma db push**

# Rodando a aplicação
Para rodar a aplicação execute:
**npm start**
