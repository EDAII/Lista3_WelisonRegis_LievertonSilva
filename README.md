Lista 3 - Ordenação
=========================
Welison Lucas Almeida Regis - 2019.1

Lieverton Santos Silva - 2019.1

## PROPOSTA

- Utilizou-se os algoritmos **n.logn** **`quick sort`, `merge sort` e `bucket sort` aplicados em um `dataset`** (arquivo "athlete_events.csv") dos resultados da partipação dos atletas nos jogos olímpicos.
- O arquivo **csv** proposto possui **271117** registros de competidores. Para o dado problema, utilizou-se todos os registros dos atletas filtrando os campos de interesse — nome, sexo, time, NOC, jogos, cidade e evento.
- Também utilizou-se um dataset (arquivo "noc_regions.csv") dos países participantes.
- O objetivo do **`notebook`** é **apresentar informações dos jogos olímpicos**, como o número de atletas participantes por edição e o número de edições das olímpiadas que cada país participou, e utilizar os algoritmos de ordenação para ordenar os atletas por nome e, ao final, **gerar metodos de busca e apresentar os resutados encontrados em uma tabela**.
- É representado também a **comparação gráfica (histograma)** dos algoritmos de ordenação aplicado a todos atletas, assim como a **comparação gráfica (`Violin Box Plot`)** dos algoritmos de ordenação aplicados a vetores de diferentes tamanhos com atletas aleatórios.


## PRÉ-REQUISITO(S)
O projeto utiliza variável de ambiente (env) para a devida execução. Portanto:

1. Acesse o site da [Anaconda](https://www.anaconda.com/distribution/), baixe a versão mais recente do _software_ e instale.


## ACESSO À APLICAÇÃO
Para testar a aplicação, execute os seguintes passos:
1. Faça uma cópia do repositório para o seu computador em um lugar de sua preferência.
	* Através do _git_, faça um _git clone_:

```
    $ git clone https://github.com/EDAII/Lista3_WelisonRegis_LievertonSilva
```

2. Entre na pasta do projeto:
```
    $ cd Lista3_WelisonRegis_LievertonSilva
```

3. Crie o ambiente com os pré-requisitos do projeto através do conda:
```
    $ conda create --name sort_algorithms2 --file requirements.txt python=3.7
```

4. Ative o ambiente:
```
    $ conda activate sort_algorithms2
```

5. Abra o projeto com o jupyter notebook:
```
    $ jupyter notebook lista3_sort_algorithms2.ipynb
```

**Observação:** caso queira desativar o ambiente, digite `conda deactivate`; já se quiser remover o ambiente criado anteriormente, digite `conda env remove -n sort_algorithms2`.

## FUNCIONAMENTO
Com o notebook aberto, execute uma célula por vez:

```
    shift + ENTER
``` 
