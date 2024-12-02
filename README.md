# Bootstrapping Intervals

Este projeto é um estudo pessoal sobre diferentes intervalos de confiança utilizando métodos de bootstrapping. Ele inclui testes para os seguintes intervalos de confiança: normal,básico, percentil, BCa (bias-corrected and accelerated), e t Studentizado.

## Objetivo

O objetivo é comparar e analisar a precisão e a aplicabilidade de diferentes métodos de intervalos de confiança bootstrap, além de avaliar seus graus de complexidade.

## Métodos de Intervalo de Confiança

1. **Intervalo de Confiança Normal**: Utiliza a distribuição normal para calcular os limites do intervalo de confiança.
2. **Intervalo de Confiança Básico**: Corrige o viés na distribuição para calcular os limites do intervalo de confiança.
3. **Intervalo de Confiança Percentil**: Baseado nos percentis da distribuição das amostras bootstrap.
4. **Intervalo de Confiança BCa**: Corrige o viés e a aceleração na distribuição das estimativas bootstrap.
5. **Intervalo de Confiança t Studentizado**: Ajusta as estimativas bootstrap usando o erro padrão, similar ao t de Student.

## Referências

Para uma leitura mais aprofundada sobre intervalos de confiança bootstrap, você pode consultar o seguinte artigo:

- [Bootstrap confidence intervals: A comparative simulation study](https://arxiv.org/html/2404.12967v1)

Os dados utilizados como exemplo podem ser baixados [aqui](https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors).
