## 📍 Fase Atual: Pipeline Validation

Essa etapa servirá como fundação técnica do projeto, o objetivo é montar e validar um pipeline completo para integrar sinais EEG e anotações subjetivas de estados emocionais com foco em personalização por indivíduo. As atividades incluem:
Analisar a qualidade dos dados coletados e selecionar os trechos e sujeitos mais adequados para uso;

- Construir uma rotina de pré-processamento dos sinais, incluindo remoção de ruídos, normalização e extração de características como bandas de frequência e entropia;
- Integrar os rótulos subjetivos com os dados fisiológicos de forma organizada e sincronizada;
- Treinar modelos supervisionados simples, individualizados por sujeito;
- Avaliar a consistência e o funcionamento técnico do pipeline como base para aprofundamentos futuros.


Além disso, caso tenha acesso ao equipamento necessário,  pretendo realizar uma coleta de dados comigo mesma utilizando um EEG não invasivo. Essa etapa tem como objetivo testar, na prática, a execução completa do pipeline com dados reais em ambiente não controlado, funcionando como exercício técnico e validação funcional.
Os dados eventualmente coletados não serão utilizados para análises clínicas nem para conclusões sobre estados emocionais, mas apenas para verificar se as etapas do processo (do pré-processamento à modelagem supervisionada)  operam conforme o esperado. A avaliação dos modelos será feita com divisão entre treino e teste, respeitando a estrutura individual dos dados. O foco estará em identificar se os algoritmos conseguem aprender padrões consistentes a partir dos rótulos subjetivos, sem extrapolar esses resultados para aplicações generalizadas.
