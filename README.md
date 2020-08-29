![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rauanisanfelice/python-wine.svg)
![GitHub top language](https://img.shields.io/github/languages/top/rauanisanfelice/python-wine.svg)
![GitHub pull requests](https://img.shields.io/github/issues-pr/rauanisanfelice/python-wine.svg)
![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/rauanisanfelice/python-wine.svg)
![GitHub contributors](https://img.shields.io/github/contributors/rauanisanfelice/python-wine.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/rauanisanfelice/python-wine.svg)

![GitHub stars](https://img.shields.io/github/stars/rauanisanfelice/python-wine.svg?style=social)
![GitHub followers](https://img.shields.io/github/followers/rauanisanfelice.svg?style=social)
![GitHub forks](https://img.shields.io/github/forks/rauanisanfelice/python-wine.svg?style=social)


# Python Data Set

Projeto de classificação com Python e Machine Learning com uma base de Vinhos.

![Tela Início](https://raw.githubusercontent.com/rauanisanfelice/python-wine/master/img/wine.jpeg)

## Instalar;

```
pip3 install pandas
pip3 install sklearn
pip3 install matplotlib
pip3 install numpy
```

## Informações da Base:

Esses dados são os resultados de uma análise química de vinhos cultivados na mesma região da Itália, mas derivados de três cultivares diferentes. A análise determinou as quantidades de 13 constituintes encontrados em cada um dos três tipos de vinhos.

|Caracteristicas||
|:-----|:----:|
|Características do conjunto de dados|Multivariada|
|Número de instâncias|178|
|Área|Fisica|
|Características do Atributo|Inteiro, Real|
|Número de atributos|13|
|Data de doação|1991-07-01|
|Tarefas associadas|Classificação|
|Valores ausentes|Não|
|Número de acessos à Web|1219336|

Os atributos são (não indicados por Riccardo Leardi, riclea)
1) Álcool
2) Ácido málico
3) Cinza
4) Alcalinidade das cinzas
5) Magnésio
6) Fenóis totais
7) Flavonóides
8) Fenóis não flavonóides
9) Proantocianinas
10) Intensidade de cor
11) Cor
12) OD280 / OD315 de vinhos diluídos
13) Prolina

## Introdução

## Testes realizados:

Foi realizado teste com 1 algoritmo de Machine Learning de Classificação:

> Teste_Algoritmos.ipynb

* KMeans;


## Tabelas de resultados:
| Algoritmo  | Best Acurácia |
|:--|:--:|
| KMeans | 83.33% |

O KMeans por ter retornado a melhor acurácia foi utilizado no aplicativo

## Links;

[Data Set](https://archive.ics.uci.edu/ml/datasets/Wine)  
[Matplotlib](https://pythonspot.com/matplotlib-scatterplot/)  
[SkLearnf KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)

## Citações:

Dua, D. e Graff, C. (2019). Repositório de aprendizado de máquina da UCI [http://archive.ics.uci.edu/ml]. Irvine, CA: Universidade da Califórnia, Escola de Informação e Ciência da Computação.
