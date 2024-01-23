# ProjetoNotas - CRUD de Anotações Pessoais

Bem-vindo ao **ProjetoNotas**, um sistema completo de CRUD para gerenciar suas anotações pessoais. Este projeto utiliza o framework Laravel, Bootstrap para o front-end, JavaScript para interatividade e MySQL como banco de dados.

## Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas antes de começar:
- PHP 8.2
- Composer
- Laravel 10
- MySQL
- Node.js (para compilar assets)

## Configuração do Ambiente
1. Clone o repositório:
   ```bash
   git clone https://github.com/KayeneTeixeira/ProjetoNotas.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd ProjetoNotas
   ```

3. Instale as dependências do Composer:
   ```bash
   composer install
   ```

4. Copie o arquivo `.env.example` para `.env`:
   ```bash
   cp .env.example .env
   ```

5. Abra o arquivo `.env` e configure as informações do banco de dados.

6. Gere a chave de aplicativo:
   ```bash
   php artisan key:generate
   ```

7. Execute as migrações para criar as tabelas no banco de dados:
   ```bash
   php artisan migrate
   ```

8. Instale as dependências do Node.js e compile os assets:
   ```bash
   npm install
   npm run dev
   ```

## Executando o Projeto
Execute o servidor embutido do Laravel:
```bash
php artisan serve
```

Acesse a aplicação em [http://localhost:8000](http://localhost:8000) no seu navegador.

## Funcionalidades
- Adicionar, visualizar, editar e excluir anotações.
- Interface amigável utilizando Bootstrap.
- Interação dinâmica com JavaScript.

Divirta-se usando o **ProjetoNotas**! Caso tenha sugestões ou identifique problemas, sinta-se à vontade para contribuir abrindo issues ou enviando pull requests. 🚀