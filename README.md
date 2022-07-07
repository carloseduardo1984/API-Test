# Simulacao REST API NodeJS


Referencia: https://github.com/UltimaSchool2022/Simulacao-REST-API-NodeJS
Itens necessários:
- Acesso a internet
-VsCode instalado
-Comandos prompt : cd , dir 


Baixe a pasta toda e extraia em seu computador

## Começando

### 1. Crie e Clone este repositório

* Abra o VSCode 
* Abra a pasta extraída do github no VsCode (no link de referencia acima)
* Abra o terminal do VsCode e insira os comando para criar o repositório na pasta:

* > `$git init`
* > `$git add .`
* > `$git commit -m "Iniciado projeto API e NodeJS"`
* > `$git remote... (inserir comando para link de seu repositorio do github)`
* > `$git branch -M main`
* > `$git push -u main`


### 2. Execute o servidor

```bash
 Abra o prompt do windows (comando cmd) e abra a pasta extraída para seu computador (utilize o comando cd)
 
 Instale o servidor Json (API Local)
 ```
  Comando> `npm install -g json-server`

  ```bash
  Execute o servidor com a base de dados
  ```

  Comando> `json-server --watch database.json`

## Acessando servidor local

- O servidor será executado em `http://localhost:3000`. Só abrir qualquer browser e digitar que será aberta a página inicial do API.

Você pode testar com o endpoint público: `http://localhost:3000/products` (método GET).

## Manipulando os dados
Com o Postment ou qualquer ferramenta de gestão de comunicação você pode alterar os dados de API, ou criar novas informações.

Para isso só utilizar os comandos abaixo.


#### Produtos

- Obter produtos: GET /produtos
- Obter produto por ID: GET /products/:id

#### Do utilizador

- Obter usuários: GET /users
- Obter usuário por ID: GET /users/:id
- Criar usuário: POST /users
- Atualizar usuário (informações completas): PUT /users/:id
- Atualizar usuário (informações parciais) PATCH /users/:id

#### Produtos
- Criar produto: POST /produtos
- Atualizar produto (informações completas): PUT /products/:id
- Atualizar produto (informações parciais) PATCH /products/:id


##### Exemplos de Filtros
http://localhost:3000/users/
http://localhost:3000/users/?status=false
