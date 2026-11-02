# Análise de Dados de RH com Python e Pandas

Projeto acadêmico de análise exploratória de dados de recrutamento, desenvolvido durante os estudos de Inteligência Artificial.

## Objetivo
Explorar uma base de processos seletivos para compreender a distribuição de candidaturas por vaga, senioridade e fonte de recrutamento, observar os status dos processos e resumir indicadores numéricos.

## O que foi praticado
- Leitura de planilhas Excel com Pandas;
- Inspeção de dimensões, tipos de dados e estatísticas descritivas;
- Identificação e tratamento de valores ausentes;
- Identificação e remoção de registros duplicados;
- Conversão e preparação de colunas numéricas;
- Análise exploratória e visualização com Matplotlib.

## Base de dados
O projeto utiliza `base_rh10.xlsx`, disponibilizada para a atividade acadêmica. A planilha contém 1.224 registros e 11 colunas antes do tratamento. Na limpeza, foram identificadas 35 linhas duplicadas; após sua remoção, permaneceram 1.189 registros.

## Como executar
1. Baixe ou clone este repositório.
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra `Analise_de_Dados_RH_Pandas.ipynb` no Jupyter Notebook ou Google Colab.
4. Mantenha `base_rh10.xlsx` na mesma pasta do notebook. No Colab, se o arquivo não for encontrado, o notebook solicitará o upload.

## Arquivos
- `Analise_de_Dados_RH_Pandas.ipynb`: notebook com as etapas de análise.
- `base_rh10.xlsx`: base utilizada na atividade.
- `requirements.txt`: bibliotecas necessárias.

## Contexto acadêmico
Atividade prática desenvolvida em sala de aula, com orientação da professora Rita Cassiano. O notebook foi organizado para apresentação em portfólio, mantendo a identificação de sua natureza acadêmica.

## Observação
Os resultados descrevem exclusivamente a base disponibilizada para a atividade. Não representam necessariamente o comportamento de processos seletivos em outras organizações.
