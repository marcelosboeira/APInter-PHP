APInter-PHP
===========

Projeto com o início de uma biblioteca para a utilização das APIs fornecidas pelo Banco Inter (077).

Inicialmente apenas a criação de boletos é suportada.

Como usar:
----------

### Instalação

Para utilizar a biblioteca através do composer:

#### Versão estável

```
composer require "ctodobom/api-inter"
```

#### Versão de desenvolvimento principal

```
composer require ctodobom/api-inter:dev-main
```

### Documentação 

O arquivo [exemplo.php](exemplo.php) fornece o básico para a utilização das classes.

Os parâmetros para a execução do exemplo devem ser salvos no arquivo com o nome `.env`, exemplos de configuração encontram-se no arquivo `.env.example`

> **ATENÇÃO:**
>
> Todos os dados verificáveis precisam ser válidos Utilize sempre CPF/CNPJ, CEP, Cidade e Estado válidos Para evitar importunar estranhos utilize seus próprios dados ou de alguma pessoa que esteja ciente, pois as cobranças sempre são cadastradas no sistema quente do banco central e aparecerão no DDA dos sacados. Os dados de exemplo NÃO SÃO VÁLIDOS e se não forem alterados o script de exemplo não funcionará.

Licença
-------

Todo o código deste projeto está licensiado sob a GNU Lesser General Public License versão 3.

Pode ser utilizado inalterado em qualquer projeto fechado ou open source, alterações efetuadas precisam ser fornecidas em código aberto aos usuários do sistema.

Facilitou sua vida?
-------------------

Se o código do projeto ajudou você em uma tarefa complexa, considere fazer uma doação ao autor pelo PIX abaixo.

![image](https://github.com/allgood/APInter-PHP/assets/6070736/e595bcdf-5903-4ee1-99c7-1f8ba7b59f8a)

Chave Pix: 80fd8916-1131-4844-917e-2732eaa2ba74
