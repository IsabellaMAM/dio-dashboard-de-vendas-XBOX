# DIO-Dashboard-de-Vendas-XBOX

Desafio da plataforma DIO para desenvolver um Dashboard no Excel para análise das assinaturas do Xbox Game Pass. 

## Descrição

Este projeto consiste em um Dashboard no Excel como base as vendas de assinaturas do Xbox Game Pass com o objetivo fornecer uma visão detalhada sobre essas assinaturas realizadas, permitindo a análise de métricas essenciais e a comparação de períodos distintos.. 

## Implementar no Projeto

* Big Numbers de EA Play Season Pass e Microsoft Season Pass;

* Filtro de segmentação de dados sobre os períodos de assinaturas;

* Gráfico dinâmico com o Total de assinaturas do XBOX Game Pass, sendo auto-renovadas ou não.

## Como reproduzir

* Baixar o arquivo: Certifique-se de ter o arquivo Excel contendo a base de dados e o dashboard;

* Abrir no Microsoft Excel: O dashboard foi desenvolvido utilizando funcionalidades do Excel, como tabelas dinâmicas e segmentações de dados;

* Crie abas: Assets (elementos utilizados, como ícones, logo, também as paletas de cores), Bases (base de dados), Cálculos (Perguntas de negócio e suas respectivas respostas resultantes de informações com tabelas dinâmicas) e Dashboard (painel que exibirá os visuais para análise posterior do usuário);
*Quando finalizado o Dashboard, oculte as outras abas para o usuário só poder ter acesso ao que realmente importa para ele.*
  
* Crie os cards: Os Bigs numbers derivados da aba de Cálculos sobre os valores de Grand Total das tabelas dinâmicos com o campo de Subscription Type como filtro, o campo de Plan como linhas e campo de EA Play Season Pass para o card 1, já para o card 2 o campo de Microsoft Season Pass Price como valores;

* Crie o gráfico: O gráfico dinâmico derivado da tabela dinâmica com o campo Subscription Type como filtro, o campo de Auto Renewal como linhas e o campo de Total Value, mas Somando como valores;

* Crie os filtros: Os filtros disponíveis para alternar entre os períodos e visualizar as métricas na aba de Dashboard, refletido no filtro de segmentação de dados derivado da tabela dinâmica tbl_annual_total e tbl_easeasonpass_total;

* Layout: implemente os elementos da aba Assets no Dashboard e também disposição do menu através do dimencionamento das células para deixar de acordo com o que o usuário entenda e consiga análisar os visuais sem esforço, também pensando no serviços e plataformas que o usuário é mais habituado utilizar.

## Tecnologias

* Microsoft Excel

## Orientação Técnica

Felipe Aguiar (DIO)
