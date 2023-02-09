# Procedure
/* Uma empresa de vendas tem um banco de dados com informações sobre os seus produtos. Ela precisa criar um relatório que faça um levantamento diário da quantidade de produtos comprados por dia. Para ajudar a empresa, crie um procedure para agilizar esse processo*/.

CREATE PROCEDURE levantamentoDiario (produtos smallint)

select concat('A quantidade é', unidade) AS unidades

from tabela_produtos

where id_produtos = produtos;
