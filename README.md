# Emotional Modeling Research

Este repositório contém o desenvolvimento de um projeto de pesquisa individual em fase inicial, com foco em modelagem personalizada de estados emocionais a partir de dados fisiológicos e autoanotações subjetivas. A proposta serve como base para ingresso futuro em um mestrado em neurociência computacional.

##  Objetivo Geral

Investigar a viabilidade técnica de construir modelos supervisionados individualizados para identificação de estados emocionais, utilizando sinais EEG e anotações subjetivas.

## Estrutura do Repositório

O projeto está organizado em fases, refletindo a evolução natural da pesquisa:

```
emotion-modeling-research/
├── 01-pipeline-validation/        # Etapa atual: validação técnica de pipeline
│   ├── notebooks/                 # Notebooks exploratórios e protótipos
│   ├── scripts/                   # Scripts reutilizáveis
│   ├── data/                      # Estrutura para dados públicos (sem dados brutos)
│   └── README.md                  # Detalhes desta fase
│
├── 02-adaptive-modeling/          # Etapa futura (mestrado)
│   ├── experiments/               # Testes com modelos adaptativos
│   └── README.md                  # Planejamento e objetivos dessa fase
│
├── docs/                          # Escopo do projeto, PDFs e anotações gerais
└── README.md                      # Este arquivo
```

## 📍 Fase Atual: Pipeline Validation

Nesta fase, o foco está em montar e validar tecnicamente um pipeline completo, com base em dados públicos como DEAP, SEED e DREAMER. As etapas envolvem:
- Análise da qualidade dos dados
- Pré-processamento de sinais EEG (remoção de ruído, bandas, entropia)
- Integração com rótulos emocionais subjetivos
- Treinamento de modelos supervisionados simples, um por indivíduo
- Avaliação estatística (treino/teste) para verificação da consistência do aprendizado

Caso viável, será realizada uma coleta pessoal com EEG de uso não invasivo para testar o funcionamento prático da estrutura.

## 🧭 Fase Futura: Adaptive Modeling

No mestrado, a pesquisa será aprofundada com a construção de um modelo adaptativo que aprenda progressivamente os padrões emocionais de cada pessoa, incorporando novos dados e feedbacks contínuos.

## 📄 Escopo da Proposta

O escopo detalhado do projeto está disponível em:  
[`docs/proposta_inicial.pdf`](docs/proposta_inicial.pdf)

---

*Este repositório está em desenvolvimento contínuo. Sugestões e referências são bem-vindas.*