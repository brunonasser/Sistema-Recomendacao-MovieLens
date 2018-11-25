# Sistema-Recomendacao-MovieLens

Sistema de Recomendação utilizando SVD
Introdução
A evolução da internet trouxe novas tecnologias como a de streaming de filmes e músicas nas quais os usuários têm acesso a milhares de produtos em um catálogo online sem ter a necessidade de baixa-los. O comercio eletrônico também sofre uma grande evolução nos últimos anos, além de grande número de sites oferecendo uma vasta gama de produtos tem-se plataformas de comparação de preços e sugestões de produtos para os usuários.

Com essa evolução toda o usuário tem disponível uma vasta quantidade de produtos a comprar nos marketplaces, ou filmes e músicas para assistir e ouvir, mas qual produto vai de acordo com o que o usuário precisa/quer comprar naquele momento? Ou qual filme ou música está mais adequado ao seu estilo? Neste sentido, surge a necessidade de uma recolha e organização da informação a ser oferecida ao usuário final para que este compre ou consuma o serviço que de fato necessita. Desta necessidade surgiram os sistemas de recomendação ou Recommender Systems (RS).

Os sistemas de recomendação possuem diferentes técnicas que diferem entre si pela forma como cada uma reúne e trata a informação relativa às preferências dos usuários. Dentro dos sistemas de recomendação um dos mais utilizados é a filtragem colaborativa ou collaborative filtering systems (CFS) que têm por base o seguinte pressuposto: se dois utilizadores classificaram/adquiriram produtos semelhantes no passado, então estes irão classificar/adquirir produtos semelhantes no futuro.

Em 2006 a Netflix abre um concurso que premia com US$1 milhão quem criar um sistema de recomendação mais eficiente e em 2009 a equipe vencedora implementando um algoritmo de filtragem colaborativa foi capaz de criar um sistema que oferece um erro 10% inferior ao do sistema utilizado pelo próprio Netflix. Em 2016 a Netflix mudou novamente o seu sistema de recomendação, criou-se um novo algoritmo que separa os assinantes em comunidades globais, independentemente de sua localização, e leva em consideração os gostos e preferências pessoais de cada usuário.

# Singular Value Decomposition (SVD)

Neste trabalho vamos utilizar o dataset MovieLens 20M que contem 20.000.263 ratings (avaliações) realizadas por 138.493 usuários aplicadas a 27.278 filmes. Como esse dataset apresenta as notas dadas pelos usuários aos filmes optou-se por utilizar o sistema de recomendação por filtragem colaborativa utilizando a técnica de decomposição de matriz por SVD. Esse sistema faz recomendações de itens desconhecidos a um usuário com base nos itens classificados anteriormente por outros cujo perfil ou gostos sejam similares ao do usuário ativo.
