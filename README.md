
# Predição de falhas utilizando Self-Training Classifier

Esse projeto trata-se da aplicação de um modelo semi-supervisionado, que conta com target labels em apenas um dos conjuntos de dados. O objetivo é encontrar dois agrupamentos, os de falha e não falha, de forma a identificar padrões escondidos nos dados, que possam predizer essa informação. Após os dados serem pré-processados, foi aplicado o modelo supervisionado Random Forest e o semi-supervisionado Self-Training Classifier, ambos da biblioteca sklearn.



## Instalação

Para funcionamento do modelo instale os pacotes do documento a seguir:

requirements.txt
## Arquivos

O projeto está dividido nos seguintes arquivos:

* requirements.txt - Bibliotecas usadas

* analise-exploratoria.ipynb - Análise estatística preliminar

* modelo-previsao.ipynb - Código completo do modelo desenvolvido

* predicted.csv - Arquivo final com as previsões

## Dados

Os dados utilizados foram fornecidos pela empresa Indicium.
## Créditos

Projeto desenvolvido por mim, Fernanda Oliveira.

