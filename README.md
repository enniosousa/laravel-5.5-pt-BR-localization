# Arquivos de linguagem do Laravel 5.5 - Português do Brasil

O arquivo README.md foi baseado no do repositório [Leomhl/laravel-5.4-pt-br-localization](https://github.com/Leomhl/laravel-5.4-pt-br-localization). A tradução foi feita por mim a partir dos arquivos originais do Laravel na versão 5.5 <s>(que é em inglês)</s>

## Instalação

1. Clonar este projeto na pasta `resources/lang/` do seu projeto
  ```
  $ cd resources/lang/
  $ git clone https://github.com/enniosousa/laravel-5.5-pt-BR-localization.git ./pt-BR
  ```
  
  Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -r pt-BR/.git/
  ```
  
  Se você estiver usando Windows Server ou Azure
  ```
  rd /s /q pt-BR/.git/
  ```
  
2. Configurar o Framework para utilizar a linguagem como Default
  ```
  // Linha 81 do arquivo config/app.php
  'locale' => 'pt-BR',
  ```
