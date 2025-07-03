# MVP Campeonato Brasileiro – Análise de Dados e Odds
Nome: Diogo Kelmer

Acesso ao código:
[Google Colab - MVP Campeonato Brasileiro](https://github.com/diogokelmer/MVP_Trabalho/blob/main/MVP_Diogo_Kelmer_4052025000826.ipynb)

## Descrição do Projeto
Este projeto analisa partidas da Série A do Campeonato Brasileiro a partir de dados históricos, incluindo resultados e odds oferecidas por casas de apostas. 

## Hipóteses Avaliadas
- As odds oferecidas pelas casas de apostas refletem, de forma geral, a tendência do resultado final da partida.
- Jogos com odds muito diferentes entre os times indicam um favoritismo mais claro e, possivelmente, um resultado mais previsível.
- Times mandantes costumam ter odds menores para vitória, o que pode indicar uma vantagem histórica jogando em casa.
- O Flamengo é o time que mais converteu favoritismo, jogando em casa, em vitórias.

## Tipo de Problema
Análise exploratória com foco descritivo. 

## Dataset
Utilizado o [dataset Futbr](https://www.kaggle.com/datasets/saulocampos/estatsticas-do-campeonado-brasileiro?resource=download), contendo informações das partidas da Série A: nome dos times, gols marcados, resultado, odds (PH, PD, PA) de casas como Pinnacle e OddsPortal.

## Pré-processamento
- Remoção de valores nulos (menos de 1% dos dados).
- Padronização de nomes de times, colunas de país e liga.
- Tradução de rótulos de resultados (Res) para português.
- Cálculo de variáveis auxiliares: diferença de odds, acerto da aposta, favoritismo, etc.

## Conclusão
- Hipótese 1: Falsa. 
- Hipótese 2: Verdadeira. 
- Hipótese 3: Falsa.
- Hipótese 4: Falsa.
