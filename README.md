# K-Nearest-Neighbors
K-NN é um algoritimo de Machine Learning que busca resolver problemas de otimização, semelhante ao do caixeiro viajante.
>O Problema do Caixeiro Viajante (PCV) é um problema que tenta determinar a menor rota para percorrer uma série de cidades (visitando uma única vez cada uma delas), retornando à cidade de origem. Ele é um problema de otimização NP-difícil inspirado na necessidade dos vendedores em realizar entregas em diversos locais (as cidades) percorrendo o menor caminho possível, reduzindo o tempo necessário para a viagem e os possíveis custos com transporte e combustível.

# Tipos de Distancia

**Table of Contents**

[TOCM]

[TOC]

#H1 header
##H2 header
###H3 header
####H4 header
#####H5 header
######H6 header
#Heading 1 link [Heading link](https://github.com/pandao/editor.md "Heading link")
##Heading 2 link [Heading link](https://github.com/pandao/editor.md "Heading link")
###Heading 3 link [Heading link](https://github.com/pandao/editor.md "Heading link")
####Heading 4 link [Heading link](https://github.com/pandao/editor.md "Heading link") Heading link [Heading link](https://github.com/pandao/editor.md "Heading link")
#####Heading 5 link [Heading link](https://github.com/pandao/editor.md "Heading link")
######Heading 6 link [Heading link](https://github.com/pandao/editor.md "Heading link")

Distancia Euclidiana
-------------
$$\ \sqrt{\sum_{i=0}^{n-1}(a_i - b_i)^2}$$

A Distancia Euclidiana é simetrica e trata todas as dimensões de forma igual. Entretanto, ela é extremamente sensivel aos valores extremos (outliers)

Distancia de Minkowski
-------------
$$\ \left [\sum_{i=0}^{p} \left | x_i -y_i \right |^{m}\right ]^{1/m} $$

Generalização da distancia Euclidiana

Distancia de Hamming
------------
$$\\sum_{i=1}^{k} \left | x_i - y_i \right | $$

Muito utilizado para atributos categoricos. A função principal da função de hamming é verificar se dois atributos são iguais ou não (se forem iguais a distancia é 0 se forem diferentes =1) 


Distancia Manhattaan / L1
-------------
$$\\sum_{i=1}^{k} \left | x_i - y_i \right | $$
-------------
A distancia Manhattaan é o modulo da distancia entre dois pontos (é a soma das diferenças absolutas de suas coordenadas). Seu nome faz alusão ao formato quadriculado da maior parte das ruas na ilha de Manhattan.Tal configuração faz com que a menor distância a ser percorrida por um carro que vai de um ponto a outro na cidade tenha como valor aquele número fornecido pela métrica L1.          


----

```

###Images

Image:

![]([https://pandao.github.io/editor.md/examples/images/4.jpg](https://www.sakurai.dev.br/assets/images/posts/2019-06-21-revisao-algebra-linear-python-06.png))

> Follow your heart.

![](https://pandao.github.io/editor.md/examples/images/8.jpg)

> 图为：厦门白城沙滩 Xiamen

图片加链接 (Image + Link)：

[![](https://pandao.github.io/editor.md/examples/images/7.jpg)](https://pandao.github.io/editor.md/examples/images/7.jpg "李健首张专辑《似水流年》封面")

> 图为：李健首张专辑《似水流年》封面
                
----
