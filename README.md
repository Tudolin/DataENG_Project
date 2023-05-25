# DataENG_Project
Study projetct form Data Engineer.

Neste projeto, utilizei uma base de dados pública do Kaggle com a finalidade de Selecionar apenas os 20 melhores smartphones do ano de 2019 baseado na nota de avaliação.

Iniciei o projeto importando a base de dados;

Em seguida, dei inicio a limpeza de dados, exluindo as colunas que não seriam úteis para mim e renomeando as que restaram de maneira que facilitace a leitura e entendimento dos dados, ex: 'brand' = nm_marca, 'title' = ds_produto, 'price' = vlr_produto..
Verifiquei as etradas vazias e preenchi com "vazio" e realizei a exclusão de duplicatas;

Após limpos, comecei a filtragem condicional, organizando de maneira DESC, com o minimo de 15 avaliações, selecionando apenas os 20 primeiros;

Em seguida salvei o arquivo.
