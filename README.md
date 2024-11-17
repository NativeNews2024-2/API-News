# API-News

Uma API RESTful para gerenciamento de notícias.

## Descrição

Esta API fornece endpoints para o client do app, permite a criação de conta e o armazenamento de preferencias.  Ela é construída usando Node.js com Express.js e TypeScript para tipagem estática.

## Tecnologias

* **Node.js:** Ambiente de execução JavaScript.
* **Express.js:** Framework web para Node.js.
* **TypeScript:** Superconjunto de JavaScript com tipagem estática.
* **MySQL:** Banco de dados relacional (utilizando `mysql2`).
* **bcrypt.js:** Para criptografia de senhas.
* **jsonwebtoken:** Para autenticação JWT (JSON Web Tokens).


## Pré-requisitos

* Node.js e npm (ou yarn) instalados.
* Um banco de dados MySQL configurado.  Configure as variáveis de ambiente `DB_HOST`, `DB_USER`, `DB_PASSWORD`, e `DB_NAME` no arquivo `.env` (crie um se não existir) com as credenciais do seu banco de dados.

## Instalação

1. Clone o repositório: `git clone https://github.com/NativeNews2024-2/API-News.git`
2. Navegue até o diretório do projeto: `cd api-news`
3. Instale as dependências: `npm install`
4. Compile o código: `npm run build`

## Execução

* **Modo desenvolvimento:** `npm run dev` (usa `ts-node-dev` para recompilar automaticamente após alterações)
* **Modo produção:** `npm start` (executa a versão compilada)

## Endpoints

Descrição das rotas da aplicação:

* [placeholder]
* [placeholder]



## Testes

[Adicione informações sobre testes se houver, como comandos para execução e cobertura.]


## Contribuições

Contribuições são bem-vindas!  Por favor, abra um issue para reportar bugs ou sugestões de melhorias.  Siga as convenções de código existentes.

## Autores

- José Roberto 
- Franciso Macedo

## Licença

Este projeto é licenciado sob a licença (GPLv3)[https://www.gnu.org/licenses/quick-guide-gplv3.html] .