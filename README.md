<h1 align="center">Análise e Visualização de Dados de Energia Eólica</h1>
<p align="center"><i>Repositório dedicado à análise de dados de energia eólica, com visualizações interativas e avaliação da potência ativa comparada à curva teórica.</i></p>

<p align="center" display="inline-block">
  <img src="https://img.shields.io/badge/Status-Ativo-brightgreen" alt="Status"/>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Seaborn-v0.11.2-yellowgreen?logo=seaborn&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Pandas-v1.5.0-green?logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Matplotlib-v3.4.3-red?logo=matplotlib&logoColor=white" alt="Matplotlib"/>
</p>

## Sobre este projeto

Este repositório contém o código para análise e visualização de dados de potência gerada por turbinas eólicas. O código compara a potência ativa real das turbinas com a curva teórica de geração de energia, mostrando a eficácia do desempenho. Além disso, o projeto inclui gráficos interativos para explorar a relação entre a velocidade do vento e a potência gerada.

### Objetivo

O objetivo deste projeto é avaliar o desempenho de turbinas eólicas, verificando se a potência ativa gerada está dentro da faixa aceitável em comparação com a curva teórica. Além disso, a análise ajuda a identificar os pontos onde a geração de energia está fora do esperado.

---

## Visualizações

### 1. **Distribuição da Potência Ativa vs Velocidade do Vento**
Um gráfico de dispersão que mostra a relação entre a velocidade do vento e a potência ativa gerada pela turbina.

![graf](https://github.com/user-attachments/assets/4b34d2ab-dd84-4e7d-9f79-0e855fa75dd7)


**Explicação**: Este gráfico ajuda a visualizar como a velocidade do vento influencia a potência ativa gerada pela turbina, o que é essencial para entender a eficiência das turbinas eólicas.

### 2. **Curva Teórica de Potência**
Mostra a relação entre a velocidade do vento e a curva teórica de geração de energia para a turbina.

![fasd](https://github.com/user-attachments/assets/949f4100-0c4b-400c-9d6c-909bd8ac6536)

**Explicação**: A curva teórica mostra a potência que se espera gerar com base na velocidade do vento, fornecendo uma referência para comparação com os dados reais.

### 3. **Potência Real vs Potência Teórica**
O gráfico de dispersão que exibe os pontos onde a potência gerada está dentro ou fora da faixa aceitável.

![asdasdasd](https://github.com/user-attachments/assets/5afc0430-c10a-40e0-9725-025529126521)


**Explicação**: Este gráfico mostra os pontos onde a potência real está dentro ou fora dos limites aceitáveis (5% acima ou abaixo da potência teórica), indicando possíveis problemas com a eficiência da turbina.

---

## Como Rodar o Projeto

1. Clone o repositório:
```bash
  git clone https://github.com/cf-neto/Monitoramento-de-Energia-Eolica.git
