# System-Laravel
Introduction to laravel

## Requisitos
- php: adicionando alguns atentos (no docs)
- cmder: emulador windows (promt command)
- artisan: o console de comandos
- composer: gerenciador de pacotes do php
- ide: phpStorm

## Instalação
- composer create-project --prefer-dist laravel/laravel 'name-project' 5.3 
- ficar atento se gerou uma chave 'php artisan key:generate'
- rodar servido do php: php artisan serve
- uns dos mais importantes arquivos: 
.env -> pode configurar bancos de dados, app_key, endereço do site, configurações de email

## Servidor
- o .env não vai subir junto ao servidor (prodution)
- 'name-project'/config toda parte de configuração

## diretórios
- principal: /app
  -> user.php esta os modelos do sistema
  -> /middleware autenticações de token
  -> /providers arquivos de configurações
- routes
  -> definição de rotas via web (web.php) e servidor (api.php)
- database
  -> pastas de facilitadores no gerenciamento do banco de dados
- public: pasta root
- resources
  -> /views parte visual do sistema layouts 'blade.php'
