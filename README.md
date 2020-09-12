<p align="center">
  <a href="https://roots.io/bedrock/">
    <img alt="Bedrock" src="https://cdn.roots.io/app/uploads/logo-bedrock.svg" height="100">
  </a>
</p>

## Funcionamento

<img src="https://i.ibb.co/q5g11sw/ezgif-4-c91e52031f95.gif" />

## Banco de dados 

- Está na root (wp.sql)
- O banco de dados tem 10mb , caso necessario no php.ini coloque o campo "upload_max_filesize=64M"

## URL Para Acessar 
http://localhost/Rits/Web/


## Configuração .env
* Renomeie o arquivo .env.example para .env
* Dentro do .env apenas substituia tudo pelo código abaixo
---------------------------------------------------------------------
- DB_NAME='wp'
- DB_USER='root'
- DB_PASSWORD=''
- WP_ENV='development'
- WP_HOME='http://localhost/Rits/Web/'
- WP_SITEURL="${WP_HOME}/wp"
- WP_DEBUG_LOG=/path/to/debug.log




