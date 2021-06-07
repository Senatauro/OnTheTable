.. Documentação .rst para o ReadTheDocs, escrito por Carlos Gabriel Silva Stedile para o projeto On The Table. 2021

=========================
Documentação da API
=========================

Bem vindo a documentação dos serviços de Backend(GraphQL e autenticação com Cognito) que serão utilizados no projeto do On The Table

Este documento possui o objetivo de exibir as operações existentes, como utiliza-las e exemplos ações corriqueiras

Essa documentação foi escrita com o desenvolvimento utilizando o React em ment

==================================================

Conteudo:

.. toctree::
   :maxdepth: 2
   :caption: Introdução

   1_authors.rst
   2_instalacao.rst
   3_banco_de_dados.rst


.. toctree::
   :maxdepth: 2
   :caption: AppSync

   4_appsync.rst
   5_operacoes.rst


.. toctree::
   :maxdepth: 2
   :caption: Cognito

   6_cognito.rst


.. toctree::
   :maxdepth: 2
   :caption: Exemplos Query

   ./operacoes/query/getParticipante.rst
   ./operacoes/query/getEvento.rst
   ./operacoes/query/getParticipando.rst


.. toctree::
   :maxdepth: 2
   :caption: Exemplos Mutation

   ./operacoes/mutation/createParticipante.rst
   ./operacoes/mutation/createEvento.rst


.. toctree::
   :maxdepth: 2
   :caption: Exemplos de funções especiais

   ./operacoes/mutation/enviarEmail.rst