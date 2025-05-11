# Emotional Modeling Research

Este repositório contém o desenvolvimento de um projeto de pesquisa individual em fase inicial, com foco em modelagem personalizada de estados emocionais a partir de dados fisiológicos e autoanotações subjetivas. A proposta serve como base para ingresso futuro em um mestrado em neurociência computacional.

##  Objetivo Geral

Desenvolver uma abordagem personalizada para reconhecimento de estados emocionais a partir de sinais EEG combinados com auto anotações subjetivas. O foco de curto prazo é montar e validar tecnicamente um pipeline supervisionado, capaz de processar esse tipo de dado de forma individualizada. Nesta primeira etapa, serão utilizados dados públicos e, se viável, uma coleta própria com EEG de uso pessoal, com o objetivo de testar o funcionamento do pipeline de ponta a ponta.
A partir dessa fundação, o projeto será aprofundado no mestrado com o objetivo de construir um modelo adaptativo capaz de aprender ao longo do tempo  os padrões emocionais específicos de cada indivíduo, lidando com novos dados e feedbacks contínuos. Em longo prazo, a intenção é aplicar esse conhecimento na criação de sistemas inteligentes voltados à saúde mental, com foco em suporte emocional personalizado e prevenção de crises.

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


Nesta fase, o foco está em montar e validar tecnicamente um pipeline completo.
- Buscar dados públicos
- Análise da qualidade dos dados
- Pré-processamento de sinais EEG (remoção de ruído, bandas, entropia)
- Integração com rótulos emocionais subjetivos
- Treinamento de modelos supervisionados simples, um por indivíduo
- Avaliação estatística (treino/teste) para verificação da consistência do aprendizado

Caso viável, será realizada uma coleta pessoal com EEG de uso não invasivo para testar o funcionamento prático da estrutura.

[`01-pipeline-validation/README.md`](01-pipeline-validation/README.md)

## 🧭 Fase Futura: Adaptive Modeling

No mestrado, a pesquisa será aprofundada com a construção de um modelo adaptativo que aprenda progressivamente os padrões emocionais de cada pessoa, incorporando novos dados e feedbacks contínuos.

## 📄 Escopo da Proposta

O escopo detalhado do projeto está disponível em:  
[`docs/proposta_inicial.pdf`](docs/proposta_inicial.pdf)

---

*Este repositório está em desenvolvimento contínuo. Sugestões e referências são bem-vindas.*