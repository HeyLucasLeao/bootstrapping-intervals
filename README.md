# Bootstrapping Intervals

Este projeto é apenas um estudo pessoal sobre diferentes intervalos de confiança utilizando diferentes métodos de bootstrapping. Ele inclui testes para os seguintes intervalos de confiança: normal, percentil, BCa (bias-corrected and accelerated), e t Studentizado.

## Objetivo

O objetivo é comparar e analisar a precisão e a aplicabilidade de diferentes métodos de intervalos de confiança bootstrap, também como seus graus de complexidade. 

## Métodos de Intervalo de Confiança

1. **Intervalo de Confiança Normal**: Utiliza a distribuição normal para calcular os limites do intervalo de confiança.
2. **Intervalo de Confiança Percentil**: Baseado nos percentis da distribuição das amostras bootstrap.
3. **Intervalo de Confiança BCa**: Corrige o viés e a aceleração na distribuição das estimativas bootstrap.
4. **Intervalo de Confiança t Studentizado**: Ajusta as estimativas bootstrap usando o erro padrão, similar ao t de Student.

## Referências

Para uma leitura mais aprofundada sobre intervalos de confiança bootstrap, você pode consultar o seguinte artigo:

- [Bootstrap confidence intervals: A comparative simulation study](https://arxiv.org/html/2404.12967v1)
