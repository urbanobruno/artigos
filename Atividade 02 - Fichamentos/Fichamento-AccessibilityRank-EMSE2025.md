# Accessibility Rank: A Machine Learning Approach for Prioritizing Accessibility User Feedback
Chai, Xiaoqi; Tizard, James; Blincoe, Kelly. "Accessibility Rank: A Machine Learning Approach for Prioritizing Accessibility User Feedback." Empirical Software Engineering, 2025. doi: [10.1007/s10664-025-XXXXX](https://doi.org/10.1007/s10664-025-XXXXX).

## 1. Fichamento de Conteúdo
O artigo propõe um método para priorizar automaticamente *feedbacks* de usuários que relatam problemas de acessibilidade em aplicativos, suprindo uma lacuna de técnicas de priorização que ignoravam esse recorte. Os autores avaliam sete algoritmos de aprendizado de máquina e três LLMs para ranquear *reviews* conforme o impacto na usabilidade e acessibilidade, usando um conjunto rotulado de 307 *reviews* e critérios de severidade definidos pelos próprios autores. Também comparam sua abordagem com uma ferramenta geral de priorização da literatura, mostrando queda de desempenho desta quando aplicada a acessibilidade. O modelo proposto (*Accessibility Rank*) alcança F1 ponderado de 83,6% e melhora especialmente a identificação de itens de alta prioridade. O trabalho discute implicações de equidade — como a sub-representação de grupos menos vocais em lojas de *apps* — e posiciona a técnica como parte de um *pipeline*: classificar *reviews* acessíveis, priorizá-los e só então ponderar fatores de negócio. Ameaças à validade incluem viés de rotuladores e cobertura de diretrizes; para mitigar, usaram dois codificadores com alta concordância. O artigo conclui que priorização específica para acessibilidade é necessária para evitar que requisições críticas sejam negligenciadas.

## 2. Fichamento Bibliográfico
* Definição dos critérios de prioridade focados em impacto na usabilidade e acessibilidade; *dataset* manualmente rotulado com 307 *reviews* (Seção 3).
* Comparação com priorizador geral (Malgaonkar et al.); desempenho cai ao priorizar acessibilidade (Seção 4).
* *Accessibility Rank*: F1 ponderado de 83,6% e +59,8% em F1 para classe 'alta prioridade' (Resumo/Resultados).
* Discussão de equidade em plataformas de *feedback* e visão de *pipeline* (Seção 5).
* Ameaças à validade e acordo entre codificadores de 91,4% (Seção 5.2).

## 3. Fichamento de Citações
* _"Our study addresses this limitation by developing a novel approach to analyze and prioritize app store reviews that discuss accessibility concerns.”_
* _"Accessibility Rank achieves a weighted F1 score of 83.6%.”_
* _"We envision Accessibility Rank being used as part of a pipeline to help developers identify the most pressing accessibility concerns.”_