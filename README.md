[pythonclub.com.br][0]
======================

Blog colaborativo sobre tecnologias que envolvam a linguagem Python


Como Contribuir
---------------

* Faça um fork desse repositório
* Clone seu fork:

    ``git clone --recursive https://github.com/SEU_USUARIO_DO_GITHUB/pythonclub.github.io.git``

* Instale os requirements ``pip install -r requirements.txt``
* Todas as publicações ficam na pasta ``content``, os textos podem ser escritos
  no formato **[Markdown][4]** ou **[reStructuredText][5]**, fique a vontade
  para usar o que você sentir mais afinidade, veja alguns **[exemplos][6]**.
* Após criar ou editar seu artigo faça um pull-request para que ele seja
  adicionado ao site.


Informações Técnicas
--------------------

O site está sendo hospedado usando o **[Github Pages][1]**. Ele hospeda arquivos
HTML sem qualquer tipo de custo, bastando que exista um repositório
chamado ``seu-usuario.github.io`` o que faz com que qualquer arquivo HTML
existente na branch ``master`` seja servido numa web.

Para gerar esses arquivos
HTML utilizamos o **[Pelican][2]**, que é um projeto feito em Python.

Como a branch ``master`` é usada internamente pelo Github para servir os
arquivos HTML. Criamos uma branch chamado ``pelican`` para armazenar os arquivos
de configuração e as publicação em seu "estado-bruto". Essa branch está definida
como padrão para o repositório e você possivelmente não precisará se preocupar
com isso.


Visualizando sua publicação antes de enviar
-------------------------------------------

O **Pelican** conta com algumas facilidades que permitem que você teste o site
localmente na medida que você vai escrevendo o texto e antes de enviar para o
servidor, inclusive vem com um script para facilitar isso.

Para utilizar o script para iniciar basta
executar o comando:

``./develop_server.sh start``

Então basta visitar o endereço [http://localhost:8000/][3]

Para finalizar o servidor use:

``./develop_server.sh stop``

Futuras Publicações
-------------------

| Autor                   | Assunto                                                                       | Data       |
|-------------------------|-------------------------------------------------------------------------------|------------|
| Eric Hideki             | Como colaborar na tradução do Djangobook sem conhecer programação             | 29/04/2014 |
| Renato Oliveira         | Introdução ao django.contrib.auth                                             | 03/05/2014 |
| Régis da Silva          | As 20 principais dúvidas que atormentam um iniciante em Django                | ?          |
| Gilmar Soares           | Parseando sites com BeaultifulSoup                                            | 16/05/2014 |
| Fábio Barrionuevo       | Limpando automaticamente o cache do Django ao fazer deploy no Heroku          | 17/05/2014 |
| Igor Santos             | 5 Django Apps que não vivo sem                                                | 06/05/2014 |
| Guilherme Rezende       | Criando uma ferramenta de pentest com Python, Nmap e Scapy                    | 12/05/2014 |
| Fabiano Góes            | Seu primeiro projeto Django com Sublime Text no Linux                         | 12/05/2014 | 
| Rômulo Collopy          | Deploy de projetos com Django-Fagungis                                        | 05/05/2014 |
| Rafael Trevisan         | Entendendo versionamento com Git                                              | 10/05/2014 |
| Artur Felipe Sousa      | O que é six e como ele te ajuda a escrever código compatível com python 2 e 3 | 29/04/2014 |
| Francisco André         | Configurando um servidor de repositórios Git                                  | 15/05/2014 |
| Anderson Rodrigues      | Configurando Django com Framework Twitter Bootstrap e Foundation              | 10/05/2014 |
| Maurício Sipmann        | Editando o template do admin do django com templatetags                       | 15/05/2014 |

[0]: http://pythonclub.com.br/
[1]: https://pages.github.com/
[2]: http://docs.getpelican.com/en/3.3.0/
[3]: http://localhost:8000/
[4]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[5]: http://docutils.sourceforge.net/docs/user/rst/quickref.html
[6]: https://github.com/pythonclub/pythonclub.github.io/tree/pelican/exemplos
