# Arquivos de linguagem do Laravel 5.5 - Português do Brasil

## Instalação

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone https://github.com/enniosousa/laravel-5.5-pt-BR-localization.git ./pt-BR
  ```
  
  Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -r pt-BR/.git/
  ```
  
2. Configurar o Framework para utilizar a linguagem como Default
  ```
  // Linha 81 do arquivo config/app.php
  'locale' => 'pt-BR',
  ```