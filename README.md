# Beer House :beers:
Projeto de e-commerce/marketplace para disciplinas de Engenharia de Software e Desenvolvimento WEB - 5° Semestre, Ciência da Computação - Universidade Anhembi Morumbi (2018)

Com o termino do semestre, esse projeto serve apenas para estudo, sofrerá modificações aos poucos. 

Instruções para deploy da aplicação:

Laravel 5.6 - PHP > 7

Clonar o repositório:  https://github.com/lucaaslb/Beer-Marketplace

Criar um arquivo '.env' com as informações presentes no arquivo '.env.example'

No arquivo '.env' preencha as informações de conexão, nome do banco usuario e senha em seu respectivo campo

Na pasta do projeto, abra o terminal e execute os comandos:
 'composer install'
 'php artisan key:generate'
 'php artisan migrate'
 'php artisan storage:link'
 'php artisan db:seed'


 Feito isso, estará configurado e com as tabelas e algumas informações no banco.

 Para executar:
 'php artisan serve'

Mussum Ipsum - O melhor lorem ipsum do mundis http://mussumipsum.com/