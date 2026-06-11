# Priorização Inteligente de Chamados de TI

Este projeto tem como objetivo desenvolver uma solução de Inteligência Artificial para **classificar chamados técnicos de acordo com sua prioridade de atendimento**.

O trabalho foi desenvolvido com base no **Tema 08 – Priorização de Chamados de TI**, utilizando uma abordagem híbrida com:
- **Machine Learning** para classificação da prioridade;
- **Lógica Fuzzy** para representar criticidade de forma mais interpretável.

## Objetivo

O sistema analisa características de um chamado técnico e determina sua prioridade, auxiliando na tomada de decisão da equipe de suporte.

## Problema abordado

Em ambientes de suporte de TI, nem todos os chamados possuem o mesmo grau de importância. Alguns precisam ser atendidos imediatamente, enquanto outros podem aguardar mais tempo.  
Este projeto busca automatizar essa priorização com base em variáveis como:

- impacto;
- urgência;
- número de usuários afetados;
- tempo de espera;
- tipo de serviço.

## Tecnologias utilizadas

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Scikit-fuzzy

## Estrutura do projeto

```bash
.
├── data/
│   └── base_chamados_ti.csv
├── notebooks/
│   └── projeto_ia_priorizacao_chamados.ipynb
├── src/
│   ├── ml_model.py
│   ├── fuzzy_system.py
│   └── utils.py
├── README.md
└── relatorio_final.pdf
